# issue-creation-from-lint-result-workflow

A simple GitHub workflow that lints changes and creates issues if the lints fails.
I recommend copying the `.github` file into your new repos to ensure good coding practice.

## How does it work?

1. It lints files with [`super-linter/super-linter@v7.1.0`](https://github.com/super-linter/super-linter)
2. It saves the output of the lint
3. It creates an issue with that output using [`JasonEtco/create-an-issue@v2`](https://github.com/JasonEtco/create-an-issue)

## Basic Info

| When does it lint                                 | What does it lint    |
| ------------------------------------------------- | -------------------- |
| You push a change to the `main` branch.           | All changed files.   |
| You create a pull request into the `main` branch. | All changed files.   |
| It is `6:00pm UTC` on Sundays.                    | The entire codebase. |
| You dispatch the workflow.                        | The entire codebase. |
