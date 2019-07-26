# Git Tutorial

## 1. 安装Git

[https://git-scm.com/downloads](https://git-scm.com/downloads)

安装完成后，点击`Git Bash`打开。同时设置用户名和邮箱。

```
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

**注意`git config`命令的`--global`参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。**



## 2. 创建版本库

初始化一个Git仓库，使用`git init`命令。

添加文件到Git仓库，分两步：

1. 使用命令`git add <file>`，注意，可反复多次使用，添加多个文件；
2. 使用命令`git commit -m <message>`，完成。



## 3. 时光机穿梭

- 要随时掌握工作区的状态，使用`git status`命令。

- 如果`git status`告诉你有文件被修改过，用`git diff`可以查看修改内容。



### 3.1 版本回退

