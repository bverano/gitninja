# Git Course

## Commands:

Creates a git repository:

> git init

Shows the repository state:

> git status

Stage files:

> git add \<filename\>\
> git add . (stage all unfollowed files )

Commit files:

> git commit -m "some message"

Show all commits of the repository:

> git log\
> git log --oneline (minified list)

Check te code of an specific commit:

> git checkout \<commitID\>

Revert the changes of one commit:

> git revert \<commitID\>

Delete all commit after one selected commit:

> git reset \<commitID\> (delete commits, but not the code)\
> git reset \<commitID\> --hard (delete commits and the code)

Create a branch:

> git branch \<branchName\>

List all branches:

> git branch -a

Change current branch:

> git checkout \<branchName\>

Delete a branch:

> git branch -d \<branchName\> (delete after merging the branch)\
> git branch -D \<branchName\> (delete without merging the branch)

Create and checkout a brand new branch:

> git checkout -b \<branchName\>

Merge branches to the master one:

> git merge \<branchName\>

What to do if there's a merge conflict?

1. Edit the file where the conflict is
2. Stage the changes
3. Commit the changes without a message

How to use Github?

1. Set an alias for the Github Repository URL

   > git remote add \<aliasName\> \<GithubURL\>

2. Push the repository to Github
   > git push \<aliasName\> \<branchName\>
