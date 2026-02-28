```markdown
# AGENTS.md File Guidelines

These guidelines outline best practices for the development of AGENTS.md, an AI coding agent repository. Adherence to these principles is crucial for maintaining code quality, scalability, and maintainability.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each module/file should have a single, well-defined purpose. Avoid creating overly complex or duplicated code.
*   **Common Logic Reuse:** Identify and reuse common logic patterns across multiple modules.
*   **Parameterization:**  Employ parameters to handle variations in input, minimizing code repetition.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible code solution that achieves the desired functionality.
*   **Clear Intent:** Each line of code should have a clear and understandable purpose.
*   **Avoid Unnecessary Complexity:** Resist over-engineering solutions.

## 3. SOLID Principles

*   **Single Responsibility Principle:**  Each class/module should have a single, logical reason for existence.
*   **Open/Closed Principle:**  The code should be extensible without modifying its internal structure. Use interfaces to decouple from external implementations.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace parent classes without breaking the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.  Interfaces should define contracts.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Focus on the Current Task:**  Implement only the necessary functionality for the current development phase.  Defer speculative features until explicitly needed.
*   **Avoid Unnecessary Features:** Resist adding features that are not currently required.

## 5. Code Style & Formatting

*   **Consistent Formatting:**  Follow a consistent code style guide (e.g., Google Style) across all files.  Use a linter and formatter (e.g., `black` or `autopep8`).
*   **Indentation:** Use 2 spaces for indentation.
*   **Line Length:**  Keep lines under 120 characters.
*   **Comments:**  Provide clear and concise comments explaining complex logic or non-obvious decisions. Avoid commenting on code that is already self-documenting.

## 6. Testing (Must Be Productive - Not Mocking)

*   **Unit Tests:** All code must be thoroughly tested with unit tests.
*   **Test Coverage:**  Aim for at least 80% test coverage. Utilize existing test suites or create new ones.
*   **Test Data:**  Ensure tests use realistic and representative data.
*   **Test Assertions:**  Test assertions to validate expected outcomes.

## 7. File Length Restriction

*   **Maximum Lines:** 180 lines of code per file.
*   **Branching/Structure:**  Maintain a logical structure within each file that reflects its purpose.

## 8.  Documentation (Optional - For Future Expansion)

*   **README:** Include a README file detailing the repository's purpose, usage, and dependencies.

## 9.  Maintainability -  Project Goals

*   **Version Control:** Use a version control system (e.g., Git) and adhere to established branching and merging practices.
*   **Code Reviews:** Encourage code reviews to identify potential issues and ensure code quality.
*   **Refactoring:**  Perform regular refactoring to improve code readability and maintainability.


These guidelines are intended as a framework.  Adapt and refine them as needed to support the specific goals of the AGENTS.md repository.
```