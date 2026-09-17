# Contributing Guidelines

Thank you for taking the time to contribute to this project!
We welcome contributions from everyone, whether you are fixing a bug, improving documentation, or proposing new features.

## 📜 Table of Contents
- [Contributing Guidelines](#contributing-guidelines)
  - [📜 Table of Contents](#-table-of-contents)
  - [📜 Code of Conduct](#-code-of-conduct)
  - [💡 How Can I Contribute?](#-how-can-i-contribute)
    - [Reporting Bugs](#reporting-bugs)
    - [Suggesting Features](#suggesting-features)
    - [Submitting Pull Requests](#submitting-pull-requests)
  - [⚙️ Development Workflow](#️-development-workflow)
  - [📝 Commit Message Guidelines](#-commit-message-guidelines)

## 📜 Code of Conduct

Please be respectful, constructive, and polite to all participants in this project. We aim to foster an inclusive and welcoming environment for everybody.

## 💡 How Can I Contribute?

### Reporting Bugs

Before creating a bug report, please check the existing issues to see if the bug has already been reported.

When submitting a bug report, please include:

* A clear, descriptive title.
* Steps to reproduce the issue.
* Expected vs. actual behavior.
* Environment details (OS, runtime version, etc.).

### Suggesting Features

Feature requests are tracked as GitHub Issues. When proposing a new feature:

* Provide a clear and detailed explanation of the feature.
* Describe the use case and why this enhancement would be beneficial.

### Submitting Pull Requests

1. **Fork** the repository and create your branch from `main`.
2. Ensure your code passes all existing tests and linters.
3. Add or update tests where relevant.
4. Update documentation if your changes modify behavior or introduce new options.
5. Create a Pull Request (PR) with a clear description using the appropriate PR template.

## ⚙️ Development Workflow

1. **Fork & Clone** the repository:
  ```bash
  git clone [https://github.com/jasonouellet/PROJECT-NAME.git](https://github.com/jasonouellet/PROJECT-NAME.git)
  cd PROJECT-NAME
  ```
2. Create a topic branch:
  ```bash
  git checkout -b feature/my-new-feature
  # or
  git checkout -b bugfix/fix-some-bug
  ```
3. Make your changes and test them locally.
4. Push to your fork:
  ```bash
  git push origin feature/my-new-feature
  ```
5. Open a Pull Request against the main branch.
   
## 📝 Commit Message Guidelines

We recommend using clear and descriptive commit messages following the Conventional Commits format:

* `feat`: for new features
* `fix`: for bug fixes
* `docs`: for documentation changes
* `refactor`: for code restructures without functional changes
* `test`: for adding or updating tests
* `chore`: for routine tasks or dependency updates

Example: feat: add user authentication handler
