#####  git 小技巧

> 1.git如何删除缓存的远程分支列表

    git remote prune origin 或 git fetch -p
    

> 2.删除开发分支（本地+远程）

	git branch -ｒ
	git branch -r -d origin/branch-name  
	git push origin :branch-name 
	git push origin --delete <branchName>
	git remote prune origin

>3.git 修改提交的用户名和邮箱
 
      git config --list   查看git的配置信息

      git config user.name 你的目标用户名;
      git config user.email 你的目标邮箱名;
      
        如果你要修改当前全局的用户名和邮箱时，需要在上面的两条命令中添加一个参数，--global，代表的是全局。
        git config  --global user.name 你的目标用户名；
        git config  --global user.email 你的目标邮箱名;
        当然，你还可以直接修改git的配置文件的方式来进行修改。
        打开全局的.gitconfig文件的命令为：vi ~/.gitconfig; 然后在文件中直接修改即可.
        打开当前project 中的config文件，该文件在每个project中的.git目录下，直接进入该目录进行编辑即可。当然，如果没有进行过修改的话，默认打开时没有对应的用户名和密码的。只有进行过修改之后，才会在config中产生对应字段。


>4.缓存账号密码
git config --global credential.helper store
    