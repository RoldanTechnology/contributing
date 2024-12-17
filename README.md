# 🚀 Contributing to RoldanTechnology 🌟

Thank you for your interest in contributing to **RoldanTechnology**! 🎉 We welcome contributions of all kinds to help us build impactful, open-source solutions in the fields of **Data Science**, **Machine Learning**, and **Software Engineering**.

Please follow the guidelines below to ensure a smooth collaboration process. 🙌

## 🔧 How You Can Contribute

Before starting to work on any feature or fix, here is a brief overview of our workflow:
1. Always start from the `development` branch for new features or regular fixes.
2. Create a dedicated branch for your changes (e.g., `feature/...` or `fix/...`).
3. After implementing and testing your changes, open a Pull Request (PR) from your branch to `development`.
4. Once reviewed and approved, changes in `development` will be merged into `main`.

### 1. 🐛 Reporting Issues
If you encounter a bug, have a question, or want to suggest an improvement:
- 🔍 **Check the existing issues** to see if your concern has already been reported.
- 📝 If not, open a new issue and provide as much detail as possible:
  - **🐞 Bug Reports**: Steps to reproduce, expected behavior, and relevant environment details (e.g., OS, Python version, dependencies).
  - **✨ Enhancements**: Describe your idea, its potential benefits, and any implementation suggestions.

### 2. 📬 Submitting Pull Requests

We welcome pull requests for:
- 🐞 Fixing bugs.
- ✨ Adding new features.
- 📝 Improving documentation.

#### 🚀 Steps to Submit a Pull Request:
1. **🍴 Fork the repository**: Click the "Fork" button at the top of the repository page.

2. **💻 Clone your fork**:
```
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

3. **🏁 Switch to `development` and update**:
```
git checkout development
git pull origin development
```

4. **🌿 Create a new branch** from `development` for your changes:
```
git checkout -b feature/your-feature-name
```

5. 🛠️ Make your changes and commit them following our [commit message guidelines](#-commit-guidelines).

6. 🔄 Push your branch to your fork:
```
git push origin feature/your-feature-name
```
   
7. **🚀 Open a pull request** on the original repository to merge `feature/your-feature-name` into `development`:   
- Include a clear description of the changes.
- Reference related issues if applicable.

## 🤝 Code of Conduct

We are committed to providing a **welcoming environment** for all contributors. 🌍 Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) when interacting with others in the community.

## 🌿 Branch Naming Guidelines

To maintain consistency and clarity in the repository, please follow these conventions when creating branches:

- **✨ Features**: `feature/<feature-name>`
  - For example: `feature/add-login-authentication`
- **🐞 Bug Fixes**: `fix/<issue-name>`
  - For example: `fix/fix-null-values-in-preprocessing`
- **📝 Documentation**: `docs/<documentation-topic>`
  - For example: `docs/update-contributing-guide`
- **🚑 Hotfixes**: `hotfix/<critical-fix>`
  - For example: `hotfix/fix-deployment-issue`

> **Note:** All branches should be created from the `development` branch, except for `hotfixes`, which should be created directly from `main` to address urgent issues.

### 🌱 **How to Create a Branch:**

To align with our Git flow process, follow these steps to create a branch and integrate changes efficiently:

1. 🏁 Check out the `development` branch:
   ```bash
   git checkout development
   ```

2. 🔄 Pull the latest changes to ensure your local repository is up-to-date:
   ```bash
   git pull origin development
   ```

3. ✨ Create a new feature branch from `development`:
   ```bash
   git checkout -b feature/<feature-name>
   ```

4. 🛠️ Implement your changes, test them thoroughly, and commit your work following the [commit message guidelines](#-commit-guidelines).

5. 📤 Push your branch to your forked repository:
   ```bash
   git push origin feature/<feature-name>
   ```

6. 🚀 Submit a Pull Request (PR) from your feature branch to the `development` branch. After review and approval, the `development` branch will merge into `main` in a controlled process.

### 📊 Git Workflow Overview:

```
  [main]  <---------- [PR: development -> main]
    ^                        ^
    |                        |
 [PR: feature/<feature-name> -> development]
    ^
    |
[feature/<feature-name>]
```

This structure ensures that:
- ✨ Feature branches are isolated until thoroughly reviewed and tested.
- 🛠️ `development` serves as the integration branch for staging and testing changes.
- ✅ `main` remains stable and ready for deployment.

By following this workflow, we can easily implement **CI/CD pipelines** for automated testing, linting, and deployment in the future. 🚀

## 📝 Commit Guidelines

We use **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)** and **[Gitmoji](https://gitmoji.dev/)** to maintain a clear and structured commit history. 📚

**🔖 Format:**
```bash
<type>(scope): <emoji> <short description>

- Extended description (optional).
```

**✨ Examples:**
- `feat(README): :sparkles: Add introductory README`
- `fix(data-cleaning): :bug: Resolve NaN handling issue in pipeline`

### 🔖 Common Types and Emojis:
- **✨ feat**: Introducing new features. (:sparkles:)
- **🐞 fix**: Fixing bugs. (:bug:)
- **📝 docs**: Documentation updates. (:memo:)
- **🎨 style**: Code style improvements. (:art:)
- **🔄 refactor**: Code refactoring. (:recycle:)
- **🧪 test**: Adding or updating tests. (:white_check_mark:)

For more emojis, check the [Gitmoji Guide](https://gitmoji.dev/). 🎉

## 🧹 Development Standards

- Follow [PEP 8 guidelines](https://peps.python.org/pep-0008/) for Python code to maintain a consistent style. 🐍
- Use tools like `flake8` or `pylint` to check code quality, and format your code automatically with `Black`. 🎨
- Ensure your code is **well-documented**. 📄
- Write unit tests for any new functionality or fixes. 🧪

## 🤔 Need Help?

If you have questions, feel free to:
- 🗣 Open a discussion in the repository.
- 🛟 Reach out by opening an issue with the `help wanted` label.

---

🌟 **Thank you for contributing to RoldanTechnology! Together, we can make a difference. 🚀**
