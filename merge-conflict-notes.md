# Merge Conflict Notes

Merge conflicts happen when Git cannot combine changes automatically.

## Basic Workflow

```bash
git status
```

Start by checking which files have conflicts.

## Resolve the File

Open each conflicted file and choose the final content to keep. Remove conflict markers such as `<<<<<<<`, `=======`, and `>>>>>>>`.

## Finish the Merge

```bash
git add <file>
git commit
```

After all conflicts are resolved and staged, complete the merge with a commit.

## Tip

Resolve one file at a time and run `git status` often.
