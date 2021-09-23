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

13、拉取远程指定分支，如：git clone -b develop 远程仓库地址（如：https://github.com/仓库作者/仓库名称.git）

14、列出tag，如：git tag

15、创建tag，如：git tag -a v1.0 -m "1.0的版本"（此处创建的是附注tag，轻量tag不做描述。参数a即annotated的缩写，指定Tag类型，后附Tag名。参数m指定Tag说明，说明信息会保存在Tag对象中。）

16、给指定的commit打tag，如：git tag -a v1.0 9fbc3d0 -m "1.0版本" （9fbv3d0 这个是git log可以到xcode sourceControl history 查看指定的commit的标识）

17、推送tag到服务器，如：git push origin v1.0  (若v1.0改成 -tags 是提交所有tag)另附著（1，切换到tag ： git checkout [tagname]  ；2，删除tag：git tag -d v1.0）
