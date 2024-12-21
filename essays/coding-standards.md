---
layout: essay
type: essay
title: "Coding Standards: ESLint with VSCode"
# All dates must be YYYY-MM-DD format!
date: 2024-09-25
published: true
labels:
  - Coding Standards
  - ES Lint
  - VSCode
---

<img height="150px" class="rounded float-start pe-4" src="../img/e28_coding-standards-reflection/programming.png">

## Importance of Coding Standards

Many people have different styles of writing. Some are better at short stories. Some like poetry. That can be said about programming languages, too. People write their code in their own style. However, as more and more people are learning to do their coding, there must be a standard in which everyone has more or less the same structure in their code. Because of a coding standard, reading another person’s code will be much easier.

Emphasizing the benefits of adhering to coding standards, I agree that they are indeed essential. I was taught that a program's functionality alone does not define good code. There are always ways to simplify and optimize the code. More importantly, it should be readable to other programmers. If your code contains an error, will someone be willing to review it? Or will they be deterred by its “messiness”? Therefore, as Antra Verma’s <a href="https://www.browserstack.com/guide/coding-standards-best-practices">Coding Standards and Best Practices to Follow</a> suggests, coding standards are crucial for readability, collaboration, consistency, scalability, error prevention, and maintenance.

### Previous Experience with Coding Standards
I had very good programming mentors and peers when I first learned programming. They have ingrained in me a very orderly and organized way of programming. However, as I progressed, I lost some of those teachings. For example, I was taught to put the first letter of the type in the variable name. An integer holding the speed of a motor would be called iSpeed, and even more specific, iLeftFrontSpeed. A string will start with a lowercase ‘s,’ doubles with a lowercase ‘d,’ and so on.

They emphasized how we wrote code because we worked as partners, and each pair contributed something to the team. They made sure that what we wrote was readable to everyone. Therefore, these practices have been with me throughout the years.

<img height="150px" class="rounded float-start pe-4" src="../img/e28_coding-standards-reflection/eslint.png">

### ESLint with VSCode
After my first week of using ESLint with VSCode, I found it useful and painful. There are some things that I like to keep things consistent, such as the spacing between operators or the curly brackets opening on the same line as the function header or keyword. By using ESLint, I can keep consistency. However, there are small things in ESLint that do not pass, such as putting a type for every variable. It is a good practice. However, there are some temporary variables where the type does not need to be explicitly declared, in my opinion.

It is not that big of a deal when writing these small programs and working with only a few people. However, when it comes to more significant projects and collaborative groups, having a coding standard helps everyone. However tedious and painful it may be to upkeep these do’s and don’ts, it will save you from more pain later on.
