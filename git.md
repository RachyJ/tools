# Git commands

[Basic Git commands - Atlassian Documentation](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)

tell git who you are 

```
git config --global user.name "Sam Smith"
git config --global user.email sam@example.com
```

Connect to a remote repository

```
git remote add origin <server>
```

List the files you've changed and those you still need to add or commit:

```
git status
```

Add files 

```
git add <filename>

git add *
```

Fetch and merge changes on the remote server to your working directory:

```
git pull
```

force your local revision to the remote repo

```
git push -f <remote> <branch>
git push -f origin master
```