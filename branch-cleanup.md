# Branch Cleanup Notes

Cleaning up old branches keeps a Git practice repository easier to read.

## List Branches

```bash
git branch
git branch -a
```

Use the local list first, then check remote branches when needed.

## Delete a Merged Local Branch

```bash
git branch -d feature-name
```

The `-d` option protects work by refusing to delete a branch that has not been merged.

## Delete a Remote Branch

```bash
git push origin --delete feature-name
```

Only delete remote branches when you are sure nobody still needs them.
