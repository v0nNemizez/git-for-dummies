# Add

syntax: git add file/folder

## What?
git add adds changes in the working directory to the staging area. It tells Git that you want to include updates to a particular file in the next commit.

## How?

suppose you have a project tree looking like this:

```bash
├── LICENSE
├── README.md
├── docs
│   ├── Commands
│   │   ├── add.md
│   │   ├── clone.md
│   │   └── pull.md
│   └── index.md
├── mkdocs.yml


```

You have made changes to the file `add.md` and want to add it to the staging area. You can do this by running:

```bash
git add docs/Commands/add.md
```
To add all changes in the folder `Commands` you can run:

```bash
git add docs/Commands
```