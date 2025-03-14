# Test Driven Development (TDD)

## What it is?
TDD is a software development practice in which automated tests are written before the functional code. 
This method promotes short and iterative development cycles, ensuring that each new feature is tested and validated from the start.

## Process
The TDD process follows the Red-Green-Refactor cycle:

- **Red**: Write a test for a new feature that has not been implemented yet. This test will initially fail, indicating that the feature does not exist or is incorrect. This may sound weird but it is how it works.
  
- **Green**: Develop the necessary code to make the test pass. The goal here is to implement the feature in such a way that the test succeeds. in this stage we should not worry a lot about the quality of the code, but it's functionality.

- **Refactor**: Improve and optimize the newly written code, ensuring it is clean, cohesive, and easy to maintain, without changing its functionality. During refactoring, all tests must continue to pass, we are just adjusting the code. 

This cycle is repeated for each new feature or adjustment in the system, promoting incremental and continuous development.

## Benefits
- **Fast feedback**: Tests provide immediate feedback on the newly implemented feature and existing functionalities, allowing for quick identification of any issues introduced.

- **Cleaner and more flexible code**: Writing tests before the code encourages developers to create simpler, less coupled solutions, making future changes and maintenance easier.

- **Confidence in refactoring and bug fixing**: With a comprehensive test suite, developers can refactor the code with confidence, knowing that tests will catch any regressions or errors introduced.

- **Increased productivity**: The reduction of bugs and lower dependency on debuggers result in a more efficient and focused development process.
