# Hello, Im Ethan!

- 𝗜 𝗮𝗺 𝗮 𝗽𝗿𝗼𝗴𝗿𝗮𝗺𝗺𝗲𝗿 𝗶𝗻 𝗵𝗶𝗴𝗵 𝘀𝗰𝗵𝗼𝗼𝗹
- 𝗜 ❤️ 𝗟𝗼𝘄 𝗟𝗲𝘃𝗲𝗹 𝗣𝗿𝗼𝗴𝗿𝗮𝗺𝗺𝗶𝗻𝗴!

```julia
module main

aboutMe :: struct {
  pronouns :: string[];
  languages :: string[];
  hobbies :: string[];
  funFact :: string;
}

main :: func(): void {
  ethan :: aboutMe = {
    pronouns: ["He", "Him"],
    languages: ["C", "C#", "Java", "Python"],
    hobbies: ["Coding", "Gaming", "Talking"],
    funFact: "The first computer virus was created in 1983!"
  };

  println "Pronouns: ${ethan.pronouns}";
  println "Languages I Know: ${ethan.languages}";
  println "My Hobbies: ${ethan.hobbies}";
  println "Fun Fact: ${ethan.funFact}";
}
```
