# git-branching

### How to create new branch
```shell
git branch <branch-name>
```

### How to list all branches
```shell
git branch --list
```

### How to switch branch
```shell
git checkout <branch-name>
```

### How to rename local branch
```shell
git branch -m <branch-name>
```

### How to delete branch
* local
    ```shell
    git branch -d <branch-name>
    ```
* remote
    ```shell
    git push <remote-name> --delete <branch-name>
    ```

### How to remove stale local branch (remove remote deleted branch from local)
```shell
git remote prune <remote-name>
```