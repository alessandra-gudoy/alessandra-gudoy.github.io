---
layout: essay
type: essay
title: "Design Patterns"
date: 2024-12-04
labels:
  - Software Engineering
  - Design Patterns
---

## Don’t Reinvent the Wheel

<img src=”../img/e63_design-patterns/wheels.jpeg” />

“Don’t reinvent the wheel” is a common phrase saying to use what already exists to save time and effort. Similarly, design patterns describe a recurring problem and define the solution in a way that can be applied without it being done the same way before. The essential characteristics of the wheel are still there, but we have built upon it. The problem may differ depending on the environment, situation, and other variables; however, the described solution allows one to apply the same thinking to solve the problem. In other words, a design pattern is a blueprint for how to solve a problem.

It is a simple concept to grasp yet very revolutionary. Because of design patterns, new people have a starting point to work with. Is there a problem where you don’t know where to start? That problem most likely has been solved a million times before. And if we look at the solutions to all those similar problems, they all have the same “heart” of the solution.

## Following Tracks

“Monkey see, monkey do” is another phrase that means to learn something through imitation. As a student starting their journey in computer science, I have often found myself looking at examples to understand how to solve different problems. Broadening the saying, 

One design pattern that I have used is the observer design pattern. It is used when we want to know when something has changed. For example, Minecraft has an observer block that sends a redstone signal when the block in front of it changes. Similarly, like in the <a href="https://react.dev/learn/tutorial-tic-tac-toe">React Tutorial of Tic-Tac-Toe</a>, when we click on a square, we want to show an “X” or “O,” or if there are three in a row, column, or diagonal, the game lets us know when a player has won. The square is waiting for the event that the user clicks on the square. The game was waiting for the event that three squares in a line were in the same state.