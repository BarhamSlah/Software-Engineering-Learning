# Functional vs. Non-Functional Requirements

- **Phase:** 3 — Requirements and Analysis
- **Status:** Learning

## Functional requirement

A **functional requirement** describes a behavior or service the system must provide.

Examples:
- The user can create an account.
- The user can deposit money.
- The user can transfer money.
- The system blocks withdrawals from a blocked account.

Ask: **What must the system do?**

## Non-functional requirement

A **non-functional requirement** describes a quality, limit, or condition the system must meet.

Examples:
- Account information must be protected from unauthorized users.
- The account page should respond within an agreed time.
- The service should remain available according to an agreed target.
- The code should be structured so it can be maintained.

Ask: **How well must it work, or under what conditions?**

## Comparison

| Functional | Non-functional |
|---|---|
| What behavior exists? | What quality or constraint applies? |
| Transfer money | Protect transfer data |
| Show account balance | Show it within an agreed response time |
| Block an account | Only authorized staff can block it |

A security rule can sometimes be written as a functional rule or a quality/constraint requirement depending on how it is stated. The important thing is to make it clear and testable.

## Common mistake

“Design the app with blue buttons” is a visual/UI requirement, not the same as a business function such as “the customer can deposit money.”

## Key idea

Functional = what it does. Non-functional = how well or under what conditions it must work.