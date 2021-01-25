# readme文档
- 项目说明文档
- 一般于项目放在一起

# git操作

## 初始化版本库
-git init
-初始化成功后当前目录后有（master）
-初始化成功后有个隐藏文件.git 不用管他


## 工作区
- 持有实际文件
- 我们平时增删改查的文件都是工作区的内容


## 提交到暂存区
- 可以理解为我们看不到的地方
- 本地仓库的一个主要组成部分

## 本地仓库
- 可以理解为我们看不到的地方
- 也是存在于用户电脑中的
- 用于存储项目代码及版本相关记录等信息

## 提交到暂存区
- git add 文件名
- 将工作区的变动提交到暂存区
- git add . 将所有变动提交到暂存区

## 提交到本地仓库
- git commit - m "提交注"
- 我改一下试试

## 查看日志
- git log
- git reflog

## 版本回退
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard 版本号

## 修改变动


## 创建远程仓库
- 进入github官网
  我随便改一下  看看成功没

## 确保自己修改的代码先提交到远程仓库
- 然后再从远程修改到本地
  这是我在本地修改的