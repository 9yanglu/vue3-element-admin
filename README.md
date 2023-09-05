### 解决 error: src refspec main does not match any error: failed to push some refs to [url]问题

`git branch
git push origin main:master
git remote re origin 
git remote add origin [url]
git init
git add .
git commit -m 'xxx'
git push origin main:master
git pull origin master:main
git pull origin master`
