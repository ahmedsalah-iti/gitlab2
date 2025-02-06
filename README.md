- how to remove local branch :
git branch -d dev
git branch -d test
- how to remove the branch remotly
git push origin :dev or git push origin --delete dev
git push origin :test or git push origin --delete test

- how to checkout another branch without commit changes : 
  by using git stash then we can checkout to another branch because it's saving the changes without commiting .
  
- how to list tags :
git tag

- how to delete tag locally :
git tag -d v1.1

- how to delete tag remotley :
git push origin --delete v1.1 or git push origin :v1.1

![hey](bye.jpg)
