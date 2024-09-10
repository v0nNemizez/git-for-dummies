# Configurations for remote repositories

Git can be configured to work with remote repositories in a variety of ways. 
When cloning a repository, the remote repository is automatically set as the **origin**.

An example of this is the `git checkout` command:
```bash
git checkout -b <branch_name> origin/<branch_name>
```
... or  `git push` command:
```bash
git push origin <branch_name>
```

For existing repositories, the remote repository can be set using the `git remote` command.
```bash
git remote add origin <url>
```


