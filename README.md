git log --pretty=format:"%h - %an, %ar : %s"

拉取主线分支覆盖当前分支：
git pull origin master --allow-unrelated-histories

推送
git push MyMaps GitHub/master:master

强制push:  
git push -u MyEffect master -f

添加远程url:  
git remote set-url --add origin git@github.com

查看远程配置：
git remote -v

移除远程地址
git remote rm origin

首先，先增加第一个地址 git remote add origin <url1>
然后增加第二个地址 git remote set-url --add origin <url2>
增加第三个地址 git remote set-url --add origin <url3>
