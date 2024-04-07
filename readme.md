# Git course short summary

## Main commands in bash to create and initiate repo, commit and push files to remote repo 

1. cd ~/dev/first-project # go to project dir

2. git init # create local repo

3. rm -rf .git # delete repo recursively force

4. git status # repo state

5. git add --all # prepare to save all files

6. git commit -m 'Commit message' # commit to local repo

7. git log # show commit history

   7.1. git log --oneline # show short commits story

8. git remote add origin HERE URL SSH OR HTTP OF REMOTE

9. git push -u origin master

### HEAD 
 __HEAD__ is a file in .git with link to last commit
 this link contains last commit hash summ sha 
 Each commint has a unique hash summ 

### File statuses

```mermaid
%% Untracked
```


