# Initial Software Engineering Assessment — Results and Learning Guide

## 1. Purpose

This report records my current understanding of Software Engineering based on my first answers. It is a learning starting point, not an exam or a judgment of my ability.

**Assessment date:** 27 November 2026  
**Current level:** Beginner — with some early foundational knowledge  
**Learning language:** Simple English  
**Main learning goal:** Understand how real software is planned, designed, built, tested, reviewed, released, and maintained.

> Important: Some of my answers do not match the exact wording of the original 15 questions in this file. This report evaluates what I actually explained. Where I did not provide enough evidence, the topic is marked **Not assessed** instead of guessing.

---

## 2. Assessment summary

| Topic | Current result | What this means |
|---|---|---|
| Programming and Software Engineering | **Partial knowledge** | I know programming is more than typing code and that software engineers solve problems. I need a clearer distinction. |
| Software Engineering roles | **Partial knowledge** | I can name frontend, backend, full-stack, API, and AI engineering, but need to understand which are roles and which are technologies or concepts. |
| SDLC | **Partial knowledge** | I know planning, analysis, design, and implementation. I need testing, deployment, and maintenance too. |
| Requirements | **Partial knowledge** | I can give banking feature examples. I need functional vs. non-functional requirements. |
| Software design | **Needs learning** | I currently connect design mostly with colors and appearance. Software design is much broader. |
| Implementation | **Basic understanding** | I correctly connect implementation with building the software, usually by writing code. |
| Features and bugs | **Partial knowledge** | I can give examples, but need precise definitions and the difference between expected and actual behavior. |
| Git and code review workflow | **Partial knowledge** | I know commit, push, review, and merge, but need to understand the complete team workflow. |
| Real-world teamwork | **Needs learning** | I do not yet know the different people who may work on a feature. |
| Database and data persistence | **Not assessed** | I did not explain how data remains saved after an application closes. |
| API vs. database | **Basic understanding** | I understand the waiter analogy for an API and that a database stores data. |
| Handling a failed transfer | **Not assessed** | I did not explain validation, errors, or how to avoid reporting a failed transfer as successful. |
| Testing | **Not assessed** | My answer about implementation did not explain why testing is necessary. |
| Maintainability | **Not assessed** | My bug example did not explain what makes software easy to change and maintain. |
| Deployment | **Needs learning** | I have heard the word but do not yet understand the process. |

---

## 3. Concepts explained at my current level

### 3.1 Programming vs. Software Engineering

**Programming** means working out a solution and expressing it in a programming language so a computer can perform it.

A useful way to remember three important activities is:

1. **Problem-solving:** Understand the problem and decide what should happen.
2. **Designing:** Plan how the solution and its parts should work.
3. **Coding:** Turn the solution into instructions the computer can run.

These activities can overlap. They are not always three separate steps.

**Software Engineering** is the wider discipline of building and supporting software in a reliable, organized way. It includes understanding needs, planning, design, programming, testing, teamwork, release, and maintenance.

**Example — Banking application**

- Problem: Customers need a safe way to manage money.
- Design: Decide how accounts, balances, deposits, and transfers should work.
- Coding: Implement those rules in Java.
- Testing: Check that the rules work correctly.
- Maintenance: Fix problems and improve the application later.

**Most important idea:** Coding is one part of software development. Software Engineering covers the whole process.

### 3.2 Software Engineer and different roles

A software engineer helps solve problems by building and improving software. Depending on the company and project, people may specialize in different areas.

| Area or role | Simple meaning |
|---|---|
| Frontend developer | Builds the part of an application users see and interact with. |
| Backend developer | Builds the server-side logic, data handling, and business rules. |
| Full-stack developer | Works on both frontend and backend. |
| API development | Builds or maintains ways for different software systems to communicate. This is work, not always a separate job title. |
| AI/ML engineer | Builds software systems that use machine-learning or AI models. |

These are examples, not a complete list. Other roles include mobile developer, QA/test engineer, DevOps engineer, security engineer, and software architect.

