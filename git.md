# Git and Github

## The Git workflow - 3 trees
1. Working directory
Use `git add [filename]` to stage. `git restore [filename]` to discard changes ().
2. `Index` - staging area
Use `git restore --staged [filename]` to unstage.
3. `Head` - latest commit

## Remote - github
- To connect a local to a remote: `git add remote origin git@github.com:zhoulele12/[repo name].git`. `Origin` here is an alias for the remote dir.
- `git push origin [branch name]`

## Branching
- `git branch [branch name]`
- `git checkout [branch name]`
- `git push --set_upstream origin [branch name]` connects a local branch to a remote branch