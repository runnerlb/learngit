git config --global user.name ''
git config --global user.email ''
mkdir learngit 创建一个目录
pwd  显示当前目录
git init 
git add filename
git commit -m '备注'
git status
git diff
git log
git log --pretty=oneline
git reset --hard HEAD^ 回到上一个版本
cat readme.txt 显示该文件的内容
git reset --hard guid 回滚到指定的版本
git reflog 查看操作版本
git diff HEAD -- readme.txt 可以查看工作区和版本库里面最新版本的区别
git checkout -- readme.txt  把readme.txt文件在工作区的修改全部撤销，这里有两种情况：
git rm file path 删除文件
ssh-keygen -t rsa -C 'lbrunner@163.com' 生成SSH
git remote add origin git@github.com:runnerlb/learngit.git 与远程建立连接
git push origin master 将代码提交到master
git clone git@github.com:runnerlb/gitskills.git  将代码复制到本地
git branch 查看分支
git branch  name创建分支
git checkout name 切换分支
git checkout -b name 创建并切换分支
git merge name 合并某分支到当前分支
git branch -d name 删除分支
http://www.07net01.com/2015/09/922578.html
http://markdownpad.com/download/awesomium_v1.6.6_sdk_win.exe