### 3.3 SDLC — Software Development Life Cycle

**SDLC** means Software Development Life Cycle. It is a way to organize the work of creating and supporting software.

A simplified flow:

```text
Idea
  ↓
Planning
  ↓
Requirements and Analysis
  ↓
Design
  ↓
Implementation (building/coding)
  ↓
Testing
  ↓
Deployment (release)
  ↓
Maintenance and Improvement
  ↺
```

| Phase | Simple question | Banking example |
|---|---|---|
| Idea | What problem could we solve? | Customers need to manage bank accounts online. |
| Planning | Is the project possible, useful, and worth doing? | Estimate time, people, cost, and risks. |
| Requirements and analysis | What exactly must the system do? | Users can create accounts and transfer money. |
| Design | How will the system be organized? | Plan screens, database tables, account rules, and components. |
| Implementation | How will we build it? | Developers implement the application in Java and other technologies. |
| Testing | Does it work correctly? | Check valid and invalid deposits and transfers. |
| Deployment | How do users get the working application? | Release it to a production server or app platform. |
| Maintenance | How do we keep it useful and reliable? | Fix bugs, improve performance, and add approved features. |

**Remember:** A project does not simply end when coding finishes. Testing, release, and maintenance are also important.

Real teams may repeat phases, work on them in parallel, or use Agile methods to deliver small improvements frequently.

### 3.4 Requirements

A **requirement** describes something the software must do or a condition it must satisfy.

There are two important types:

**Functional requirement:** Describes a behavior or service the system must provide.

Examples:
- The user can create a bank account.
- The user can deposit money.
- The user can withdraw money.
- The user can transfer money.
- The user can block an account.

**Non-functional requirement:** Describes a quality or condition the system should meet.

Examples:
- The system should protect customer information.
- The account screen should load within an agreed time.
- The service should be available reliably.
- The application should be easy to maintain.

**Easy memory trick:**
- Functional = **What must it do?**
- Non-functional = **How well or under what conditions must it work?**

### 3.5 Design is more than appearance

You said design is like colors or what we see. That is one kind of design: **visual/user-interface design**.

Software design also includes:

- **UI design:** What users see and click.
- **Data design:** How information is organized and stored.
- **Component design:** What classes or parts the application needs and what each part does.
- **Architecture:** The high-level structure of the whole system.
- **Process/workflow design:** How an operation should happen from beginning to end.

**Bank transfer example:** Before coding, the team should decide how to identify the sender and receiver, validate the amount, check the sender's balance, update both accounts, and handle errors.

### 3.6 Implementation

**Implementation** is the phase where the team builds the planned solution. For a Java application, this usually means writing and integrating Java code, connecting required services, and following the design and requirements.

Example: Implementing the deposit feature means creating the behavior that accepts a valid amount and updates the account balance according to the rules.

Implementation is not the same as the entire SDLC. It is one phase within it.

### 3.7 Feature vs. bug

A **feature** is a function or capability that the product is intended to provide.

Banking application features:
- Create an account.
- Deposit money.
- Withdraw money.
- Transfer money.
- Block an account.

A **bug** is a defect: the software behaves differently from what was expected or required.

**Calculator example:**
- Expected: 5 + 5 = 10.
- Actual: The calculator displays 11.
- Result: This is a bug because the result is incorrect.

**Banking example:**
- Expected: Deposit $50 into an account with $100.
- Actual: The application shows $140.
- Result: This is a bug in the deposit behavior.

A feature is not automatically correct just because it exists. It must also work as required.

### 3.8 Git, GitHub, and code review

You understand that another developer can review a change before it becomes part of the main codebase. Here is a common team workflow:

```text
Create a branch
      ↓
Make a change
      ↓
Commit the change
      ↓
Push the branch to GitHub
      ↓
Open a Pull Request (PR)
      ↓
Another developer reviews it
      ↓
Fix issues if needed
      ↓
Approve and merge into the main branch
```

