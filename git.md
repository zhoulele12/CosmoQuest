# Git and Github
`git log` shows the entire `HEAD` tree.
`git diff --cached` shows diff of staged files
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
- `fast-forward` happens when one branch is directly ahead of another. E.g. branch `master` is on commit3 and branch `hotfix` is on commit 4. To merge `hotfix` into `master`, we can just move the `HEAD` pointer of `master` forward.
- After conflict resolution, do `git add [file_name]` to mark completion of merge.

## Amend
- Modify the most recent commit.
- `git commit --amend` without any files staged would only modify the commit message.
- `git commit --amend --no-edit` combines staged file with last commit without chaning the commit message.

## Rebase
- Change the base of a branch from one commit to another
- The purpose is to create a linear project history
- `git rebase master` rebases the current branch to the `HEAD` of `master`

## Stash
- saves uncommitted changes in your working dir so that you can quickly switch task
- `git stash` to save, `git stash pop` to reapply changes

