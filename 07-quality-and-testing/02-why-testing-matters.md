# Why Software Testing Matters

- **Phase:** 7 — Quality and Testing
- **Status:** Not assessed

## Simple definition

**Software testing** means checking software to find defects and see whether it behaves as expected.

## Why is testing needed?

Code may compile and still contain incorrect logic. One successful example does not prove every situation works.

## Deposit example

Assume the requirement says a deposit amount must be greater than zero.

| Situation | Expected result |
|---|---|
| Deposit $50 into $100 | Balance becomes $150 |
| Deposit $0 | Reject the request |
| Deposit -$20 | Reject the request |
| Deposit into a blocked account | Follow the stated account rule |

A **test case** describes a situation, the input or action, and the expected result.

## Different test levels

| Type | Simple meaning |
|---|---|
| Unit test | Checks one small part, such as a method |
| Integration test | Checks that parts work together, such as a service and database |
| End-to-end test | Checks a complete user flow through the system |

## Testing does not guarantee perfection

Testing reduces risk and finds defects, but no realistic test suite can prove that a complex application has zero bugs in every possible situation.

## Key idea

Testing compares actual behavior with expected behavior and helps teams find problems before users suffer from them.