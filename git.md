# Git and Github

## The Git workflow - 3 trees
1. Working directory
Use `git add [file_name]` to stage. `git restore [file_name]` to discard changes.
2. `Index` - staging area
Use `git restore --staged [file_name]` to unstage.
3. `Head` - latest commit

## Remote - github
- To connect a local to a remote: `git add remote origin git@github.com:zhoulele12/[repo_name].git`. `origin` here is an alias for the remote dir.
- `git push origin [branch_name]`

## Branching
- `git branch [branch_name]`
- `git checkout [branch_name]`
- `git push --set_upstream origin [branch_name]` connects a local branch to a remote branch

## Merging
- `git merge [branch_name]` merges a branch into your current branch. 
- `git diff [source_branch] [target_branch]` Note that all comparisons and merging take place between `HEAD` (commited changes)

Conflict 2