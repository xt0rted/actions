<!--lint disable awesome-badge awesome-code-of-conduct awesome-contributing awesome-git-repo-age awesome-github-->
# GitHub Actions

## Contents

- [dotnet](#dotnet)
- [Frontend](#frontend)
- [Tools](#tools)
- [Repository Templates](#repository-templates)
- [Samples](#samples)
- [NPM Packages](#npm-packages)
- [Miscellaneous](#miscellaneous)

## dotnet

- [dotnet-format](https://github.com/xt0rted/dotnet-format) - A wrapper around `dotnet-format` used to lint and fix violations.
- [dotnet-format-problem-matcher](https://github.com/xt0rted/dotnet-format-problem-matcher) - A problem matcher to highlight `dotnet-format` errors in the build log and create annotations.
- [dotnet-tool-restore](https://github.com/xt0rted/dotnet-tool-restore) - Restores dotnet local tools saved in the `.config/dotnet-tools.json` file.

## Frontend

- [stylelint-problem-matcher](https://github.com/xt0rted/stylelint-problem-matcher) - A problem matcher to highlight [stylelint](https://github.com/stylelint/stylelint) errors in the build log and create annotations.

## Tools

- [block-autosquash-commits-action](https://github.com/xt0rted/block-autosquash-commits-action) - Prevent merging pull requests that have commit messages starting with `fixup!` or `squash!`.
- [markdownlint-problem-matcher](https://github.com/xt0rted/markdownlint-problem-matcher) - A problem matcher to highlight [markdownlint-cli](https://github.com/igorshubovych/markdownlint-cli) errors in the build log and create annotations.
- [pull-request-comment-branch](https://github.com/xt0rted/pull-request-comment-branch) - Gets the branch name and sha for pull request comments so you can act on that branch instead of the default branch.
- [slash-command-action](https://github.com/xt0rted/slash-command-action) - Check comments for `/commands` with optional arguments and pass them to other steps in the workflow.

## Repository Templates

[Repository templates](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) to make getting started with actions easier.

- [problem-matcher](https://github.com/xt0rted/problem-matcher) - A template action for quickly setting up problem matchers.

## Samples

- [actions-cake-demo](https://github.com/xt0rted/actions-cake-demo) - Demo project using GitHub Actions and Cake to build & deploy a .NET Core website to Azure App Services.

## NPM Packages

- [github-actions-problem-matcher-typings](https://github.com/xt0rted/github-actions-problem-matcher-typings) - TypeScript typings for the GitHub Actions problem matcher file format.
- [stylelint-actions-formatters](https://github.com/xt0rted/stylelint-actions-formatters) - Stylelint report formatters that emit fully qualified file paths so annotations can be created with the problem matcher.

## Miscellaneous

- [annotation-previewer](https://github.com/xt0rted/annotation-previewer) - A page to [preview annotation commands](https://xt0rted.github.io/annotation-previewer/) without having to run a workflow.
