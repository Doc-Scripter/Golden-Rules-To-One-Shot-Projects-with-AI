# Golden Rules To One-Shot Projects with AI
This guide outlines the critical considerations and steps for AI agents to ensure high accuracy, effective debugging, seamless integration, and overall project success. The goal is to empower the AI with a deep understanding of the consequences and necessary actions for top-tier performance, minimizing the need for subsequent correction prompts.
## Getting this started
- There are different methods to setup rules for ai to follow in a project ,please check the one suited for your coiding AI :
### Qodo
Go to the projects settings and click preferences then add the rules 
### Github Copilot
- create a .github folder 
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
### Cursor

## Quick Start
Checkout [template](template.md) for instructions already tailored for high accuracy,simple copy and paste in the rules file youve created.

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

# Code Style and Conventions

## Naming Conventions   

## Comments

## Modularity
- maintain sepration of concerns ,Keep Code Files Short: Limit your code files to under 500 lines.
# Project-Specific Rules

## Error Handling

## Code Review


By adhering to these principles, the AI will operate with a heightened sense of responsibility and foresight, leading to more accurate, robust, and successful project outcomes with minimal corrective intervention.
