```markdown
# AGENTS.md Guidelines

These guidelines outline the principles and expectations for all development within the AGENTS repository. Adherence to these principles will ensure a maintainable, scalable, and robust codebase.

## 1. DRY (Don't Repeat Yourself)

*   All code should have a single, clear purpose and be reusable across multiple modules or components.
*   Avoid duplicating logic or components.
*   Refactor duplicated code into separate functions or classes where appropriate.

## 2. KISS (Keep It Simple, Stupid)

*   Prioritize simplicity and readability.
*   Strive for the shortest, most understandable code.
*   Avoid overly complex solutions.
*   Focus on essential functionality.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have one well-defined responsibility.
*   **Open/Closed Principle:** Code should be extensible without modifying its core interface.
*   **Liskov Substitution Principle:** Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Each client should not be required to know detail about the methods of a class that they do not use.
*   **Dependency Inversion Principle:** High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is explicitly required at a specific point in time.
*   Defer implementation until it's absolutely necessary.
*   Avoid adding unnecessary features or complexity.

## 5. Code Structure & Organization

*   **File Structure:**  Maintain a clear and logical file structure. Utilize a consistent naming convention.
*   **Module Decomposition:** Break down large modules into smaller, manageable components.
*   **Comments:** Provide concise, helpful comments where necessary, explaining *why* not *what*. Focus on the intent behind the code.

## 6. Code Quality & Best Practices

*   **Naming Conventions:** Follow a consistent naming convention (e.g., camelCase, snake_case).
*   **Error Handling:** Implement robust error handling with appropriate logging and exception management.
*   **Logging:**  Use a consistent logging framework.
*   **Data Structures:**  Choose appropriate data structures for each task.
*   **Code Style:**  Adhere to the established code style guide (refer to [style_guide.md] for details).
*   **Testability:** Write unit tests for all significant functions and classes.

## 7. Testing & Coverage

*   **Unit Tests:** All development must be productive. No mocks or fake implementations are allowed.
*   **Test Coverage:** Achieve at least 80% test coverage for all major functions and classes.
*   **Test-Driven Development:**  Prioritize writing tests before implementation.
*   **Regression Tests:**  Ensure all new code adds to existing functionality.

## 8. Line Limit

*   Maximum code length: 180 lines.

## 9.  Specific Requirements (Illustrative - adapt to the actual project)

*   **Agent Initialization:**  All agent initialization logic must be encapsulated within a separate class.
*   **Communication Protocol:**  Specify a clear communication protocol and implement it.
*   **Data Persistence:**  Define a strategy for data persistence (e.g., database, file storage).
*   **Event Handling:** Implement a robust event handling system.

## 10.  Documentation

*   **README.md:** Provide a README file documenting the project's purpose, setup instructions, and usage.

## 11. Version Control

*   Use Git for version control.  Commit frequently and with clear messages.

## 12.  Coding Standards Reference

*   Refer to the [coding_standards.md] document for a comprehensive list of coding standards.
```