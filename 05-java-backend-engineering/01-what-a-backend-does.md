# What Does a Backend Do?

- **Phase:** 5 — Java Backend Engineering
- **Status:** Not assessed

## Simple definition

The **backend** is the part of an application that runs behind the user interface. It handles rules, requests, data access, and communication with other systems.

## Frontend and backend

| Frontend | Backend |
|---|---|
| What the user sees and interacts with | The logic and services behind the interface |
| Forms, buttons, screens | Business rules, APIs, data access |
| Sends requests | Receives and processes requests |

## Banking example

A user presses “Deposit” in an application.

```text
User interface
     ↓ sends request
Backend API
     ↓ checks request
Business logic
     ↓ updates data
Database
     ↓ result
Backend sends response
     ↓
User sees success or error
```

The backend should not trust every request automatically. It must validate input and check permission and business rules.

## Java connection

A Java backend may use classes and services to organize responsibilities. A framework such as Spring Boot can help build web APIs, but the framework does not replace understanding the rules.

## Key idea

The frontend is the interaction surface; the backend processes requests and applies the system's rules.