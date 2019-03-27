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
git remote add github git@github.com:dcdavia/leangit ##relate the repository to a remote repository
git push github master ##push the local repository to the remote repository
git pull github master ##pull the remote repository to local repository
git clone git@github.com:dcdavia/leangit
