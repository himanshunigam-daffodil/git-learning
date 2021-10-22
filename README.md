# git-learning

### How to setup config
* Local
    ```shell
    git config user.name <User name>
    git config user.email <User email>
    ```

* Global
    ```shell
    git config --global user.name <User name>
    git config --global user.email <User email>
    ```

### Working status
```shell
git status
```
### How to Clone
```shell
git clone https://github.com/himanshunigam-daffodil/git-learning.git
```

### How to view remote list for repository
```shell
git remote
git remote --v
```

### How to add file/directory
```shell
git add branch.txt
git add branch/
```

### How to view difference
```shell
git diff <file-path>
```
### How to commit
```shell
git commit -a -m "Commit git branching commands"
```

### How to fetch remote changes
```shell
git fetch
```

### How to pull remote changes
* Pull from remote branch
```shell
git pull
```

* Pull from remote another branch
```shell
git pull <remote-name> <branch-name>
```

### How to push changes
```shell
git push <remote-name> <branch-name>
```

## How to revert the change on particular file
 git checkout --