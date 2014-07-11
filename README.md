training
========

测试~~~~~~

### 更新远程仓库到本地文件夹
    $ git clone https://github.com/strivek/training.git
### 查看远程库
查看全部远程仓库名称
    $ git remote
查看远程仓库地址
    $ git remote -v 
    
===========

### 从远程数据库获取数据

#### fetch 命令
*fecth只是将远程库的书库下载到本地仓库，并不会自动合并到当前的分支，需要手工合并*
    
    $ git fetch <远程主机名>
    
更新远程主机的更新,默认取回所有分支（branch）的更新

    $ git fetch <远程主机名> <分支名>

取回指定分支的更新,fecth并不进行更新，只是从远程获取更新到本地，所有取回的更新需要用

> "远程主机名/分支名"的形式读取
>  "git branch命令-r选项,可以用来查看远程分支,-a选项查看所有分支"


    $ git branch -r
    origin/master
    $ git branch -a
    * master
      remotes/origin/master
      
#### pull 命令

获取并且合并到当前工作分支
ks
    $ git pull origin master
    

### 正常工作流

	$ git add  file1 file2 file3
更新列举出的文件更改

	$ git add  .
更新全部文件夹下文件的更改



#### 查看更改

	$ git diff -cached
查看已经存到缓存区内的更改（已经add）
	
	$ git diff 
查看尚未存到缓存区内的更改 (尚未add)

	$ git commit -a
自动将所有被修改内容的文件（不包括新建的文件夹）都添加到索引中，并且同时把他们提交。


#### 分支操作

	$ git branch exp
新建分支exp

	$ git branch

	* master
	  exp

查看本地分支，分支前星号表示为当前所在分支

	$ git checkout [分支名]
切换分支，在本分支有未处理的

