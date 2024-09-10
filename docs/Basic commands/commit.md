# Commit

Syntax: `git commit -m "message"`

Commit is a command that is used to save changes to the local repository. It is a snapshot of the project at a particular point in time. 
It is a good practice to commit changes to the repository frequently. This helps in keeping track of the changes made to the project 
and allows you to revert to a previous state if needed.

Committing changes involves two steps:
1. **Staging**: This step involves selecting the changes that you want to commit. You can stage changes using the `git add` command.
2. **Committing**: This step involves creating a commit with the staged changes. You can commit changes using the `git commit` command.

**Message**: It is a good practice to add a meaningful message to your commit. This helps in understanding the changes made in the commit.

**Example**: Suppose you have made changes to a file `index.html` and want to commit these changes. You can do this by running:

```bash
git add index.html
git commit -m "Updated index.html"
```