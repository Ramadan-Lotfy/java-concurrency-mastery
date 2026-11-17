
# Contributing

Thank you for contributing to Java Concurrency Mastery.

## Guidelines

- Keep examples focused on one concurrency concept.
- Use descriptive class and method names.
- Prefer clear explanations over unnecessarily complex code.
- Document important concurrency behavior.
- Avoid examples that introduce unsafe shared state without explaining it.
- Include tests for relevant behavior.
- Do not use arbitrary Thread.sleep() calls to make tests pass.
- Explain the Java version required for version-specific features.

## Code Style

- Use four spaces for indentation.
- Follow standard Java naming conventions.
- Keep classes focused on a single responsibility.
- Prefer try-with-resources when managing AutoCloseable resources.
- Handle interruption correctly.
- Always shut down executors when appropriate.

## Pull Requests

Every pull request should explain:

1. What problem does it solve?
2. What concept does it demonstrate?
3. How can it be executed?
4. How was it tested?
5. Which Java version does it require?

## Commit Messages

Use conventional commit prefixes:

- feat: Add a new feature or learning example.
- fix: Correct an implementation or explanation.
- docs: Update documentation.
- test: Add or improve tests.
- refactor: Improve code without changing behavior.
- build: Modify build configuration.
- ci: Modify CI configuration.
