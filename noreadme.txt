I add some words to the top!

Git：分布式版本控制系统
第一步：创建仓库，一般一个仓库就是一个工程，可以存放文件夹，图片等数据。
New repository--Repository name--Description-- Initialize this repository with a 

README.

第二步：创建一个分支，默认情况下有一个master分支

第三步：确认和提交修改

第四步：打开一个Pull请求

第五步：合并Pull请求



Git命令
//名字
$ git config --global user.name "Your Name"
//email地址
$ git config --global user.email "email@example.com"

//创建仓库
$ mkdir learngit
//初始化一个Git仓库，使用git init命令。
$ git init
//添加文件到Git仓库，分两步：
//创建一个readme.txt
$ vim readme.txt
//将文件添加到仓库
$ git add readme.txt
//使用命令git add <file>，注意，可反复多次使用，添加多个文件；
//使用命令git commit -m <message>，完成。
$ git commit -m "description"

//要随时掌握工作区的状态，使用git status命令。
$ git status
//如果git status告诉你有文件被修改过，用git diff可以查看修改内容。
$ git diff
//查看最近提交的日志，简化版的日志
$ git log
$ git log --pretty=oneline

//回退到上1个版本
$ git reset --hard HEAD^
//回退到上100个版本
$ git reset --hard HEAD~100
//回退到1094a这个版本
$ git reset --hard 1094a
//查看历史命令
$ git reflog

//工作区和暂存区，讲新增或者是修改的文件加入暂存区，提交之后暂存区为空










