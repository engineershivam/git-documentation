# How to check changes or diffrences
``` php
git diff file_name_with path
```

# How to go back on previous commit

We have two option to go back on the  specific commit
- Go back on the specific commit and commit as a new commit
- Go back on specific commit and remove the after commits

## Go back on the specific commit and commit as a new commit

### Steps
- Get the commit ID 

``` php
git log
```
OR
``` php
git log --oneline
```
- Checkout on commit id & apply changes
``` php
git checkout commit_id -- .
```
- Commit as a new commit
``` php
git commit -m "msg"
```
## Go back on specific commit and remove the after commits
``` php
git reset --hard commit_id
```

# How to go back on previous commit and back to the current commit

If you want to go back on the specific commit for test and back to the original state
``` php
git checkout commit_id
git checkout branch_name
```
If you want to know branch name
``` php
git branch
```

