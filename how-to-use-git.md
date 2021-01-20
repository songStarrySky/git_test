# how to use git&githup

###### 1 githup的使用
###### 2 下载git，并配置本地仓库
###### 3 git常用指令
###### 4 git常见错误

## 1 githup的使用
#### 1.1登录网址，注册账号
网址:https://github.com/
账号:songStarrySky
#### 1.2创建仓库，配置ssh
仓库:https://github.com/songStarrySky/git01.git
ssh<settings>:(B-gitRepo)

## 2 下载git，并配置本地仓库
#### 2.1下载安装git
#### 2.2创建本地目录文件，配置本地仓库,上传文件至githup
###### 2.2.0 建立ssh连接
ssh-keygen -t rsa -C "18298199852@163.com"
cat /Users/{用户名}/.ssh/id_rsa.pub

###### 2.2.1 在本地目录下创建文本，并对文本目录进行git bash here
index01.txt
查看版本
git --version

###### 2.2.2 配置GitHub上用户名、邮箱
git config --global user.name "songStarrySky"
git config --global user.email "18298199852@163.com"

###### 2.2.3 创建本地代码仓库,并将文本添加到仓库中
git init
git add .
git status
git add index01.txt
git commit -m "first commit"

###### 2.2.4 连接本地仓库和远程仓库，并提交文本
git remote add origin git@github.com:songStarrySky/git_test
git push origin master


## 3 git常用指令
https://www.runoob.com/git/git-basic-operations.html

## 4 git常见错误