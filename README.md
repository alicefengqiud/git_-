# git_-
git_指令


一、git与github

1、git的概述

①版本控制

就是一种记录文件内容的变化，以便将来查阅指定版本的代码的系统。

git就是当下最流行的 最好用的版本控制工具。
作用：
①防止代码的丢失
②
团队协作
③版本还原
遇到bug，直接将代码回滚到指定的版本



为什么选择Git？
①节省时间
②离线工作
③撤销错误
④可靠性比较高
⑤让提交更有意义
⑥避免混乱


github官网：https://github.com/
github 主要提供基于git的版本托管服务。
git是一款免费的开源的分布式版本控制工具。




二、git常用的命令
演示

mkdir test 创建test目录
cd test 进到test目录中 (change directory ==> cd)
touch a.md 去创建a.md的文件
(print the working directory ==> pwd打印当前目录)

git init 初始化代码仓库

配置用户名 邮箱
git config --global user.name 'web1606a'

git config --global user.email 'web1606a@vip.163.com'

git status 查看代码状态

git add a.md 将这个文件保存到缓存区
git commit -m '提交本次代码的改动信息'

git branch 查看分支
git branch dev 创建一个分支名字为dev的分支

git checkout dev切换到dev分支
 
git remote add origin https://github.com/zzlTedu/HelloGit.git 添加一个origin

git push orgin dev 通过push指令往origin的dev去推代码
