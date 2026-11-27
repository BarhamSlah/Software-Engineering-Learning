# Practical Software Engineering Roadmap

## Course approach

This course teaches general Software Engineering through one continuous case study: a **Campus Service Request System**. We begin with a real problem and gradually make the decisions needed to turn it into a reliable software product.

The goal is not to write code in every lesson. The goal is to learn how to reason, document, design, evaluate, and communicate like a software engineer. Java, APIs, databases, Git, and GitHub are supporting examples—not the main subject.

Each phase produces a practical artifact. We will not pretend that a document is useful just because it is completed: you should be able to explain the decisions inside it.

## Phase 0 — Personal baseline

**Status: Initial assessment completed; some topics need to be learned and checked.**

You recognize basic programming, early SDLC stages, banking capabilities, a simple bug, Git vocabulary, and the API/waiter analogy. Your understanding of requirements, software design, testing, persistence, deployment, and maintenance needs development.

## Phase 1 — Foundations: what is Software Engineering?

**Learn:** programming vs. Software Engineering; problem-solving; SDLC; iterative development; software quality; technical debt; engineering trade-offs.

**Practical work:** describe the Campus Service Request System problem in plain language. Explain why simply starting to code is not enough.

**Deliverable:** one-page problem statement and a simple lifecycle diagram.

**Outcome:** explain the full lifecycle and the purpose of engineering activities.

## Phase 2 — Understand the people and the problem

**Learn:** stakeholders; users; goals; business rules; scope; assumptions; constraints; functional and non-functional requirements; user stories; use cases; acceptance criteria; prioritization.

**Practical work:** identify students, service staff, and administrators. Discover what each needs. Separate a feature from a requirement and a quality requirement.

**Deliverable:** stakeholder map, scope statement, prioritized requirements, and acceptance criteria.

**Outcome:** turn a vague request into clear, testable expectations.

## Phase 3 — Model and design a solution

**Learn:** UI/UX vs. software design; process and data modeling; use-case and activity diagrams; components; interfaces; architecture; modularity; cohesion and coupling; design trade-offs.

**Practical work:** map the request lifecycle (submitted → assigned → in progress → resolved). Decide which responsibilities belong to users, the request service, and staff.

**Deliverable:** use-case diagram, process flow, simple data model, component diagram, and short design decision records.

**Outcome:** explain how the system should be organized before implementation.

## Phase 4 — Plan the work and collaborate

**Learn:** development workflow; tasks and milestones; estimation; risks; Git vs. GitHub; branches; commits; pull requests; code review; team communication.

**Practical work:** break one project feature into small tasks. Review a proposed change description and decide what questions a reviewer should ask.

**Deliverable:** small backlog, task breakdown, and sample pull-request review checklist.

**Outcome:** understand how a team coordinates work and controls changes.

## Phase 5 — Understand implementation and system boundaries

**Learn:** what frontend and backend responsibilities are; APIs; request/response; validation; service boundaries; database responsibilities; layered architecture; dependencies.

**Practical work:** trace “student submits a service request” from the screen through the backend to stored data. Identify what could fail at each step.

**Deliverable:** request sequence diagram and responsibility map.

**Outcome:** understand how parts of a software system work together. Java is used only as a familiar implementation example.

## Phase 6 — Data and correctness

**Learn:** persistence; relational data; entities and relationships; constraints; transactions; consistency; backups.

**Practical work:** decide what information a service request needs, how it relates to a student and staff member, and what must remain consistent when a request is assigned or closed.

**Deliverable:** simple entity-relationship diagram, data rules, and transaction scenario.

**Outcome:** reason about storing and protecting information.

## Phase 7 — Quality, testing, and maintenance

**Learn:** expected behavior; feature vs. bug; test cases; edge cases; unit, integration, and end-to-end testing; debugging; regression; refactoring; maintainability.

**Practical work:** test scenarios such as submitting an empty request, viewing another student's private request, assigning a request twice, and closing a request that is already closed.

**Deliverable:** test plan, test cases with expected results, defect report, and maintenance proposal.

**Outcome:** evaluate whether a system works correctly and can be safely changed.

## Phase 8 — Delivery and operations

**Learn:** build; environments; deployment; configuration; CI/CD; release planning; monitoring; logs; rollback.

**Practical work:** plan how the campus system moves from development to a test environment and then to production. Consider what to check before and after release.

**Deliverable:** release checklist, deployment flow, and rollback plan.

**Outcome:** explain how software becomes available to real users and is operated.

## Phase 9 — Security and reliability

**Learn:** authentication vs. authorization; privacy; access control; input validation; least privilege; reliability; availability; resilience; safe failure; recovery.

**Practical work:** decide who may view, assign, update, and close service requests. Analyze what happens if the database or notification service is unavailable.

**Deliverable:** permission matrix, risk list, and failure-response plan.

**Outcome:** identify risks and make safer design decisions.

## Phase 10 — Teamwork and professional judgment

**Learn:** product, design, development, QA, and operations roles; communication; documentation; decision records; feedback; estimation; prioritization.

**Practical work:** explain a design decision to a non-technical campus manager. Respond to a proposed feature change that would delay the release.

**Deliverable:** short decision record and change-impact analysis.

**Outcome:** communicate decisions and understand the human side of engineering.

## Phase 11 — Review the complete case study

Bring the artifacts together:

1. Problem statement
2. Stakeholder map and scope
3. Requirements and acceptance criteria
4. Models and architecture
5. Work plan
6. Data model and system flow
7. Test plan and defect examples
8. Security and reliability plan
9. Deployment and maintenance plan

**Final outcome:** explain how you would take a software idea from problem discovery through delivery and ongoing maintenance, and justify your important decisions.

## Learning priority

Learn the foundations, requirements, design, and quality first. Then deepen backend, data, delivery, security, and teamwork concepts. Advanced cloud platforms, distributed systems, and complex architecture can wait until the fundamentals are strong.

## Progress standard

- **Learning:** recognize the term.
- **Understood:** explain it in your own words.
- **Applied:** use it to analyze the case study.
- **Reviewed:** explain and apply it again later without relying on the lesson.