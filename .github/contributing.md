# Contribution Guide

Be nice and respect the maintainers' time. ❤️

Please read this whole thing. Most of this applies to any repo on GitHub. 🙏

## Contribute

Code is not the only thing you can contribute. I truly appreciate contributions in the form of:

- Fixing typos.
- Improving docs.
- Triaging [issues][latipun-issues].
- Reviewing [pull requests][latipun-pr].
- Sharing your opinion on issues.

I would love for you to contribute and help to make it better. I welcome you [with arms wide open~ 🎶][creed]

## Issues

- Before opening a new issue, look for existing issues (even closed ones).
- [Don't needlessly bump issues][issue-bumping].
- If you're reporting a bug, include as much information as possible. Ideally, include a test case that reproduces the bug. For example, a [Runkit](https://runkit.com) or [repl.it](https://repl.it) playground.

## Pull requests

### Prerequisite

**Working on your first Pull Request?** You can learn how from this _free_ series ["How to Contribute to an Open Source Project on GitHub"][pr-course].

- If the changes are large or breaking, open an issue discussing it first.
- Don't open a pull request if you don't plan to see it through. Maintainers waste a lot of time giving feedback on pull requests that eventually go stale.
- Don't do unrelated changes.
- Adhere to the existing code style.
- If relevant, add tests, check for typos, and add docs and types.
- Don't add editor-specific metafiles. Those should be added to your own [global gitignore][global-gitignore].
- Don't be sloppy. I expect you to do your best.
- Adhere to the existing [commit message guide](#commit-message-guide).
- Squash your local commits into one commit before submitting the pull request, unless you have important atomic commits.
- Double-check your contribution by going over the diff of your changes before submitting a pull request. It's a good way to catch bugs/typos and find ways to improve the code.
- Do the pull request from a new branch. Never from the default branch (_example: `main`_).

### Submission

- Give the pull request a clear title using [commit message guide](#commit-message-guide).
- Give the pull request clear descriptions. It's up to you to convince the maintainers why your changes should be merged.
- If the pull request fixes an issue, [reference it in the pull request description][pr-link-issue] using the syntax `Fixes #123`, `Closes #123`, or `Resolves #123`, where `123` is the issue's number.
- Make sure the **Allow edits from maintainers** checkbox is checked. That way, maintainers can make certain minor changes themself, allowing your pull request to be merged sooner.

### Review

- Push new commits when doing changes to the pull request. Don't squash as it makes it hard to see what changed since the last review. I will squash when merging.
- It's better to present solutions than asking questions.
- Review the pull request diff after each new commit. It's better that you catch mistakes early than the maintainers pointing it out and having to go back and forth.
- Be patient. Feel free to bump the pull request if you haven't received a reply in a couple of weeks.
- And most importantly, have fun! 👌🎉

## Commit Message Guide

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

<!-- Variables -->

[latipun-issues]: https://github.com/search?q=user%3Alatipun7+user%3Aruppyio+is%3Aissue+is%3Aopen+NOT+%22Dependency+Dashboard%22&type=Issues "Open Issues"
[latipun-pr]: https://github.com/search?q=user%3Alatipun7+user%3Aruppyio+is%3Apr+is%3Aopen+-author%3Aapp%2Fpull+-author%3Aapp%2Fdependabot+-author%3Aapp%2Fdependabot-preview+-author%3Aapp%2Frenovate+-author%3Aapp%2Flatipun-renovates+-author%3Aapp%2Fgithub-actions&type=Issues "Open Pull Requests"
[creed]: https://www.youtube.com/watch?v=99j0zLuNhi8 "Creed - With Arms Wide Open"
[issue-bumping]: https://blog.sindresorhus.com/issue-bumping-e3b9740e2a0 "Issue Bumping"
[pr-course]: https://app.egghead.io/playlists/how-to-contribute-to-an-open-source-project-on-github "How to Contribute to an Open Source"
[global-gitignore]: https://gist.github.com/subfuzion/db7f57fff2fb6998a16c "Global Gitignore"
[pr-link-issue]: https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword "Linking a Pull Request to an Issue"
