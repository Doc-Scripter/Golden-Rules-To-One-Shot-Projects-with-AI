# Golden Rules To One-Shot Projects with AI
This guide empowers AI agents to achieve high accuracy, effective debugging, and seamless integration, ensuring project success with minimal correction prompts.
## Getting started
- There are different methods to setup rules for AI agents to follow in a project , use the one suited for your coding AI :
### Qodo
Go to the projects settings and click preferences then add the rules 
### Github Copilot
- enter this in the terminal .
```bash
mkdir .github
cd .github
touch copilot-instructions.md
```
### Trae IDE
- create a .trae folder 
```bash
mkdir .trae
cd .trae
touch projects_rules.md
```
OR 
- go to the settings in the top right and click rules,then select create `projects_rules.md`
### Cursor AI
- enter this in the terminal .
```bash
mkdir .cursor
cd .cursor
touch cursor_rules.md
```

## Quick Start
Checkout [template](template.md) for a base template , copy and paste in the rules file you created.

## 1. Project Setup
### Define clear project scope and requirements 
- start by defining the purpose/goal and structure of the project like :
  - What is the project about ?
- If project structure is unknown simply tell the AI :
```
create a basic project structure with scalability as the core concern.
```
# Separation of concerns :
  - Clearly define where the frontend ,backend or server location:

## 2. Development Workflow
- Write tests before or after implementation
- Commit small, focused changes
- Document as you go
- Use meaningful commit messages to help you when you need to revert changes

## 3. AI Interaction Best Practices
- Ask specific, focused questions
- Break complex tasks into smaller chunks
- Validate AI-generated code
- Always review suggested changes
- Keep context window focused

## 4. Code Quality
- Maintain consistent coding style
- Follow SOLID principles
- Keep functions small and focused
- Use meaningful variable names
- Comment complex logic

## 5. Testing & Documentation
- Write unit tests for core functionality
- Document API endpoints
- Include setup instructions
- Maintain updated README

## 6. Version Control
- Use feature branches
- Regular commits
- Meaningful commit messages
- Pull request reviews

## 7. Error Handling
- Handle edge cases
- Log errors appropriately
- Provide meaningful error messages

## 8. Security
- Sanitize user input
- Secure API endpoints
- Handle sensitive data carefully
- Regular dependency updates

# Documentation
- **Comprehensive README:** Ensure the `README.md` is always up-to-date, providing clear instructions for setup, usage, and contribution.
- **Comments:** Use comments to explain complex logic, non-obvious decisions, or workarounds.No inline comments,keep the comments on top of the function and keep it short
- **API Documentation:** Document all public APIs, functions, and classes with clear descriptions, parameters, and return values.
- **Design Documents:** For larger features or architectural changes, consider creating separate design documents.

# Code Style and Conventions
- **Consistency is Key:** Adhere to a consistent coding style throughout the entire project. (e.g. how you comment,how you structure you code), this will help the AI understand the codebase and make better decisions.
- **Linter and Formatter:** Utilize automated tools like linters (ESLint, Pylint) and formatters (Prettier, Black) to enforce style guidelines and catch common errors.

## Naming Conventions
- **Descriptive Names:** Use clear, descriptive names for variables, functions, classes, and files that indicate their purpose.
- **Case Conventions:** Follow established case conventions for your language (e.g., `camelCase` for JavaScript variables, `snake_case` for Python variables, `PascalCase` for class names).
- **Avoid Abbreviations:** Unless widely understood, avoid excessive abbreviations.

## Comments
- **Why, Not What:** Comments should explain *why* a piece of code does something, not just *what* it does (which should be evident from the code itself).
- **Keep them Updated:** Outdated comments are worse than no comments. Ensure comments are updated when code changes.
- **TODOs and FIXMEs:** Use `TODO` comments for planned work and `FIXME` for known issues that need addressing.

## Modularity
- **Separation of Concerns:** Design components to have distinct responsibilities. Each module, class, or function should do one thing and do it well.
- **Loose Coupling, High Cohesion:** Minimize dependencies between modules (loose coupling) and ensure elements within a module are functionally related (high cohesion).
- **Keep Code Files Short:** Limit your code files to a reasonable size, ideally under 500 lines, to improve readability and maintainability.

# Project-Specific Rules
- **Technology Stack:** Clearly define and adhere to the chosen technology stack and versions.
- **Dependency Management:** Establish clear guidelines for adding, updating, and managing project dependencies.
- **Configuration Management:** Define how configuration settings are managed (e.g., environment variables, config files) and accessed.

## Error Handling
- **Graceful Degradation:** Implement error handling that allows the application to fail gracefully, providing informative messages to users or logs.
- **Centralized Error Logging:** Use a consistent and centralized mechanism for logging errors, including relevant context (stack traces, request details).
- **Specific Exceptions:** Use specific exception types rather than generic ones to make error handling more precise.

## Code Review
- **Mandatory Reviews:** All code changes should undergo a review process by at least one other team member.
- **Checklist:** Use a code review checklist to ensure consistency and cover key areas like functionality, style, tests, and documentation.
- **Constructive Feedback:** Provide constructive and actionable feedback during code reviews, focusing on the code rather than the person.


By adhering to these principles, the AI will operate with a heightened sense of responsibility and foresight, leading to more accurate, robust, and successful project outcomes with minimal corrective intervention.
