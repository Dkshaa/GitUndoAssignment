# Git Undo Reference

Quick reminders for safe undo commands while practicing Git.

## Unstage a File

```bash
git restore --staged notes.txt
```

Use this when a file was added to staging by mistake but the working copy should stay unchanged.

## Discard Working Changes

```bash
git restore notes.txt
```

Use this only when the local file changes are no longer needed.

## Undo the Last Commit

```bash
git reset --soft HEAD~1
```

This moves the last commit back into staged changes so it can be edited and committed again.

## Review Before Undoing

```bash
git status
git log --oneline
```

Check the current state and recent history before running an undo command.
