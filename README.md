# How to use git

Commands we're going to try today

git clone - copy the remote repository to your local  
git pull - check if there are remote changes and update your local   
git fetch - check if there are remote changes  
git checkout -b "feature/new-branch" - create a new local branch
git checkout "feature/existing-branch" - change to an existing branch   
git branch - list all your branches  
git status - show which file was modified  
git diff - show the changes for each line  
git reset --hard - revert the changes made locally  
git add -p - allow you to look at small chunks of code, and stage them one by one  
git restore --staged file-to-be-unstaged  
git commit -m "commit message" - commit your changes locally
git push --set-upstream origin branch-name - create your local branch remotely and push changes    
git push - update remote with your local changes

# How to rebase
git checkout master 
git pull (to update your local with the latest changes in master)
git checkout your_branch
git rebase master (check if there are any conflicts)
git push -f
