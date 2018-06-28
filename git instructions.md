## to push
```
  git checkout -b new-branch
  git add .
  git commit -m "This is a new commit"
  git push --set-upstream origin email-validation # need to tell which remote branch to use 
  git push 
```
see also: 
https://stackoverflow.com/questions/37770467/why-do-i-have-to-git-push-set-upstream-origin-branch


# to commit a single file 
git commit path/.../ -m "my notes"


## Clean Git
- `git log`
- `git diff`
- `git add -p`
- rebase:
  - `git rebase -i origin/master  # represents "interactive"`
  - `git push -f # force push `
  - `git rebase --abort # put everything back`
