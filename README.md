 Version Control Task
 1 - How To Remove 2 Branches Them Locally & Remotely ?
 ------------------------------------------------------
 Locally : 
 ---------
 git branch -d dev
 git branch -d test
 
 Remotely : 
 ----------
 git push origin --delete dev
 git push origin --delete test
 
 2 - How To Checkout Another Branch Without Commit Changes ?
 -----------------------------------------------------------
 git stash
 git checkout <branch-name>
 git stash pop

 3 - How to List Tags ? 
 -----------------------
  git tag

 4 - How To Delete Tag Locally & Remotely?
 ------------------------------------------
 Locally :
 ---------
 git tag -d v1.7

 Remotely :
 ----------
 git push origin --delete v1.7

