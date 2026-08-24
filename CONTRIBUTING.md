# Contributing to Hands-on Git

Thank you for considering contributing to this project! Please take a moment to review these guidelines before submitting your contribution.

## How to Contribute

### 1. Fork the Repository

Click the **Fork** button at the top right of this repository to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/hands-on-git.git
cd hands-on-git
```

### 3. Create a Branch

Create a new branch for your changes. Use a clear, descriptive name that reflects the purpose of your change.

```bash
git checkout -b <branch-name>
```

**Branch naming conventions:**
- `feature/<short-description>` — for new features (e.g. `feature/add-compound-interest`)
- `bugfix/<short-description>` — for bug fixes (e.g. `bugfix/fix-readme-typo`)
- `docs/<short-description>` — for documentation updates (e.g. `docs/update-contributing`)

### 4. Make Your Changes

Make your edits, then stage and commit them with a clear commit message.

```bash
git add .
git commit -m "Brief description of the change"
```

### 5. Push Your Branch

```bash
git push origin <branch-name>
```

### 6. Open a Pull Request

Go to your fork on GitHub and click **Compare & pull request**. Fill in:
- A clear title describing the change
- A short description of what was changed and why

Submit the pull request against the `main` branch of this repository.

### 7. Review Process

- Maintainers will review your pull request and may request changes.
- Once approved, your pull request will be merged into `main`.

## Code Style

- Keep scripts simple and well-commented.
- Use clear, descriptive variable and function names.
- Test any scripts before submitting a pull request.

## Reporting Issues

If you find a bug or have a suggestion, please open an issue describing:
- What you expected to happen
- What actually happened
- Steps to reproduce (if applicable)

## Code of Conduct

By contributing, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
