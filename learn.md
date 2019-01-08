1. git每次都要输入密码问题：
git目录下输入以下命令，输入一次账号密码后，后面就不需要输入了
git config --global credential.helper store

2. 分支创建
查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
