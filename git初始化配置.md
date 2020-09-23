###设置用户
设置提交时使用的git用户，不是远程仓库用户  
git config --global user.name "xxx"  
git config --global user.email "xxx"  
查看设置  
git config --list

###初始化仓库
git init  

###添加到缓存区
git add <file>...

###从缓存区中删除
git rm --cache <file>...

###提交到本地仓库
git commit -m "xxx" <file>...

###查看历史记录
git log  
空格下一页，b上一页，q退出  

带HEAD   
git reflog 






