# Git commands

[Basic Git commands - Atlassian Documentation](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)

[常用 Git 命令清单 - 阮一峰的网络日志](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)

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

git add .
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

## How to review a file

1. Create a branch and check it out

```
$ git checkout -b newBranchName
```
2. Make the updates on the branch

3. Commit the changes to the branch 

4. Under your repository name, click "Compare & Pull request" to view the edits

5. Merge the branch to major when ready

* [GitHub flow - User Documentation](https://help.github.com/articles/github-flow/)
* [Git - Basic Branching and Merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
* [Commenting on a pull request - User Documentation](https://help.github.com/articles/commenting-on-a-pull-request/)