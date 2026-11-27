# Transactions: Keeping Data Safe

**Time:** 6 minutes · **Level:** Beginner

## 1. The problem

Imagine a bank transfer:

- Account A sends $30.
- Account B should receive $30.

What if the money is removed from A, but an error stops it from reaching B?

That would be a serious problem.

## 2. What is a transaction?

A **database transaction** groups related changes together.

For a transfer, we want:
- Both changes to succeed, or
- Neither change to be saved.

This is called **all or nothing**.

## 3. Simple picture

```
Start
  ↓
Remove $30 from A
  ↓
Add $30 to B
  ↓
Both succeed? → Save both
Any failure?  → Undo the changes
```

- **Commit:** save the changes.
- **Rollback:** undo changes that were not committed.

## 4. Why does it matter?

It helps prevent the database from keeping half of a transfer.

## 5. Remember this

**A transaction helps keep related database changes together and consistent.**

## 6. Quick check

If adding money to B fails, should the removal from A remain?

**Answer:** No. The transaction should be rolled back.