# Case Study: Bank Account Application

- **Type:** Hypothetical learning example
- **Status:** Learning
- **Purpose:** Connect the first Software Engineering concepts to a familiar project.

## 1. Problem

Customers need a safe way to manage bank accounts and transactions.

## 2. Possible features

- Create an account
- View account information
- Deposit money
- Withdraw money
- Transfer money
- Block an account

A feature is a capability. Each feature needs detailed requirements and rules.

## 3. Example requirements

**Functional**
- A customer can create an account.
- A customer can deposit a positive amount.
- A blocked account cannot withdraw money.
- A transfer requires a valid sender and receiver.

**Non-functional**
- Customer data must be protected.
- Operations should complete within an agreed response time.
- Account records must remain saved after the application restarts.

## 4. Design questions

- What information belongs to an account?
- Which part checks business rules?
- How does the user request a transfer?
- Where is account information stored?
- How do we prevent a half-completed transfer?

Design includes interface, data, components, workflows, and architecture—not only colors.

## 5. Implementation

Developers build the planned behavior, perhaps using Java for backend logic and PostgreSQL for persistent data.

## 6. Testing

Examples:
- Deposit $50 into $100 → expected $150.
- Deposit a negative amount → reject.
- Withdraw more than the balance → reject if that is the rule.
- Transfer to a missing receiver → fail safely.

## 7. Deployment and maintenance

After testing, the team deploys the application to an environment for users. Later, it fixes defects, monitors the service, and adds improvements.

## 8. Full lifecycle

```text
Customer need
    ↓
Requirements
    ↓
Design
    ↓
Implementation
    ↓
Testing
    ↓
Deployment
    ↓
Maintenance
```

## Key idea

A banking application is not just a collection of Java methods. It is a product with user needs, rules, data, design, testing, release, and ongoing support.