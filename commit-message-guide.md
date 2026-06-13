# Commit Message Guide

Clear commit messages make Git history easier to review.

## Format

Use a short sentence that starts with an action verb.

Examples:

- Add Git status checklist
- Explain revert and reset usage
- Fix typo in branch cleanup notes

## Tips

- Keep the first line under about 72 characters.
- Describe what changed, not every command that was used.
- Use present tense, such as `Add`, `Fix`, or `Update`.

## Before Committing

```bash
git status
git diff --cached
```

Review staged changes before writing the commit message.
