# Getting started with git

1. Initialise the folder

```
git init
```

2. Add files to version control

```
git add .
```

3. Make a commit

```
git commit -am "Initial Commit"
```

4. Remove unwanted git files from version control

```
git rm test MakeFile *.o *.pro.user
```

-new commit
```
git commit -am "removed unwanted files"
```

5. .gitignore file, do a touch .gitignore, add to other files, whatever is inside of it will not be added to git
```
git commit -am "added ignore"
```
