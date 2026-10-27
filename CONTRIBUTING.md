# Contributing Guidelines

Thank you for considering contributing to this project! We welcome contributions of all kinds, whether it’s bug reports, feature requests, documentation improvements, or code contributions. Please follow the guidelines below to make the process smooth for both you and the maintainers.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Development Setup](#development-setup)
- [Commit Message Guidelines](#commit-message-guidelines)
- [License](#license)

## Code of Conduct

Please note that this project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How to Contribute

### Reporting Bugs

1. **Search existing issues** to see if the bug has already been reported.
2. If not, open a new issue and include:
   - A clear title and description.
   - Steps to reproduce the bug.
   - Expected vs. actual behavior.
   - Your environment (OS, Python version, etc.).

### Suggesting Enhancements

1. Check the existing issues for similar feature requests.
2. Open a new issue with a concise title and a detailed description of the proposed change, including any relevant use‑cases.

### Submitting Pull Requests

1. **Fork the repository** and create a new branch for your changes.
2. Follow the **Development Setup** steps below to get the project running locally.
3. Make your changes, ensuring they are well‑tested and documented.
4. **Write clear commit messages** (see guidelines below).
5. Push your branch to your fork and open a pull request against the `main` branch.
6. Provide a descriptive PR title and body, linking any related issues.
7. Respond to any review feedback promptly.

## Development Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run tests** to ensure everything is working:
   ```bash
   pytest
   ```
5. **Make your changes** and ensure that the test suite passes.

## Commit Message Guidelines

- Use the **imperative mood** (e.g., `Add feature`, `Fix bug`).
- Keep the subject line under 50 characters.
- Separate the subject from the body with a blank line.
- Provide a detailed description in the body if necessary, explaining **what** and **why**.
- Reference related issues using `#<issue-number>`.

**Example**:
```
Add support for XYZ feature

Implemented the XYZ functionality to allow users to ...

Closes #42
```

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (see the `LICENSE` file).

---

Thank you for helping improve this project! If you have any questions, feel free to reach out in the issue tracker.
