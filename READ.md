To remove branches dev & test:
locally:
git branch -d branch_name

Remotely:
git push origin :branch_name
git push origin --delete branch_name

--------------------------------------------

To checkout another branch without commit changes:
 
use git stash -> to store all changes or branch