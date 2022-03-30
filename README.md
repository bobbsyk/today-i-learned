# today-i-learned
git init
tree - apt install tree (Ubuntu)
git add
git commit -c "message"
git log

# https://learngitbranching.js.org

#branching
git branch <name-of-the-branch>
git checkout -b <name-of-the-branch>

#merging
git checkout -b bugFix
git commit
git checkout main
git commit
git merge bugFix
  
#rebase
git rebase main
git checkout main
git rebase bugFix

  30.03.2022
  https://dillinger.io
  
  1. Command line essentials
  2. Using source control in VS Code
    a. Commiting

