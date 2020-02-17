# GitHub Actions

Action types:
#️⃣ - Problem matcher,
🧹 - Linter,
🧰 - Build tool,
💬 - ChatOps

## dotnet

| | Name | Description
-- | -- | --
🧹 | [dotnet-format](https://github.com/xt0rted/dotnet-format-problem-matcher) | A wrapper around [dotnet-format](https://github.com/dotnet/format) used to lint and fix violations
#️⃣ | [dotnet-format-problem-matcher](https://github.com/xt0rted/dotnet-format-problem-matcher) | A problem matcher to highlight [dotnet-format](https://github.com/dotnet/format) errors in the build log and create annotations
🧰| [dotnet-tool-restore](https://github.com/xt0rted/dotnet-tool-restore) | Restores dotnet local tools saved in the `.config/dotnet-tools.json` file

## Frontend

| | Name | Description
-- | -- | --
#️⃣ | [stylelint-problem-matcher](https://github.com/xt0rted/stylelint-problem-matcher) | A problem matcher to highlight [stylelint](https://github.com/stylelint/stylelint) errors in the build log and create annotations

## Tools

| | Name | Description
-- | -- | --
🧰 | [block-autosquash-commits-action](https://github.com/xt0rted/block-autosquash-commits-action) | Prevent merging pull requests that have commit messages starting with `fixup!` or `squash!`
🧰 | [pull-request-comment-branch](https://github.com/xt0rted/pull-request-comment-branch) | Gets the branch name and sha for pull request comments so you can act on that branch instead of the default branch
💬 | [slash-command-action](https://github.com/xt0rted/slash-command-action) | Check comments for `/commands` with optional arguments and pass them to other steps in the workflow

## NPM Packages

Name | Description
-- | --
[github-actions-problem-matcher-typings](https://github.com/xt0rted/github-actions-problem-matcher-typings) | TypeScript typings for the Github Actions problem matcher file format
[stylelint-actions-formatters](https://github.com/xt0rted/stylelint-actions-formatters) | Stylelint report formatters that emit fully qualified file paths so annotations can be created with the problem matcher
