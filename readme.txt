<<<<<<< HEAD
Git is a distribute version control system.
Git is a free software under the GPL.
Git has a mutable index called stage.

git add ##add a file to stage
git commit -m "" ##commit all changes of stage to repository
git status ##show status of working directory
git diff ##show diffrence between working directory and stage
git log ##show log of commit
git reflog ##show future log of commit
git reset --hard HEAD^ ##reset working directory and stage from repositry, you can set the version
git reset HEAD ##reset stage from repository
git checkout -- file ##reset working directory from stage
git checkout ##switch to another branches
=======
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
>>>>>>> b2309ad6f32edb9087a9b43ae6dab71daf8ae651
