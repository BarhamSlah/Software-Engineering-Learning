# Database and Persistence

- **Phase:** 6 — Databases and Data
- **Status:** Learning

## What is a database?

A **database** is an organized place to store and retrieve data.

A relational database such as PostgreSQL stores data in tables made of rows and columns.

## What is persistence?

**Persistence** means data remains saved after the application stops or restarts.

Example:
- Your Java program puts an account in an ArrayList.
- While the program runs, it can read that account.
- If the program closes, the in-memory list is normally lost.
- If the account is saved in a database, it can be loaded again later.

## Comparison

| In-memory data | Persistent database data |
|---|---|
| Stored while the program is running | Stored beyond one program run |
| Often disappears when the process ends | Remains until changed or deleted |
| Useful for temporary data and simple exercises | Useful for real application records |

## Banking example

A bank account may need:
- Account ID
- Customer ID
- Account status
- Current balance
- Transaction history

The application reads and updates these records through its backend logic.

## Important idea

A database is not just a place for user names. It stores organized information the application needs to use reliably.