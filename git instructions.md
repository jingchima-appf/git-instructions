## to push
```
  git checkout -b new-branch # this is to copy the content in current local branch to the 'new-branch'
  git add .
  git commit -m "This is a new commit"
  git push --set-upstream origin email-validation # need to tell which remote branch to use 
  git push 
```
see also: 
https://stackoverflow.com/questions/37770467/why-do-i-have-to-git-push-set-upstream-origin-branch

## to commit a single file 
git commit path/.../ -m "my notes"


## Clean Git
- `git log`
- `git diff`
- `git add -p`
- rebase:
  - `git rebase -i origin/master  # 'i' represents "interactive"`
  - `git push -f # force push `
  - `git rebase --abort # put everything back`
  
  
## clone only one branch
`git clone -b <branch> <remote_repo>`

## change parent branch
for current branch
git rebase --onto <new-parent> <old-parent>

see: https://stackoverflow.com/questions/3810348/setting-git-parent-pointer-to-a-different-parent

## Remove git tracking from a folder
`rm -r .git/`

## Move a branch back by several commits
git reset --hard HEAD~3

see: https://stackoverflow.com/questions/1628563/move-the-most-recent-commits-to-a-new-branch-with-git
