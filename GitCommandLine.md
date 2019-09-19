git命令行
1、克隆master分支，如：git clone https://github.com/仓库作者/仓库名称.git

2、查看分支，本地分支（git branch -v）、全部分支（git branch -a）

3、创建分支，如：git branch develop

4、切换分支，如：git checkout develop

5、查看状态，如：git status

6、增加改动的文件，如：git add *

7、提交文件并附上日志，如：git commit -m "develop测试”

8、提交到远程仓库，如：git push origin develop:develop

9、删除本地分支，如：git branch -d dev

10、删除本地分支，如：git branch -r -d origin/dev 

11、删除远程分支，如：git push origin --delete dev

12、分支合并，如：dev-->master，先提交dev改动或增加文件，再git checkout master，接着git merge dev，最后git push origin master
