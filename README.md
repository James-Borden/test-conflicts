# test-conflicts

> 这是我第一次写Markdown文件 



## 记录一下学习过程 



### 1、 安装和配置

```shell
对所有本地仓库的用户信息进行配置

对你的commit操作设置关联的用户名
$ git config --global user.name "name"

对你的commit操作设置关联的邮箱地址
$ git config --global user.email "email address"

启用有帮助的彩色命令行输出
$ git config --global color.ui auto
```



### 2、 创建仓库

```shell
当着手于一个新的仓库时，你只需创建一次。要么在本地创建，然后推送到 GitHub；要么通过 clone 一个现有仓库。

# 进入仓库，初始化
$ git init

# 创建仓库并初始化
$ git init test

在使用过 git init 命令后，使用以下命令将本地仓库与一个 GitHub 上的空仓库连接起来：
$ git remote add origin [url]

Clone（下载）一个已存在于 GitHub 上的仓库，包括所有的文件、分支和提交(commits)
$ git clone [url]
```



### 3、基本用法

```shell




```

### 4、三种状态

```shell
modified

staged 

commited
```

### 5、标签tag

```shell
git tag -a 标签名 -m 备注
```

### 6、分支branch

```shell
分支是使用 Git 工作的一个重要部分。你做的任何提交都会发生在当前“checked out”到的分支上。使用 git status 查看那是哪个分支。

创建一个新分支
$ git branch [branch-name]

创建，并切换到指定分支
$ git switch -c [branch-name]

将指定分支的历史合并到当前分支。这通常在拉取请求(PR)中完成，但也是一个重要的 Git 操作。
$ git merge [branch]

删除指定分支
$ git branch -d [branch-name]
```

### 7、合并分支

```shell
```

### 8、远程仓库

```shell
```

### 9、多人远程合作

```shell
```