training
========

Git练习和代码审查


===========
将strivel加入管理


===========

### fetch命令

    $ git fetch <远程主机名>
    
更新远程主机的更新,默认取回所有分支（branch）的更新

    $ git fetch <远程主机名> <分支名>

取回特定分支更新,fecth并不进行更新，只是从远程获取更新到本地，所有取回的更新需要用

> "远程主机名/分支名"的形式读取
>  "git branch命令-r选项,可以用来查看远程分支,-a选项查看所有分支"


    $ git branch -r
    origin/master
    $ git branch -a
    * master
      remotes/origin/master
    

    

