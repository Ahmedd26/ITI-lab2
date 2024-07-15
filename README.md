# Q: Tell me how to remove them locally and remotely.

> To remove them locally:
> `git branch -d dev` > `git branch -d test`

> To remove them Remotely:
> `git push origin :dev` > `git push origin :test`

# Q: Tell me how to checkout another branch without commit changes.

> Use `git stash` to temporarily save changes, then use `git checkout master` to switch back to the main/master branch.

# Q: Tell me how to list tags.

> Use `git tag` to list tags.

# Q: Tell me how to delete tag locally and remotely.

> Locally, Use `git tag -d v1.7`
> Remotely, Use `git push origin --delete v1.7`

![Git Wallpaper](git.jpg)