- **Git** tracks changes to files and helps developers work with versions of a project.
- **GitHub** hosts Git repositories and provides collaboration tools such as Pull Requests.
- **Commit** saves a recorded set of changes in Git.
- **Push** sends local commits to a remote repository.
- **Pull Request (PR)** asks the team to review and consider merging a change.
- **Merge** combines the approved changes into another branch.

A reviewer does not simply decide whether to ignore the work. They may approve it, ask for changes, or discuss a better solution. A rejected approach may be closed or replaced.

**Why code review?**
- Find mistakes before they reach the main codebase.
- Check whether the change meets the requirement.
- Improve readability and maintainability.
- Share knowledge across the team.
- Discuss security, performance, and design concerns.

Code review is not a guarantee that code has no bugs. Testing is still necessary.

### 3.9 Who works on a software product?

A programmer is important, but a team may include many people:

| Person or role | Contribution |
|---|---|
| Customer / stakeholder | Explains the problem and business needs. |
| Product manager | Helps decide what should be built and in what order. |
| Business analyst | Helps understand and document requirements. |
| UI/UX designer | Plans the user experience and visual interface. |
| Software engineer/developer | Designs and builds software. |
| QA/test engineer | Checks whether the software works and finds defects. |
| DevOps / platform engineer | Helps automate delivery and operate the application. |
| Security specialist | Helps identify and reduce security risks. |

One person may perform several of these responsibilities, especially in a small team.

### 3.10 API vs. database

Your waiter analogy is a good starting point.

Imagine a restaurant:
- The customer makes a request.
- The waiter carries the request to the kitchen and brings back the response.
- The kitchen prepares the order.

An **API** is a defined way for one software system or part of a system to request something from another. It receives requests and provides responses according to rules.

A **database** stores and organizes data so it can be saved and retrieved.

In a banking application:
- API: receives a request such as “show this account” or “make a transfer.”
- Backend logic: checks whether the operation is allowed.
- Database: stores account and transaction information.

The API does not normally mean the database itself. They have different jobs.

### 3.11 Database persistence

**Persistence** means data remains saved after the application closes or restarts.

For example, if a customer has a balance of $500, the balance should not disappear when the program closes. A database such as PostgreSQL can store the account and transaction records.

An in-memory Java list can hold data while a simple program is running, but it is not a replacement for persistent database storage.

### 3.12 What should happen when a bank transfer fails?

Suppose a user wants to transfer money, but the receiving account does not exist.

A reliable system should:
1. Check that the sender and receiver accounts exist.
2. Check that the amount is valid and greater than zero.
3. Check that the sender has enough money.
4. Apply the transfer safely.
5. Report success only if the operation really succeeds.
6. Give a clear error if it fails.

A key database idea is a **transaction**. A transfer should not subtract money from one account while failing to add it to the other. The operation should succeed as a whole or be rolled back safely.

This topic needs a practical lesson later.

### 3.13 Testing

**Testing** means checking software to find out whether it behaves as expected.

For a deposit feature, tests could check:
- Deposit $50 into an account with $100 → expected balance $150.
- Deposit zero → should be rejected if the requirement says the amount must be positive.
- Deposit a negative amount → should be rejected.
- Deposit into a blocked account → follow the application's stated rule.

Testing matters because code can compile and still behave incorrectly. A successful run of one example does not prove that every situation works.

### 3.14 Maintainability

**Maintainability** means how easy it is to understand, fix, test, and improve software later.

For example, if deposit, withdrawal, and transfer rules are clearly organized, another developer can understand and change them more safely.

Maintainable software usually has:
- Clear names.
- Small, understandable responsibilities.
- Organized structure.
- Useful tests.
- Limited unnecessary duplication.
- Helpful documentation where needed.

### 3.15 Deployment

**Deployment** means making a software version available in the environment where it will be used.

