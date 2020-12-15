# kuikuiI-m


## 向仓库中添加文件流程(本地操作)

工作区 ——————>暂存区————————>Git仓库

git stats     当前状况(learning:两个空格换行)  
git add test.php/hello.php

git commit -m 提交描述  
git status

git status    

## Git初始化  
git config --global user.name 'dhkdhk'设置用户名  
git config --global user.eamil '1336442150@qq.com'      
提交文件  
1、 
git init 生成 .git隐藏文件  
2、添加到暂存区  
git stats     当前状况  
git add test.php/hello.php  
3、从暂存区添加到仓库  
git commit -m  ‘test.php/hello.php’  
git commit -m  ‘第一次提交’  


删除文件  
1、  
rm -rf test.php/hello.php  
2、   
git rm test.php/hello.php    
3、  
git commit -m '第一次删除'  





## 使用远程仓库   （远程操作）  

Git克隆：将远程仓库复制到本地  
git clone 仓库地址（复制）

1、创建新文件  
vim new.md  
2、加入暂存区    
git add new.md    
3、从暂存区添加到仓库  
git commit -m  “第一次git提交”  
4、将本次仓库提交到远程仓库  
git push  
  










