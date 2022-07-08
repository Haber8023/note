# git入门

https://git-scm.com/

## 一、版本控制工具

集中式：CVS、SVN、VSS

分布式：Git

workspace  -add->  暂存区  -push-> 本地库  -->远程库

## 二、代码托管中心（远程库）

局域网：Gitlab

互联网：GitHub、Gitee

## 三、Git常用命令

git config --global user.name +用户名

git config --global user.email +邮箱

git init  初始化本地库

git status  查看本地库

git add +文件  添加到暂存区

git rm --cache +文件  删除暂存区文件

git commit -m "版本日志信息" +文件  提交本地库

git reflog  查看精简版本信息

git log  查看详细版本日志

git reset --hard +七位版本号  切换版本

## 四、Git分支的操作

git branch -v  查看分支

git branch +分支名  创建分支

git checkout +分支名  切换分支

git merge +分支名  合并分支到当前分支

## 五、Git远程仓库操作

 git remote -v  查看当前所有远程仓库地址别名

git remote add +别名 +远程地址  创建远程仓库地址别名

git push +别名/仓库地址 +分支名  推送到远程仓库

git pull +别名/仓库地址 +分支名  拉取到本地和本地仓库

git clone +别名/仓库地址 克隆远程仓库到本地