For example:
- A Java program works on the developer's laptop.
- The team prepares the application and its configuration.
- The team releases it to a production server.
- Customers can now use it.

**Important difference:**
- Running locally = running it on your own development machine.
- Deployment = releasing it to the environment where users or other systems can access it.

Deployment is not the same as pushing code to GitHub. Pushing uploads code to a repository; deployment releases a working application to an environment.

---

## 4. My current strengths

Based on my answers, I already have these starting points:

1. I know programming is not only coding.
2. I understand that software engineers solve problems.
3. I can name several software development areas.
4. I recognize some SDLC phases.
5. I can identify common banking application features.
6. I understand that implementation involves building the software.
7. I can explain a simple bug using a calculator example.
8. I know that code can be reviewed before merging.
9. I know basic Git/GitHub words such as commit, push, and merge.
10. I have a basic idea of APIs and databases.

These are starting points, not proof of complete mastery.

## 5. My learning gaps

The most important gaps to address are:

1. Functional vs. non-functional requirements.
2. Software design vs. visual design.
3. The complete SDLC, especially testing, deployment, and maintenance.
4. Git branches and Pull Requests in a real team.
5. How different team roles work together.
6. Database persistence and how backend applications use databases.
7. Safe handling of failed operations and database transactions.
8. Testing and maintainable software.
9. Deployment and production environments.

---

## 6. Recommended learning order

Learn these topics in this order. Each topic builds on the previous one.

| Order | Topic | Learning goal |
|---:|---|---|
| 1 | Programming vs. Software Engineering | Understand the bigger picture. |
| 2 | SDLC | Understand the full software lifecycle. |
| 3 | Requirements | Learn what a system must do and how well it must work. |
| 4 | Software design | Understand how developers plan a solution before and during coding. |
| 5 | Features, bugs, and implementation | Understand building software and expected behavior. |
| 6 | Testing | Learn how teams check software quality. |
| 7 | Git branches and Pull Requests | Understand collaboration and code review. |
| 8 | Software team roles | Understand how a team delivers a product. |
| 9 | Backend, APIs, and databases | Understand how an application handles requests and data. |
| 10 | Database transactions and reliability | Understand safe operations such as money transfers. |
| 11 | Deployment and maintenance | Understand how software reaches users and improves over time. |

Do not rush through all the topics. Learn one concept, explain it in your own words, and connect it to the banking application example.

---

## 7. Important vocabulary

| Word | Simple meaning |
|---|---|
| Requirement | Something the software must do or satisfy. |
| Feature | Something the product can do. |
| Bug | A defect that causes incorrect or unexpected behavior. |
| Design | A plan for how the software or its parts should work. |
| Implementation | Building the planned solution. |
| Testing | Checking whether the software works as expected. |
| Code review | Another developer checks a proposed code change. |
| Commit | A recorded set of changes in Git. |
| Push | Send local commits to a remote repository. |
| Pull Request | A request to review and merge changes. |
| Merge | Combine changes into another branch. |
| API | A defined way for software parts or systems to communicate. |
| Database | A system for storing and organizing data. |
| Deployment | Releasing software to an environment where it can be used. |
| Maintenance | Fixing and improving software after release. |
| Production | The live environment used by real users or systems. |

---

## 8. How to measure progress

For each topic, use these three levels:

- **Not yet:** I cannot explain the concept.
- **Learning:** I understand the basic idea but need help or examples.
- **Confident:** I can explain it simply and apply it to a realistic example without copying a definition.

Do not mark a topic as confident only because the word looks familiar.

---

## 9. Final assessment

My current level is **Beginner with partial foundational knowledge**.

I should not restart programming from zero, and I should not jump directly into advanced architecture or DevOps. The best next step is to strengthen the foundations: SDLC, requirements, design, testing, and the real development workflow.

**My guiding idea:**

> A software engineer does not simply write code. A software engineer helps understand a problem, plans a solution, builds it, checks it, releases it, and improves it.

This report should be updated as I learn and can explain each topic more confidently.
