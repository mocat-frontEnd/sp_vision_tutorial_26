# 2026 赛季 RM 视觉组第一节培训

# Lesson1 Hello Ubuntu & git 教程

## 第一步 Ubuntu 上手教程

- 使用 ubuntu22.04 版本，这是小电脑的操作系统 也是业内最常用的操作系统。

- Terminal 终端(快捷键 Ctrl + Alt + T )

  - 用于输入命令，直接与系统核心进行交互
  - 终端命令灵活高效，支持自动化和远程操作（SSH 远程连接）

## 如何使用 Ubuntu

### Terminal 终端(使用更便捷，功能更强大)

- 之后训练一些 YOLO 的神经网络模型，去识别一个图案或者是一个装甲板
  - 例子：批量重命名 为所有图片添加 image\_前缀

```
- 图形化界面：逐个修改添加
- 终端：rename's/^/image_/'*.png
```

- 路径 例：~/Desktop/ap_vison_25

  - pwd 查看当前路径(print working directory)
  - cd 切换工作目录(change directory)
  - ls 列出当前工作目录下的内容
  - ls -a 列出当前工作目录下的所有内容，包括隐藏文件
  - mkdir 创建文件夹(make directory)
  - rm 删除文件(remove)
  - rm -r 删除文件夹 -r 表示递归删除
  - rmdir 删除空文件夹(remove directory)
  - cp 复制文件或文件夹(copy)
  - mv 移动文件或文件夹(move)
  - touch 创建空文件(touch)
  - sudo 管理员权限(super user do)
  - ctrl + r 搜索历史命令
  - ctrl + z 暂停程序
  - ctrl + c 强制终止程序
  - ctrl + l 清屏

- apt 先进包管理器(advanced packaging tool)

  - sudo apt update 只检查不更新
  - sudo apt upgrade 检查并更新
  - sudo apt install 下载并安装远程/本地软件
  - sudo apt purge 卸载软件并移除配置文件

## 第一步 Git、GitHub 和 Gitee 讲解

### Git 它是一个分布式管理系统

打开 vscode，跳转官网安装对应版本的 git。下载好之后进行查看版本。

- 安装
  - sudo apt install git

# 前⾔

Git 官网:

https://git-scm.com/install/windows

Sourcetree 官网:

https://www.sourcetreeapp.com/

github:

https://github.com/

gitee:

https://gitee.com/

```
终端中输入 git --version 查看版本号
cls 清屏
```

之后 vscode 打开文件夹，先点击初始化仓库，对应命令为

```
git init
```

添加文件到暂存区

```
git add .
```

提交文件到本地仓库

```
git commit -m "提交信息"
```

推送代码到远程仓库

```
git push origin 分支名
```

克隆远程仓库

```
git clone 仓库地址
```

拉取代码(从远程仓库拉取最新代码到本地仓库)

```
git pull origin 分支名
```

## 第二步

初始化配置用户名和邮箱

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

```
shashen
sunbo13704426091@outlook.com
```

## Git 常⽤命令及 SSH 配置

⽣成 SSH 密钥

```
ssh-keygen -t rsa -C "你的邮箱"

```

### 测试连接

测试 GitHub：

```
ssh -T git@github.com

```

测试 Gitee：

```
ssh -T git@gitee.com
```

## 第三步

清屏

```
clear
```

初始化一个仓库本地

```
git init
```

查看 git 仓库当前状态

```
git status
```

在本地服务器上查看存档日志时间

```
git log
```

查看当前分支

```
git branch
```

切换分支

```
git checkout 分支名
```

创建分支

```
git branch 分支名
```

合并分支

```
git merge 分支名
```

删除分支

```
git branch -d 分支名
```

版本回滚/分支合并（之后要学习的）

```

```

## 第四步

学习同济大学
