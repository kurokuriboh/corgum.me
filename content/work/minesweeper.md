---
title: Internet Multiplayer Minesweeper
comments: false
date: 2017-04-04
enableQuarterDate: true
quarterDate: 2017, Spring
description: A client-server model for multiplayer minesweeper game.
---
### About
---
This project was a final project for UW's Computer Networks course.

**Team Members:** Hiep Can, Reilly Mulligan, Ricky Chai

### Project goals
---
{{% center %}} ![Minesweeper Game](image/minesweeper.gif) {{% /center %}}  

Minesweeper is a fun and interesting game that lets people clear a board containing hidden mines without detonating any of them. This project turns a simple single-player puzzle game into a multiplayer one with the goal of making it accessible by many people at the same time. With Socket Programming, this project aims to create a distributed and multi-threaded system that makes every action instantaneous over the network.

### Contributions
---

- Implemented a client-server model with a central server distributing payloads to sockets through multiple threads.
