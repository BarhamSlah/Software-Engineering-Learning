# Software Design Is More Than Appearance

- **Phase:** 4 — Design and Architecture
- **Status:** Learning

## Simple definition

**Software design** is planning how a software solution and its parts should work together.

You were thinking of colors and what users see. That is **visual design** or part of **UI design**. It is real design, but not the whole subject.

## Different kinds of design

| Type | What it plans | Banking example |
|---|---|---|
| UI/visual design | Screens, colors, buttons, layout | Where the Deposit button appears |
| Data design | How information is organized | Account table, balance, transaction records |
| Component design | Parts and their responsibilities | Account service handles account rules |
| Process/workflow design | Steps in an operation | How a transfer is validated and completed |
| Architecture | High-level structure of the system | Frontend, backend API, database |

## Example: design a transfer

Before writing code, the team should think about:
1. How does the user request a transfer?
2. How do we identify the sender and receiver?
3. What rules must be checked?
4. What happens if the receiver does not exist?
5. How do we prevent money being removed without being received?
6. What information must be stored?

These are design questions. They are not about button colors.

## Design vs. implementation

- **Design:** Plan how the solution should work.
- **Implementation:** Build that solution.

In real projects, design and implementation can influence each other. Developers may adjust the design when they learn more.

## Key idea

Design is the plan for how the software works and is organized. The user interface is only one part of it.