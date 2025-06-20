# Template

## Core Principles for AI Operation:

1.  **High Accuracy and Precision:**
    *   **Understanding the Goal:** Always strive for a complete and precise understanding of the user's request and the project's objectives. If anything is unclear, ask clarifying questions.
    *   **Contextual Awareness:** Utilize all available context (codebase, file structure, previous interactions, relevant documentation) to inform decisions and implementations.
    *   **Verification:** Before making changes, verify assumptions and proposed solutions against existing code and project requirements.

2.  **Debugging Concerns and Proactive Error Handling:**
    *   **Root Cause Analysis:** When errors or unexpected behavior occur, focus on identifying and addressing the root cause rather than just the symptoms.
    *   **Logging and Diagnostics:** Implement clear and descriptive logging to track variable states, execution flow, and potential issues, aiding in debugging.
    *   **Test-Driven Approach:** Where possible, create and run test files for new functionality or code changes to proactively identify syntax errors, incomplete implementations, or poor code editing. Ensure tests cover edge cases and expected behavior.
    *   **Error Prevention:** Anticipate potential failure points and implement robust error handling mechanisms.

3.  **Suggesting and Defining Changes for Project Success:**
    *   **Impact Assessment:** Before suggesting or implementing changes, assess their potential impact on the entire project, including dependencies, performance, and maintainability.
    *   **Clarity and Justification:** Clearly articulate proposed changes, their benefits, and any trade-offs. Provide a strong rationale for why a particular approach is chosen.
    *   **Iterative Refinement:** Be prepared to refine suggestions based on feedback or new information, always aiming for the optimal solution.

4.  **Integration-Oriented Development:**
    *   **Interrelated Code Check:** Thoroughly examine interrelated code and files to ensure that new implementations or modifications integrate seamlessly with existing components.
    *   **Dependency Management:** Be mindful of existing libraries, frameworks, and dependencies. Ensure compatibility and avoid introducing conflicts.
    *   **API Consistency:** Maintain consistency with existing APIs and interfaces when extending or modifying functionality.

5.  **Staying Up-to-Date and Avoiding Duplication:**
    *   **Recent Updates:** Always check for the most recent updates and changes in the file(s) to be adjusted before implementing any modifications to prevent overwriting or conflicts.
    *   **Function Duplication:** Actively avoid duplicating existing functions or logic. Reuse existing code where appropriate to maintain a lean and efficient codebase.

6.  **Respecting Project Structure:**
    *   **Structural Integrity:** Avoid changing the fundamental project structure (e.g., directory layout, core configuration files) unless explicitly instructed to do so by the user.
    *   **Naming Conventions:** Adhere to established naming conventions for files, folders, variables, and functions.

7.  **Code Quality and Review:**
    *   **Syntax and Semantics:** Rigorously check for syntax errors, logical flaws, and incomplete implementations.
    *   **Code Readability:** Write clean, well-commented, and easily understandable code.
    * **Code Consistency:** Do not write inline comments unless that is how the existing project structure is .Otherwise only write function code summary at the top of the function
    
    - **Naming:**  Use meaningful variable names
    *   **Self-Correction:** If a test fails or an issue is identified, take immediate steps to diagnose and correct the problem untill all tests pass.

8.  **README and Documentation:**
    *   **Project Details:** If project details are missing from the `README.md` or other documentation, suggest relevant additions or updates to ensure comprehensive and accurate project information.
    *   **Usage and Setup:** Ensure documentation clearly explains how to use, set up, and contribute to the project.

