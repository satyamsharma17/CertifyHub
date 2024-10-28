# Contributing to CertifyHub

Thank you for considering contributing to CertifyHub! We appreciate your support and efforts in improving this decentralized certification platform. Please follow the guidelines below to ensure a smooth contribution process.

## Table of Contents

1. [Getting Started](#getting-started)
2. [How to Contribute](#how-to-contribute)
   - [Reporting Issues](#reporting-issues)
   - [Suggesting Enhancements](#suggesting-enhancements)
   - [Code Contributions](#code-contributions)
3. [Coding Standards](#coding-standards)
4. [Pull Request Process](#pull-request-process)
5. [Contact](#contact)

## Getting Started

1. **Fork the Repository**: Start by forking the CertifyHub repository to your GitHub account.
2. **Clone the Repository**: Clone the forked repository to your local machine:
   ```bash
   git clone https://github.com/<your-username>/CertifyHub.git
   ```
3. **Set Up Remote**: Add the original repository as an upstream remote:
   ```bash
   git remote add upstream https://github.com/Code4All-Club/CertifyHub.git
   ```
4. **Install Dependencies**: Ensure all dependencies are installed:
   ```bash
   npm install
   ```

## How to Contribute

### Reporting Issues

If you find a bug or have a question, please check if it has already been reported. If not, open a new issue and provide:

- A clear and descriptive title.
- Steps to reproduce the issue.
- Expected and actual outcomes.
- Any relevant screenshots or code snippets.

### Suggesting Enhancements

Enhancements and feature requests are welcome! When suggesting an enhancement, please include:

- A detailed description of the enhancement.
- Any relevant use cases or examples.
- Additional context or screenshots (if applicable).

### Code Contributions

1. **Create a Branch**: Always create a new branch for your contributions, branching off `main`:
   ```bash
   git checkout -b feature/<feature-name>
   ```
2. **Write Code**: Follow our [coding standards](#coding-standards) while making your changes.
3. **Commit Changes**: Write descriptive commit messages. Use the following convention:
   ```
   git commit -m "feat: add <feature description>"
   ```

## Coding Standards

1. **Naming Conventions**:
   - Use camelCase for variables and function names.
   - Use PascalCase for component names.
   - Use snake_case for file names.

2. **Documentation**: Document your code, especially complex functions, with comments and docstrings.

3. **Code Formatting**: Ensure consistent code formatting. Use [Prettier](https://prettier.io/) for JavaScript and JSON files:
   ```bash
   npm run format
   ```

4. **Testing**: Write tests for new features and bug fixes. Make sure all tests pass before submitting a pull request.

## Pull Request Process

1. **Pull Changes**: Always pull the latest changes from `main` before submitting a pull request:
   ```bash
   git pull upstream main
   ```
2. **Resolve Conflicts**: Fix any merge conflicts before submitting.
3. **Push Changes**: Push your branch to your forked repository:
   ```bash
   git push origin feature/<feature-name>
   ```
4. **Submit Pull Request**:
   - Go to your forked repository and open a pull request to the `main` branch of `Code4All-Club/CertifyHub`.
   - Add a descriptive title and details of your changes in the pull request description.
   - Link to any related issues.

## Contact

For questions, please reach out to the repository maintainers via [satyamsharma1725@gmail.com](mailto:satyamsharma1725@gmail.com).

Thank you for contributing to CertifyHub!
