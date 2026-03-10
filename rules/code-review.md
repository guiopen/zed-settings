Perform a thorough code review of the staged changes following the steps below:

1. Run `git diff --staged --name-only` to get the list of modified files.
2. Run `git diff --staged` to understand exactly what lines were added, modified, or removed.
3. Read the full current content of those specific files, alongside any related files if necessary to understand the broader context of the changes.
4. Using the gathered context, provide a code review of the staged changes, focusing on bugs, improvements, and best practices.
5. If you spot issues in the surrounding code outside the diff, comment on them discreetly at the very end of your response, completely separated from the main review.

Formatting rules: Be direct. Skip summaries of what the changes do and skip positive feedback. Only output actionable issues and concrete suggestions for improvement, grouped by file.
