Git is a distributed version control system
better than svn

git init 初始化
git add file 提交到暂存区
git commit -m "" 提交到工作区
git status 查询已修改未提交的变更
git diff file 查看文件修改内容
git log 查询提交历史记录
git reflog 查询执行命令历史记录
git reset --hard HEAD^/版本号 回退工作区到指定的版本
git checkout -- file 丢弃工作区的修改，回退到暂存区或版本库
git reset HEAD file 撤销暂存区的修改