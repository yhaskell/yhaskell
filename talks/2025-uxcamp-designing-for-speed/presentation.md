---
title: Designing for speed
author: yhaskell
data-theme: funky
---

# Designing for _Speed_

by Igor Dultsev

_this is a rant_

by [`Igor Dultsev`](https://github.com/yhaskell) for UX Camp Europe 2025

---

_<h1>J I R A</h1>_

---

![](./create-issue-jira.gif)

---

I wanted to do this talk because of this video 😂

---

![](./create-issue-linear.gif)

---

Feels different, right?

---

## There are actually topics I wanted to talk about

Not only show the videos 😊

---

### Topics

- What to do if your software is slow
- What to do if your software is :star:fast:star:
- Desiginer's responsibility
- Local-first

---

## What to do if your software is slow

- (Captain Obvious) make it _faster_!
- Push your PM to prioritise speed
- Push your developers to prioritise speed
- Often only possible for new software 😢

---

## Some things simply cannot be made faster

- Should we do an async?
- Should we put a loading spinner 🤮?
  - Many(!) loading spinners?
- Skeleton animation
- Problem of half-second lag spike

---

## Designer's responsibility

- Product design
- Architecture design
- UX design
- Animations

---

## Local-first

---

## Different software architectures

- Client-server
- Local
- Local-first\*

---

## Local Software

There's no server<sup>1</sup>

Your average application, storing data on your local computer

- Text Editors
- Image viewers
- Obsidian

<br/><br/>
<sup>1</sup> that was supposed to be a matrix meme

---

## Client-Server Architecture

Software we all know and love

- Frontend initiates actions
- Backend processes actions and returns some data
- Frontend uses them to render the data

---

## Local-first

- Behaves like a local application
- "Somehow" syncs the data to the cloud storage

---

## You might actually already be working with local-first

- Google Docs
- Linear

---

## How does local-first works?

- Sync engines
- CRDT
- What to do when

---

## Some Links

[Local-first software](https://localfirstweb.dev)
[Unexpected benefits of going local-first - Tuomas Artman (Local-First Conf)](https://www.youtube.com/watch?v=VLgmjzERT08)

---

<!--config align=center-->

#### Obligatory advertisement

<img src="https://camunda.com/wp-content/uploads/2020/05/logo-camunda-black.svg" alt="Camunda logo" style="width: 400px" />
<a href="https://camunda.com/careers"><img src="qr.svg" alt="Camunda logo" style="width: 400px" /></a>

---

# _Thanks!_
