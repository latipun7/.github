# Commit Message Guide

Generally, please read and follow [Conventional Commits](http://conventionalcommits.org/) guide.

```git
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Use these commit message `type`:

- `feat` or `feature`: A new feature โจ
- `fix`: A bug fix / patches ๐
- `perf`: A code change that improves performance โก
- `revert`: Reverts a previous commit โป๏ธ
- `docs`: Documentation only changes ๐
- `security`: Changes that resolve security vulnerabilities ๐
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc) ๐จ
- `chore`: Other changes that don't modify src or test files ๐งน
- `refactor`: A code change that neither fixes a bug nor adds a feature ๐ฏ
- `test`: Adding missing tests or correcting existing tests ๐งช
- `build`: Changes that affect the build system or external dependencies (example scopes: `yarn`, `deps`, `deps-dev`, `deps-tree`) ๐๏ธ
- `ci`: Changes to CI configuration files and scripts (example scopes: Github Actions, Travis, Circle, BrowserStack) ๐

Default git message for **Merge** and **Revert** still allowed.
