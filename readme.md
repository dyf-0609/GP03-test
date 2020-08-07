# readme

1. 一般会随着项目放在一起
2. 作为项目说明文档

## git init
1. 把当前目录初始化为版本库
2. 当前目录下会生成一个隐藏文件.git

## git add 文件名
1. 把当前目录下的某个文件提交到暂存区
2. git add readme.md 把这个文件提交到暂存区
3. git.add . 当前目录所有变动提交到暂存区

## git status 
1. 查看当前目录状态（新增、删除、修改）

## git commit -m '提交注释'
1. 把暂存区的内容提交到本地仓库

## 本地仓库涉及到的三个组成部分
1. 工作区（实际持有文件）
2. 暂存区
3. 本地仓库

## git log
1. 查看操作日志

## git reflog
1.查看操作日志（简单版）

## git diff 文件名
1. 查看文件变更信息

## git reset --hard 版本号
1. 版本回退 HEAD^回退到上一个版本
2. 回退到指定版本

## 主要的几个操作
1. git init -> 创建版本库
2. git add 文件名 -> 工作区提交到暂存区
3. git commit -m '注释' -> 暂存区提交到本地仓库

# 远程仓库

## git remote add origin 仓库地址
1. 把本地仓库与远程仓库关联

## git remote -v 
1. 查看本地仓库关联的远程仓库地址

## git push -u origin master
1. git push 本地仓库提交到远程仓库
2. -u origin master 设置默认的远程仓库和分支(u -> upstream)
3. 执行完这个命令之后，以后可以直接`git push`提交到远程仓库的master分支

## 更新代码
1. 把远程代码更新到本地时，一定要养成先提交本地代码再更新的习惯！
2. git pull 把远程代码拉取到本地
3. git clone 把远程克隆到本地

## git branch
1. 查看分支
2. 当前分支前面有*

## git branch 分支名
1. 创建分支

## git checkout 分支名
1. 切换分支

## git merge 分支名
1. 合并分支