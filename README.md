# Q: Tell me how to remove them locally and remotely.

> To remove them locally:
> `git branch -d dev` > `git branch -d test`

> To remove them Remotely:
> `git push origin :dev` > `git push origin :test`

# Q: Tell me how to checkout another branch without commit changes.

> Use `git stash` to temporarily save changes, then use `git checkout master` to switch back to the main/master branch.
