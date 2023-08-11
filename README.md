# first-repo
1、git init 初始化

2、git add .  将当前目录下修改的所有代码从工作区添加到暂存区
   git add 文件夹/.  提交整个文件

3、git commit -m  ['注释']  将缓存区内容添加到本地仓库

4、git remote add origin 仓库地址  将本地仓库与远程仓库连接起来
   git remote -v  查看当前仓库所对应的远程仓库的别名和地址
   
  git branch -M main  指定分支名称为 Main

5、git push -u origin master 将本地仓库的 origin分支 推送到远程仓库的 master分支 上
   git push -u origin master:main   全称：将本地分支的 master 推送到远程分支的 main上
