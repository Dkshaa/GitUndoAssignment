# Git Stash Workflow

`git stash` is useful when you need to pause unfinished work without committing it.

## Save Current Work

```bash
git stash push -m "practice undo changes"
```

Use a message so the stash is easier to recognize later.

## View Saved Stashes

```bash
git stash list
```

This shows each saved stash with an index such as `stash@{0}`.

## Restore a Stash

```bash
git stash pop
```

`pop` applies the latest stash and removes it from the stash list.

## Safer Restore

```bash
git stash apply
```

`apply` keeps the stash saved, which is helpful while practicing.
