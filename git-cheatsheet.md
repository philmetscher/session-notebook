### Cloning a remote repository

```
git clone <url>
```

<br>

### check git status (untracked, tracked, staged)

```
git status
```

<br>

### Add a file to the stage

```
git add <filename>
```

<br>

### Create a commit including all staged files

```
git commit -m "Commit message"
```

<br>

### Connecting your local repository to a new remote repository

```
git remote add origin git@github.com:GitHubUsername/repository-name.git
git branch -M main
git push -u origin main
```

<br>

### Upload content to the remote repository

```
git push
```

<br>

### Download content from the remote repository

```
git pull
```

<br>

### Create new branch

```
git branch BRANCHNAME
```

<br>

### Delete branch

```
git branch -d BRANCHNAME
```

<br>

### Show the commit history

```
git log --oneline
```

<br>

### You can always return to the last committed state of the entire project

```
git restore .
```

<br>

### You can always return to the last committed state of the entire project

```
git restore <file name>
```
