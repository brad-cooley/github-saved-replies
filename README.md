# GitHub Saved Replies

A collection of GitHub saved reply templates for consistent, structured PR reviews. Each template is a Markdown file you can copy into your GitHub [saved replies](https://docs.github.com/en/get-started/writing-on-github/working-with-saved-replies) for quick access during code reviews.

## Templates

### Inline review comments

| Template                         | File                                 | Description                                                                                                                       |
| -------------------------------- | ------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| Bug, blocking                    | `bug-blocking.md`                    | Flag a bug found during review, with space to describe the issue and steps to reproduce. Blocks merging.                          |
| Critical Issue, blocking         | `critical-blocking.md`               | Raise a critical issue such as a security vulnerability, data loss risk, or broken functionality that must be fixed before merge. |
| Suggestion, blocking             | `suggestion-blocking.md`             | Propose a specific code change that must be addressed before merging. Supports GitHub's suggestion syntax.                        |
| Suggestion, non-blocking         | `suggestion-non-blocking.md`         | Propose an optional code change the author can take or leave. Supports GitHub's suggestion syntax.                                |
| Code Clarification, blocking     | `code-clarification-blocking.md`     | Request clarification on unclear code that must be resolved before the PR can proceed.                                            |
| Code Clarification, non-blocking | `code-clarification-non-blocking.md` | This code could benefit from clarification, but it doesn't block merging.                                                         |
| Nit pick, non-blocking           | `nit-pick-non-blocking.md`           | Minor style or preference feedback that doesn't affect functionality. Fine to ignore.                                             |
| Praise                           | `praise.md`                          | Call out something the author did well like a clever solution, clean refactor, great tests, etc.                                  |

### Overall review comments

| Template                      | File                                                | Description                                                                                             |
| ----------------------------- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Approved                      | `overall-comments-approved.md`                      | Overall summary comment to accompany an approval.                                                       |
| Changes Requested             | `overall-comments-needs-changes.md`                 | Overall summary comment when requesting changes, referencing inline feedback.                           |
| Further Clarifications Needed | `overall-comments-further-clarifications-needed.md` | Overall summary comment when you have open questions that need answers before you can finish reviewing. |

### Other

| Template | File         | Description                    |
| -------- | ------------ | ------------------------------ |
| Ship it  | `ship-it.md` | The classic :shipit: squirrel. |

## How to add these as GitHub saved replies

1. Go to [github.com/settings/replies](https://github.com/settings/replies).
2. For each template above, click **Add a saved reply**.
3. Set the **Title** to the template name (e.g. "Bug, blocking").
4. Copy the raw Markdown content of the file into the **Reply** body.
5. Click **Add saved reply**.

Once saved, you can insert any of these replies during a PR review by clicking the saved replies button (the icon with a curved arrow) in the comment toolbar, or by using the `Ctrl+.` / `Cmd+.` keyboard shortcut.
