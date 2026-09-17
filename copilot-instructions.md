# GitHub Copilot Instructions

This document provides guidelines and context for GitHub Copilot when generating code, documentation, or responses within this repository.

## 🏗️ Repository Overview & Standards

* **Project Conventions:** Always follow the code structure, formatting, and contribution workflows defined in [`CONTRIBUTING.md`](./CONTRIBUTING.md).
* **Issue & PR Standards:** Ensure all suggested PR descriptions, commit messages, and issue resolutions align with the templates in `.github/PULL_REQUEST_TEMPLATE/`.
* **Security First:** Never hardcode secrets, API keys, passwords, or credentials. Refer to [`SECURITY.md`](./SECURITY.md) for security practices and vulnerability handling.

## 💻 Code Generation Guidelines

* **Style & Consistency:** Match the existing coding style, indentation, and naming conventions present across the project.
* **Documentation:** Write clear, concise docstrings and inline comments for non-obvious logic.
* **Error Handling:** Implement explicit error handling rather than suppressing errors or returning generic failures.
* **Testing:** When writing or modifying features, generate accompanying unit tests that align with the existing testing suite.
* **Dependencies:** Avoid introducing unnecessary external dependencies. Prefer built-in libraries or tools already declared in project configuration files.

## 📝 Commit & PR Messaging

* Format commit messages using standard **Conventional Commits** (`feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`).
* When asked to draft a Pull Request description, default to using the relevant template under `.github/PULL_REQUEST_TEMPLATE/`.
