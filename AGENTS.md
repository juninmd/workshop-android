```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure the development of high-quality, maintainable, and robust AI coding agents. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   All logic, data structures, and code patterns should be encapsulated within reusable components or functions.
*   Avoid duplication of functionality across multiple files.
*   When a task can be accomplished with a single function or component, create it.
*   Favor single responsibility principle.

## 2. KISS (Keep It Simple, Stupid)

*   Code should be concise and easy to understand.
*   Prioritize readability over cleverness.
*   Avoid unnecessary complexity.
*   Minimize the number of lines of code.
*   Strive for clarity in naming conventions.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or component should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be open for extension but closed for modification.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Client code should not be forced to depend on methods it doesn't use.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features and components that are explicitly required and necessary at the time of development.
*   Defer implementing features until they are needed.
*   Avoid adding unnecessary code or functionality.

## 5. Testing & Mocking

*   All testing MUST be performed using mocks.  No reliance on real systems or data.
*   Mocks should be simple and represent expected behavior.
*   Mocking should be used solely for unit testing.  No integration or end-to-end testing.
*   Test coverage should be at least 80%.
*   Test cases should cover all critical scenarios and edge cases.

## 6. Code Structure & File Limits

*   Each file shall not exceed 180 lines of code.
*   Code blocks should be clearly delineated with appropriate indentation and spacing.
*   Comments should explain the *why*, not the *what*.  Focus on design decisions and rationale.
*   Use consistent naming conventions.
*   Consider using a code formatter (e.g., Black) for consistent formatting.

## 7. File Structure & Organization

*   **AgentDefinition.md:** Describes the core agent model, including data types, properties, and methods.
*   **AgentInitialization.md:**  Initializes the agent's state.
*   **AgentLogic.md:** Contains the primary logic and algorithms for each agent.
*   **DataProcessing.md:** Handles data processing and transformation logic.
*   **InteractionModule.md:** Defines the interaction mechanisms between agents.
*   **MonitoringModule.md:** Tracks agent performance and states.
*   **Configuration.md:** Stores configuration settings.
*   **ExampleAgents.md:**  Repository for sample agent implementations.

## 8. Development Practices

*   Follow a consistent coding style throughout the project.
*   Use version control (Git) religiously.
*   Write clear and well-documented code.
*   Conduct regular code reviews.
*   Prioritize code readability and maintainability.

## 9.  Specific Considerations for AI Agents

*   All data transformations must be explicitly documented.
*   Error handling mechanisms must be robust and provide informative messages.
*   Consider using techniques for probabilistic reasoning where appropriate.
*   Ensure the agent's reasoning process is traceable and understandable.

## 10.  Mandatory Elements

*   Include a section defining "AgentId" and its purpose.
*   Implement a mechanism for tracking agent versions.
*   Include a section for defining "AgentCapabilities".

These guidelines are intended to provide a comprehensive framework for the development of AGENTS.md.  They are subject to change and refinement as the project evolves.
```