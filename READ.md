To remove branches:
locally:
git branch -d branch_name

Remotely:
git push origin :branch_name
git push origin --delete branch_name

--------------------------------------------

To checkout another branch without commit changes:
 
use git stash -> to store all changes or branch

--------------------------------------------
To list tags:
git tag

--------------------------------------------
To remove Tags:
locally:
git tag -d tag_name

Remotely:
git push origin :tag_name
git push origin --delete tag_name