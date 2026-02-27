# Contributing to VibeTensor

Thank you for your interest in contributing to VibeTensor projects. We welcome contributions from the community and are grateful for every pull request, bug report, and feature suggestion.

## Getting Started

1. **Fork the repository** you want to contribute to
2. **Clone your fork** locally
3. **Create a branch** for your changes: `git checkout -b feature/your-feature-name`
4. **Make your changes** following our coding standards
5. **Test your changes** thoroughly
6. **Commit with a clear message** following our commit conventions
7. **Push to your fork** and submit a pull request

## Development Setup

Each repository has its own setup instructions in its README. Generally:

```bash
# Clone the repo
git clone https://github.com/VibeTensor/<repo-name>.git
cd <repo-name>

# Install dependencies
npm install   # for TypeScript/JavaScript projects
pip install -e .  # for Python projects

# Run development server
npm run dev   # or equivalent
```

## Branch Naming Convention

Use descriptive branch names with a category prefix:

- `feature/short-description` - New features
- `fix/issue-description` - Bug fixes
- `refactor/what-changed` - Code restructuring
- `docs/what-updated` - Documentation changes
- `test/what-tested` - Test additions or updates

Always branch from `main` unless told otherwise by a maintainer.

## Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat(scope): add new feature description
fix(scope): fix bug description
docs(scope): update documentation
refactor(scope): restructure code without behavior change
test(scope): add or update tests
chore(scope): maintenance tasks
```

**Examples:**
- `feat(auth): add OAuth2 login support`
- `fix(api): handle null response from endpoint`
- `docs(readme): update installation instructions`

## Pull Request Guidelines

- **Keep PRs focused** - One feature or fix per pull request
- **Write a clear description** explaining what changed and why
- **Include a test plan** describing how to verify the changes
- **Reference related issues** using `Fixes #123` or `Relates to #456`
- **Ensure CI passes** before requesting review
- **Be responsive** to review feedback

### Review Process

- A maintainer will review your PR within **3 business days**
- Small fixes (typos, docs) may be merged faster
- Larger changes may require multiple review rounds
- If you have not received feedback within a week, feel free to leave a polite comment

### PR Template

When creating a PR, include:

```markdown
## Summary
Brief description of changes

## Changes
- Bullet points of what changed

## Test Plan
- How to verify the changes work

## Related Issues
Fixes #(issue number)
```

## Coding Standards

### TypeScript / JavaScript
- Use ES modules (`import`/`export`)
- Prefer `const` over `let`, never use `var`
- Use TypeScript strict mode
- Follow existing code patterns in the repository

### Python
- Follow PEP 8 style guidelines
- Use type hints where applicable
- Write docstrings for public functions

### General
- Write self-documenting code with clear variable and function names
- Add comments only where logic is not self-evident
- Keep functions small and focused
- Handle errors appropriately at system boundaries

## Reporting Bugs

When reporting bugs, please include:

1. **Description** of the bug
2. **Steps to reproduce** the behavior
3. **Expected behavior** vs actual behavior
4. **Environment** (OS, Node version, Python version, browser, etc.)
5. **Screenshots** if applicable
6. **Error logs** or stack traces

Use the bug report issue template when available.

## Suggesting Features

We welcome feature suggestions. When proposing a feature:

1. **Check existing issues** to avoid duplicates
2. **Describe the problem** the feature would solve
3. **Propose a solution** with as much detail as possible
4. **Consider alternatives** you have thought about

## Security Vulnerabilities

If you discover a security vulnerability, please **do not** open a public issue. Instead, report it responsibly by emailing **info@vibetensor.com** with details. See our [Security Policy](SECURITY.md) for more information.

## License

By contributing, you agree that your contributions will be licensed under the same license as the project you are contributing to. Check the repository's LICENSE file for details.

## Questions?

If you have questions about contributing, feel free to:
- Open a discussion in the relevant repository
- Email us at info@vibetensor.com

---

**VibeTensor Private Limited** - Built to Trust.
