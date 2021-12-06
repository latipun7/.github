# Commit Message Guide

Generally, please read and follow [Conventional Commits](http://conventionalcommits.org/) guide.

```git
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Use these commit message `type`:

- `feat` or `feature`: A new feature ✨
- `fix`: A bug fix / patches 🐛
- `perf`: A code change that improves performance ⚡
- `revert`: Reverts a previous commit ♻️
- `docs`: Documentation only changes 📚
- `security`: Changes that resolve security vulnerabilities 🔐
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc) 🎨
- `chore`: Other changes that don't modify src or test files 🧹
- `refactor`: A code change that neither fixes a bug nor adds a feature 🎯
- `test`: Adding missing tests or correcting existing tests 🧪
- `build`: Changes that affect the build system or external dependencies (example scopes: `yarn`, `deps`, `deps-dev`, `deps-tree`) 🏗️
- `ci`: Changes to CI configuration files and scripts (example scopes: Github Actions, Travis, Circle, BrowserStack) 🚚

Default git message for **Merge** and **Revert** still allowed.
