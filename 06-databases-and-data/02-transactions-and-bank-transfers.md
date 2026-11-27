# Transactions and Safe Bank Transfers

- **Phase:** 6 — Databases and Data
- **Status:** Learning

## The problem

Suppose Account A has $100 and wants to send $30 to Account B.

A transfer has at least two important changes:
1. Subtract $30 from A.
2. Add $30 to B.

What if the first change succeeds but the second fails? A loses money, but B does not receive it.

## What is a database transaction?

A **transaction** is a group of database operations treated as one unit.

For a transfer, the goal is:
- Either both balance changes succeed.
- Or neither change is kept.

This is often described as **all or nothing**.

## Simple flow

```text
Start transaction
      ↓
Check accounts and amount
      ↓
Subtract from sender
      ↓
Add to receiver
      ↓
Commit transaction if all succeed
      ↓
Otherwise roll back changes
```

**Commit** means confirm and save the transaction. **Rollback** means undo the uncommitted changes.

## Other checks

Before a transfer, the application should also check:
- Sender exists.
- Receiver exists.
- Amount is greater than zero.
- Sender has enough money.
- The sender is allowed to transfer.

## Important limitation

A database transaction protects a group of database changes. The application still needs correct validation, authorization, error handling, and suitable database design.

## Key idea

A transfer must not leave the system in a half-completed state. Transactions help keep related data changes consistent.