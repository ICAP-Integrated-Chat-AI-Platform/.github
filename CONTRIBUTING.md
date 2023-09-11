# Contributor Guidelines

Thank you to all the contributors who have helped make this project possible! We welcome various types of contributions, such as bug reports, documentation improvements, feature requests, and code contributions.

## Contributing Guidelines

If the feature you would like to contribute has not already received prior approval from the project maintainers (i.e., the feature is currently on the [roadmap](https://github.com/orgs/ICAP-Integrated-Chat-AI-Platform/projects/2/views/2)), please submit a request in the [Feature Requests & Suggestions category](https://github.com/orgs/ICAP-Integrated-Chat-AI-Platform/discussions/new?category=features-request) of the discussions board before beginning work on it. The requests should include specific implementation details, including areas of the application that will be affected by the change (including designs if applicable), and any other relevant information that might be required for a speedy review. However, proposals are not required for small changes, bug fixes, or documentation improvements. Small changes and bug fixes should be tied to an [issue](https://github.com/ICAP-Integrated-Chat-AI-Platform/.github/issues) and included in the corresponding pull request for tracking purposes.

Please note that a pull request involving a feature that has not been reviewed and approved by the project maintainers may be rejected. We appreciate your understanding and cooperation.

## Our Standards

We strive to maintain a positive and inclusive environment within our project community. We expect all contributors to adhere to the following standards:

- Using welcoming and inclusive language.
- Being respectful of differing viewpoints and experiences.
- Gracefully accepting constructive criticism.
- Focusing on what is best for the community.
- Showing empathy towards other community members.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that do not align with these standards.

## To contribute to this project, please adhere to the following guidelines:

## 1. Git Workflow

We utilize a GitFlow workflow to manage changes to this project's codebase. Follow these general steps when contributing code:

1. Fork the repository and create a new branch with a descriptive slash-based name (e.g., `new/feature/x`).
2. Implement your changes and ensure that all tests pass.
3. Commit your changes using conventional commit messages with GitFlow flags. Begin the commit message with a tag indicating the change type, such as "feat" (new feature), "fix" (bug fix), "docs" (documentation), or "refactor" (code refactoring), followed by a brief summary of the changes (e.g., `feat: Add new feature X to the project`).
4. Submit a pull request with a clear and concise description of your changes and the reasons behind them.
5. We will review your pull request, provide feedback as needed, and eventually merge the approved changes into the main branch.

## 2. Commit Message Format

We follow the [semantic format](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) for commit messages.

### Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

### Commit Guidelines
- Do your best to reduce the number of commits, organizing them as much possible. Look into [squashing commits](https://www.freecodecamp.org/news/git-squash-commits/) in order to keep a neat history.
- For those that care about maximizing commits for stats, adhere to the above as I 'squash and merge' an unorganized and/or unformatted commit history, which reduces the number of your commits to 1,:
```
* Update Br.tsx

* Update Es.tsx

* Update Br.tsx
```


## 3. Pull Request Process

When submitting a pull request, please follow these guidelines:

- Ensure that any installation or build dependencies are removed before the end of the layer when doing a build.
- Update the README.md with details of changes to the interface, including new environment variables, exposed ports, useful file locations, and container parameters.
- Increase the version numbers in any example files and the README.md to reflect the new version that the pull request represents. We use [SemVer](http://semver.org/) for versioning.

Ensure that your changes meet the following criteria:

- All tests pass as highlighted [above](#1-development-notes).
- The code is well-formatted and adheres to our coding standards.
- The commit history is clean and easy to follow. You can use `git rebase` or `git merge --squash` to clean your commit history before submitting the pull request.
- The pull request description clearly outlines the changes and the reasons behind them. Be sure to include the steps to test the pull request.

## 4. Naming Conventions

Apply the following naming conventions to branches, labels, and other Git-related entities:

- **Branch names:** Descriptive and slash-based (e.g., `new/feature/x`).
- **Labels:** Descriptive and kebab case (e.g., `bug-fix`).
- **JS/TS:** Directories and file names: Descriptive and camelCase. First letter uppercased for React files (e.g., `helperFunction.ts, ReactComponent.tsx`).
- **Docs:** Directories and file names: Descriptive and snake_case (e.g., `config_files.md`).

---

Please ensure that you adapt this summary to fit the specific context and nuances of your project.

---

## [Go Back to ReadMe](../README.md)