## Create

- `git init` : Create a new local repository
- `git clone` : Clone a repository into a new directory

## Make a change

- `git add <Filel>` : Add file to staging area
- `git commit -m "Message"` : Commit changes to head
- `git reset <File>` : Unstage a file while retaining the changes in working directory
- `git reset --hard` : Discard all history and changes back to the specified commit

## Observes changes

- `git status` : List the files you've changed and those you still need to add or commit
- `git diff` : Show the differences between the working directory and the index
- `git diff --staged` : Show the differences between the index and the latest commit
- `git log` : Show the commit history
- `git show` : Show the changes in the commit

## Sync changes

- `git fetch` : Fetch changes from remote repository
- `git pull` : Fetch changes from remote repository and merge with local branch
- `git push` : Push changes to remote repository
- `git remote add origin <URL>` : Add a remote repository
- `git remote -v` : List remote repositories

## Branches

- `git branch` : List branches
- `git branch <Branch>` : Create a new branch
- `git checkout <Branch>` : Switch to a branch
- `git merge <Branch>` : Merge a branch into the active branch
- `git branch -d <Branch>` : Delete a branch
- `git push origin --delete <Branch>` : Delete a remote branch
- `git tag <Tag>` : Create a tag
- `git tag -a <Tag> -m "Message"` : Create an annotated tag
- `git tag` : List tags
- `git push origin <Tag>` : Push a tag
- `git push origin --tags` : Push all tags
