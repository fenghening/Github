#设置用户
设置提交时使用的git用户，不是远程仓库用户  
git config --global user.name "xxx"  
git config --global user.email "xxx"  
查看设置  
git config --list

#帮助
git help [command]

#初始化仓库
git init  

#添加到缓存区
git add [file]...  
git add -A

#从缓存区中删除
git rm --cache [file]...  

#提交到本地仓库
git commit -m "xxx" [file]...  
git commit -a -m "xxx" [file]...  

#查看历史记录
git log  
空格下一页，b上一页，q退出  

带HEAD   
git reflog 

#版本前进后退
git reset --hard [index]
##soft，mixed，hard参数的区别  
soft 仅改变本地仓库的HEAD  
mixed 改变本地仓库HEAD，并且清空暂存区  
hard 工作区，本地仓库HEAD都会改变，并且暂存区清空   
 





