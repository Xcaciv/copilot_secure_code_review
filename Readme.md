# Copilot Secure Code Review

This repository provides a structured environment for using GitHub Copilot to perform security-focused code reviews. It uses a custom instruction file to guide Copilot's analysis based on established security principles.

## Setup and Usage

To get started, follow these steps:

1.  **Check out the repository:**
    Clone this repository to your local machine using the following command:
    ```bash
    git clone https://github.com/your-username/copilot-secure-code-review.git
    ```

2.  **Add your code:**
    Place the code you want to analyze into the `code_under_review` directory. This directory is intentionally left empty in the repository for you to add your own projects.

    ```
    copilot-secure-code-review/
    ├── .github/
    │   └── copilot-instructions.md
    ├── code_under_review/
    │   └── [Your code goes here]
    └── Readme.md
    ```

## Using GitHub Copilot for Analysis

Once your code is in place, you can start using GitHub Copilot Chat in your IDE (e.g., VS Code) to analyze it. The behavior of Copilot is guided by the files in this repository.

### Copilot Instructions (`.github/copilot-instructions.md`)

This file acts as a "meta-prompt" or system message that sets the context for all your interactions with Copilot within this workspace. It instructs Copilot to adopt a specific persona—in this case, a "Tenacious Security Architect"—and to frame its analysis using the FIASSE Securable Software Engineering model (SSEM).

By defining the persona and rules in this file, you ensure that Copilot's suggestions and analyses are consistently focused on security, maintainability, trustworthiness, and reliability.

### Slash Commands

Slash commands are shortcuts you can use in the Copilot Chat window to perform common tasks. They are powerful tools for interacting with your codebase.

Here are some useful commands:

*   `@workspace /explain`: Ask Copilot to explain the entire workspace or a specific part of it. This is useful for getting a high-level overview of the code in `code_under_review`.
*   `@workspace /tests`: Ask Copilot to generate unit tests for the code in your workspace.
*   `/fix`: Select a piece of code with a potential bug or vulnerability and use this command to ask Copilot for a fix.
*   `/doc`: Generate documentation for a selected function or class.
*   `/explain`: Explain a selected piece of code in detail.

**Example Prompt:**

After adding your code, you can open the Copilot Chat and ask:

> `@workspace Can you identify potential security vulnerabilities in this application based on your security architect persona?`