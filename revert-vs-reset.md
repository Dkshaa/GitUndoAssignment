# Revert vs Reset

`git revert` and `git reset` both undo work, but they are useful in different situations.

## Use Revert For Shared History

```bash
git revert <commit>
```

`git revert` creates a new commit that reverses an older commit. It is safer when the commit has already been pushed.

## Use Reset For Local History

```bash
git reset --soft HEAD~1
git reset --mixed HEAD~1
```

`git reset` moves the current branch pointer. Use it carefully, especially before pushing work to a shared branch.

## Rule of Thumb

Use `revert` after pushing. Use `reset` while cleaning up local work.
