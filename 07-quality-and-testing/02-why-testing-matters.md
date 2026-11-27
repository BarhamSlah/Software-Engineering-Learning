# Why Do We Test Software?

**Time:** 5 minutes · **Level:** Beginner

## 1. The idea

**Testing** means checking that software behaves as expected.

## 2. Our project example

We want students to send reports.

Let's check some situations:

| Situation | Expected result |
|---|---|
| Student sends a report with a title | Report is saved |
| Student sends an empty report | App asks for the missing information |
| Student opens their report | They can see its status |
| Student tries to see another student's private report | Access is denied |

Each situation checks something important.

## 3. What is a test case?

A **test case** is a simple check with:
- A situation or action.
- An expected result.

## 4. Why test?

Because software can look correct but still have mistakes. Testing helps find problems before users depend on the product.

## 5. Remember this

**Testing checks whether the real result matches the expected result.**

## 6. Quick check

If we expect an empty report to be rejected, what should happen when we try to send one?

**Answer:** The app should reject it or ask for the missing information.