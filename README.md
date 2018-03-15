
1. 建立本地仓库与远程仓库的连接配置：

git remote add origin git@github.com:purelegant/any.git

2. 将代码推送至远程仓库(现在没有进行分支配置，所以只有一个master分支)：

git push -u origin master

注意：这时候github仓库不要初始化

3. 如果修改了本地的文件，然后提交

git commit -a -m "Change Emp.java"

但是这一步并没有将服务器的代码更新

4. 将本地的代码与远程仓库进行合并

git push -u origin master




