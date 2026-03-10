QA Glossary – Beginner Terms

1. Test Case – A set of steps to verify a feature works as expected.
Example: Login with standard_user on Sauce Demo.

2. Defect (Bug) – A problem in the code that causes incorrect behavior.
Example: “Add to Cart” button doesn’t work for problem_user.

3. Failure – When the system behaves incorrectly because of a defect.
Example: Product quantity not updating after adding to cart.

4. Test Plan – Document describing what to test, how, and when.
Example: Planning login, product, and checkout tests on Sauce Demo.

5. Equivalence Partitioning – Grouping inputs to reduce redundant testing.
Example: Testing only positive, zero, and negative quantities in the cart.

6. Boundary Value Analysis – Testing input edges for errors.
Example: Password field: 0, 1, maximum, and over-limit characters.

7. Positive Testing – Verifying the system works with valid input.
Example: Login with standard_user and correct password.

8. Negative Testing – Checking system behavior with invalid input.
Example: Login with wrong password or empty username.

9. Test Execution – Running test cases and recording results.
Example: Execute login test cases and mark pass/fail in test-cases/login-tests.md.

10. Test Closure – Summarizing testing, lessons learned, and open issues.
Example: Documenting which test cases passed/failed and linking bug reports.

11. Smoke Testing – Quick check to see if basic functionality works.
Example: Can a user log in, add a product to the cart, and reach checkout?

12. Regression Testing – Testing existing features after changes.
Example: After updating checkout flow, re-run cart and login tests.
