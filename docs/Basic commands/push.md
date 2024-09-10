# Push

syntax: `git push [remote] [branch]`

## What?
`git push` is used to push the changes made in the local repository to the remote repository.

## How?
To push changes to the remote repository, you need to specify the remote repository and the branch you want to push to.

**Example**: Suppose you have made changes to the `somechanges` branch and want to push them to the remote repository. You can do this by running:
```bash
git push origin somechanges
```

## A word of caution
![nomaster](../img/nomaster.webp)

In lager projects, things might break if you push directly to the `master` branch. So, it is always a good practice to create a new branch and push your changes to that branch.

