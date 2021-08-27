1.git init
2.git remote add origin git@github.com:wxr777/Keil.git


上传
git add . -------------添加所有的文件到缓存区
git commit -m "备注" ------------将缓存区的所有改动都给提交到本地仓库管理中心去
git push -u origin master ----------将本地所有改动提交都推送到远程仓库
master是github远程仓库分支（master是默认的主干，自己就是一条分支）


拉取
git clone git@github.com:wxr777/Keil.git

git status ---------- 查看文件提交情况
git diff readme.txt----------- 查看文件更改情况
git log --pretty=oneline ----------参看版本历史记录
git reset --hard HEA^   ----------回退到上一个版本
git reflog ---------- 获取版本号
git checkout --readme.txt -------------把readme.txt文件在工作区做的修改全部撤销


查看分支：git branch

创建分支：git branch name

切换分支：git checkout name

创建+切换分支：git checkout –b name

合并某分支到当前分支：git merge name

删除分支：git branch –d name


