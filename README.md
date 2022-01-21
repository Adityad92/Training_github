# Training_github
git init
git add README.md
git commit -m "first commit"
git branch -M prod
git remote add origin <repo url>
git push -u origin production
  
#Setting up other branches
git checkout -b UAT
git push
git push --set-upstream origin UAT
  
git chekout master
git checkout -b developer
git push
git push --set-upstream origin developer
