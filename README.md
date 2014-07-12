#工作规范与参考文档
==================

##Git 日常工作流程

1. 项目开始
2. folk项目到自己github仓库
3. 建立自己的本地分支，进行开发
4. 每完成一部分内容后，commit到远程自己的仓库，
5. 每日工作完成后，pull request到共享主仓库
6. 每日注意查收邮件解决pull request 后，code review后提出的问题
7. issues 中提到的问题，如分派给自己完成，需认真完成，直至问题close


##Git 常用命令
    git clone [远程库地址]

克隆远程库到本地



    git remote 
    git remote -v

`remote` 查看现有远程库有哪些，
日常工作,一个是共享远程库，用来`pull`，一个自己folk的远程库，用来推送`pull request`

`remote -v` 可以查看更详细的远程库信息，包含了其库所在的URL
