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
