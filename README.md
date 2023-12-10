# GitHub Actions CI/CD for Unit Tests

GitHub provides a powerful tool for CI/CD processes called GitHub Actions. You can find detailed documentation 
[here](https://github.com/features/actions).

One common use case for GitHub Actions is to automatically run unit tests when a Pull Request is opened into the main 
branch.

## Implementation Overview

1. Define a trigger to respond to the opening of a Pull Request into the main branch.
2. Specify the action to be executed (e.g., for a Gradle project, run the command `./gradlew test`).

For a step-by-step guide on setting up tests for a Java project using GitHub Workflow, refer to the 
[official tutorial](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-java-with-gradle).

## Task #1 - Configure Unit Test Execution

1. Select any project with existing unit tests (or create a new project and add a simple unit test).
2. Configure a GitHub Action for the project that triggers on Pull Requests into the main branch.
3. The action should execute the unit tests (e.g., for a Gradle project, run the command `./gradlew test`).
4. Open a Pull Request into the main branch and ensure that the GitHub Action is triggered.

## Example

Here's an example GitHub repository with a configured GitHub Action for running unit tests: 
[Sample Project](https://github.com/example/sample-project)

Feel free to use this template for your own projects. Happy coding!
