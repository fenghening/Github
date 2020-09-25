> **设置用户**
- 设置提交时使用的git用户，不是远程仓库用户  
git config --global user.name "xxx"  
git config --global user.email "xxx"  

- 查看设置  
git config --list

> **帮助**
- git help [command]

> **初始化仓库**
- git init  

> **添加到缓存区**
- 单文件添加
git add [file]...  
- 全部添加
git add -A

> **从缓存区中删除**
- git rm --cache [file]...  

> **提交到本地仓库**
- git commit -m "xxx"

> **添加暂存区并提交本地仓库**
- git commit -a -m "xxx" [file]...  

> **查看历史记录**
- git log  
- git reflog 
空格下一页，b上一页，q退出  

> **版本前进后退**
- git reset --hard [index]

- soft，mixed，hard参数的区别  
soft 仅改变本地仓库的HEAD  
mixed 改变本地仓库HEAD，并且清空暂存区  
hard 工作区，本地仓库HEAD都会改变，并且暂存区清空   
 
> **分支**
- 查看本地分支  
git branch

> **创建本地分支**

- git branch [branchName]

> **切换分支**
- git checkout [branchName]  

> **远程仓库**
- 添加远程仓库地址  
git remote add origin [url]
origin相当于别名，代表远程仓库

- 查看远程仓库地址
git remote -v

- 推送到远程仓库
git push origin [branchName]





