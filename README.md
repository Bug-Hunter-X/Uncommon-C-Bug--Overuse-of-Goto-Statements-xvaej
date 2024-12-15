# Uncommon C Bug: Overuse of Goto Statements

This repository demonstrates a simple C program that uses a `goto` statement. While `goto` can be useful in very specific situations (like error handling in deeply nested loops), its overuse often leads to unreadable and difficult-to-maintain code.

The `bug.c` file contains the buggy code, demonstrating a scenario where a `goto` is used unnecessarily to jump out of a loop. The `bugSolution.c` file offers a cleaner, more readable solution without the `goto`.

**Why is using `goto` generally bad?**

* **Reduces readability:** Makes code harder to follow and understand.
* **Increases complexity:** Can lead to spaghetti code with unpredictable flow.
* **Makes debugging difficult:** Tracing execution becomes significantly more challenging.

**Better Alternatives:**

In most cases, using structured control flow statements (like `break`, `continue`, or refactoring the code) provides a more maintainable and readable approach.