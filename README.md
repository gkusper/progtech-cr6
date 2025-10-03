# Change Request (CR) Coding Exercise Series

This repository is part of an **eight-step coding exercise series** (CR0–CR7).
Each repository contains one exercise, represented as a **Change Request (CR)**.
The same README file applies to all repositories in the series.

## What is this about?

The goal of this exercise is to practice **Vibe Coding** by solving a **complex programming task**.
Without AI assistance, this task is very difficult: the details are overwhelming, and it is easy to get lost.
To make it manageable, the task is divided into a series of CRs (Change Requests).

The term **Change Request (CR)** is well-known in software engineering.
When developing an information system, the client often changes requirements:
something different is needed, or extra functionality is requested.
Such modifications are formalized as **CR documents**.

In this series, the CRs simulate a **mini agile project**: in each sprint you receive a new CR document to implement.

## Key characteristics of the task

* You do **not** know all CRs in advance.
* You cannot start the next CR until you have solved the current one.
* The CRs build on each other: this is not a greenfield project.
* If the existing code is not flexible enough, you may need to **refactor** before starting the next CR.
* If complexity is not managed (e.g., by introducing design patterns), the task will eventually become unmanageable—even for an AI assistant.

## How to approach the task

* Understanding the CR documents requires strong **text comprehension**.
* Each CR is accompanied by **unit tests** in English and in Hungarian.
* The simplest way is to ask an AI:
  *“Generate production code that passes the unit tests from the following link!”*
* Alternatively, you may write the tests yourself based on the text, or solve the task without tests at all.
* You can try solving it under different **time constraints** (e.g., 1 hour, or 30 minutes/day).
* You may also attempt different strategies:

  * with/without AI-generated tests,
  * with/without design patterns,
  * with/without SOLID principles.

## Possible goals

* **Maximize passing tests in one hour.** Completing all CRs within 1 hour is an achievement.
* **Daily practice (30 minutes per day).** This simulates a real hobby project.
* **Using AI to generate unit tests.** Useful to learn test-driven AI-assisted development.
* **Solving without unit tests.** Useful to test text comprehension (your own or the AI’s).
* **Applying design patterns.** Strategy, Template Method, Visitor, Decorator patterns may appear hidden in the requirements.
* **Applying SOLID principles.** The first two (SRP, OCP) are easy; the rest are more challenging.
* **Time-limited challenge.** How many CRs can you solve in 30 minutes?
* **Create your own CR series.** For example, develop a ToDo app step by step with new CRs.

## Instructions for progressing

* **Do not start CR1 until all CR0 tests are passing.**
* **Do not start CR2 until all CR0 and CR1 tests are passing.**
* Continue likewise: only proceed when **all previous CRs are fully passing**.
* Refactor frequently.

## Typical pitfalls

* The AI generates code that is not what you wanted → type the correct code yourself.
* The AI hallucinates methods that do not exist → point this out or implement the method properly.
* The prompt becomes “tired” (context drift) → start a new chat.
* The AI forgets details from uploaded files → copy-paste the text into the prompt.
* Old mistakes leak from previous conversations → instruct the AI to ignore old context.

## Why do this?

The purpose of the CR series is **twofold**:

1. To explore how quickly you can progress with AI assistance.
2. To learn how to **grow a project step by step**, considering the consequences of previous design decisions.

**Vibe Coding** is about **flexibility**: instead of planning every detail in advance, you always focus on the **next logical step**.
This CR-based exercise series is a perfect way to practice that approach.

## Final note

Enjoy the process.
Observe your progress.
Remember: the goal is **not perfect code**, but to **explore tools, methods, and Vibe Coding**.
And if you don’t like the given CRs—feel free to invent your own!
