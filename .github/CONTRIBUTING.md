# Contributing to LanikSJ

We appreciate your interest in contributing to our project! This document provides
guidelines and information for contributors.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Development Process](#development-process)
- [Pull Request Process](#pull-request-process)
- [Coding Guidelines](#coding-guidelines)
- [Testing](#testing)
- [Documentation](#documentation)

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct.
By participating, you are expected to uphold this code.

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors
and maintainers pledge to making participation in our project and our community a
harassment-free experience for everyone, regardless of age, body size, disability,
ethnicity, gender identity and expression, level of experience, nationality,
personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information, such as a physical or electronic address,
  without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional
  setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable
behavior and are expected to take appropriate and fair corrective action in response
to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject
comments, commits, code, wiki edits, issues, and other contributions that are not
aligned to this Code of Conduct, or to ban temporarily or permanently any
contributor for other behaviors that they deem inappropriate, threatening,
offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces when
an individual is representing the project or its community. Examples of
representing a project or community include using an official project e-mail
address, posting via an official social media account, or acting as an appointed
representative at an online or offline event. Representation of a project may be
further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported
by contacting the project team at [forums.lanik.us](https://forums.lanik.us).
All complaints will be reviewed and investigated and will result in a response that
is deemed necessary and appropriate to the circumstances. The project team is
obligated to maintain confidentiality with regard to the reporter of an incident.
Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith
may face temporary or permanent repercussions as determined by other members of the
project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version
2.1, available at
[https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][version].

[homepage]: https://www.contributor-covenant.org
[version]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues as you might find out
that you don't need to create one. When you are creating a bug report, please
include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed after following the steps**
- **Explain which behavior you expected to see instead and why**
- **Include screenshots and animated GIFs if possible**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement
suggestion, please include:

- **Use a clear and descriptive title**
- **Provide a step-by-step description of the suggested enhancement**
- **Provide specific examples to demonstrate the steps**
- **Describe the current behavior and explain which behavior you expected to see
  instead**
- **Explain why this enhancement would be useful**

### Your First Code Contribution

Unsure where to begin contributing? You can start by looking through these
beginner-friendly and help-wanted issues:

- **Beginner issues** - issues which should only require a few lines of code
- **Help wanted issues** - issues which should be a bit more involved than
  beginner issues

## Development Process

### Prerequisites

Before you begin, ensure you have the following installed:

- [List specific requirements for your project]
- [Add any necessary tools, dependencies, etc.]

### Setting Up Your Development Environment

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:

   ```bash
   git clone https://github.com/YOUR_USERNAME/laniksj.git
   cd laniksj
   ```

3. **Add upstream remote**:

   ```bash
   git remote add upstream https://github.com/LanikSJ/laniksj.git
   ```

4. **Create a virtual environment** (if applicable):

   ```bash
   # For Python projects
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

5. **Install dependencies**:

   ```bash
   # For Node.js projects
   npm install

   # For Python projects
   pip install -r requirements.txt
   ```

### Working on Issues

1. **Choose an issue** from the available issues
2. **Create a branch** for your work:

   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix-name
   ```

3. **Make your changes** following our coding guidelines
4. **Test your changes** thoroughly
5. **Commit your changes** with a clear commit message:

   ```bash
   git commit -m "Add feature: brief description of changes"
   ```

## Pull Request Process

### Before Submitting

1. **Ensure your code follows our style guidelines**
2. **Run the test suite** and ensure all tests pass
3. **Update documentation** as needed
4. **Add tests** for new functionality
5. **Ensure your branch is up to date** with the main branch:

   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

### Pull Request Guidelines

1. **Fill out the pull request template completely**
2. **Ensure any install or build dependencies are removed** before the end of the
   layer when doing a build
3. **Update the README.md** with details of changes to the interface, including:

   - New environment variables
   - Exposed ports
   - Useful file locations
   - Container parameters

4. **Increase version numbers** in any examples files and the README.md to the new
   version that this Pull Request would represent. The versioning scheme we use is
   [SemVer](https://semver.org/)
5. **Your pull request will be merged** once you have the sign-off of two other
   developers, or if you do not have permission to do that, you may request the
   second reviewer to merge it for you

### Pull Request Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Testing
- [ ] I have tested these changes locally
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes

## Checklist
- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
```

## Coding Guidelines

### General Guidelines

- **Follow the existing code style** in the project
- **Write clear, meaningful commit messages**
- **Keep functions and methods focused** - do one thing well
- **Add comments** for complex logic or when the purpose isn't immediately obvious
- **Use meaningful variable and function names**

### Language-Specific Guidelines

#### Python

- Follow [PEP 8](https://pep8.org/) style guidelines
- Use type hints where applicable
- Write docstrings for all public functions and classes

#### JavaScript/TypeScript

- Follow the project's ESLint configuration
- Use meaningful variable names
- Prefer const and let over var

#### General

- Keep lines to a reasonable length (typically 80-120 characters)
- Use spaces for indentation (no tabs)
- Remove trailing whitespace

## Testing

### Running Tests

```bash
# Run all tests
npm test  # or python -m pytest

# Run specific test files
npm test -- specific-test-file.js

# Run tests in watch mode
npm run test:watch
```

### Writing Tests

- **Write tests for all new functionality**
- **Maintain high test coverage** (>80%)
- **Use descriptive test names** that explain what is being tested
- **Follow the AAA pattern**: Arrange, Act, Assert

### Test Types

- **Unit tests**: Test individual functions/methods
- **Integration tests**: Test how components work together
- **End-to-end tests**: Test complete user workflows

## Documentation

### What to Document

- **All public APIs** (functions, classes, methods)
- **Configuration options**
- **Installation and setup instructions**
- **Examples and usage patterns**

### Documentation Style

- **Use clear, concise language**
- **Include code examples** where helpful
- **Keep documentation up-to-date** with code changes
- **Use proper markdown formatting**

### Where to Find Documentation

- **README.md**: Main project overview
- **API documentation**: Generated from code comments
- **Wiki**: Additional guides and tutorials

## Additional Resources

- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Writing Good Commit Messages](https://chris.beams.io/posts/git-commit/)
- [Code Review Best Practices](https://github.com/features/code-review/)

## Questions?

If you have questions about contributing, please:

1. **Check existing issues** and documentation
2. **Create a new issue** with the "question" label
3. **Contact the maintainers** at [forums.lanik.us](https://forums.lanik.us)

Thank you for contributing to LanikSJ!
