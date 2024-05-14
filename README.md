# steps to work on Git

1. Git clone  [note:only use the git clone command when you are downloading the git repo first] (git clone git@git.Aramyd.git)
2. cd into the downloaded git folder, so you can work in the directory
3. make your changes to a file, or add a new file, or delete
4. git status to check [NB: the files changed will be in red colour] (git status)
5. use `git add <name of the file> to add the modified file (`git add index.html`)
6. git status 
7. use git commit to add a message (`git commit -m "write the message here"`)
8. use git push to push to git repo server (`git push`)

```
example
cd devops
edit text.txt
git status
git add text.txt
git status
git commit -m "update to text,txt file"
git status
git push
```
### To work on a new branch

1. git branch to check the branch you working in (`git branch`)
2. if on main branch (main will be green with * ) use git pull to sync your local with main (`git pull`)
3. use git branch <branch name> to create a new branch (`git branch 80/my-branch-name`)
4. use git checkout <branch name> to change to the new branch (`git checkout 80/my-branch-name`)
5. start working on the files, or add a new file to work on 
6. once you are done working follow the git push procedure
Joseph Akinola
4:32 AM
6. once you are done working follow the git push procedure (`git add , git status, git commit, git push`) NB, the push will be different using upstream from the suggestion

### To work on Existing branches
1. git branch to check the branch you working in (`git branch`)
2. if not on main use `git checkout main` to checkout to main
3. `git pull ` to pull latest 
4. use git checkout <branch name> to change to the branch (`git checkout 80/my-branch-name`)
5. start working on the files, or add a new file to work on 
6. once you are done working follow the git push procedure (`git add , git status, git commit, git push`)
 Refreshing my brain with git
