# Git commands I learned

- `git init` - start a repo
- `git status` - what changed
- `git add <file>` - move changes to staging
- `git commit -m "msg"` - save staged changes
- `git log --oneline` - short history
- `git show HEAD~1` - open a previous commit
- `git show HASH:file` - see a file as it was in a commit
- `git diff` - working dir vs staging
- `git diff --staged` - staging vs last commit
- `git restore <file>` - discard uncommitted changes (permanent!)
- `git revert HEAD` - undo a pushed commit with a new commit
- `git reset --soft HEAD~1` - undo last local commit, keep changes staged
- `git reset HEAD~1` - undo last local commit, keep changes unstaged
- `git reset --hard HEAD~1` - undo last local commit AND delete changes (dangerous)