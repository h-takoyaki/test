# git order
## 基础

1. 配置个人信息

   ~~~shell
   $ git config --global user.name "Your Name"
   $ git config --global user.email "email@example.com"
   ~~~

2. 配置ssh

   [github官方教程](https://docs.github.com/cn/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

3. 常用命令

   ~~~shell
   # 拉取自己的仓库
   git pull
   
   # clone 自己的仓库
   git clone
   
   # 将本地的修改从工作区提交到暂存区stage
   git add .
   
   # 提交到github(远程仓库)
   git commit -m 'say something about this commit'
   
   # 查看当前的状态
   git status
   
   # 查看提交日志 --pretty=oneline 查看简单日志
   git log
   git log --pretty=oneline
   
   # 回退
   git reset --hard head^ 回退到上一个版本
   git reset --hard 版本号 指定回退到某一个版本
   # 这时候本地仓库落后于远程仓库，将本地仓库强制push
   git push -f
   # 如果是协同开发不要这么做
   [远程版本仓库退回](https://zhuanlan.zhihu.com/p/56843134)
   ~~~







## 参考

[廖雪峰git](https://www.liaoxuefeng.com/wiki/896043488029600/900003767775424)

[机器之心](https://zhuanlan.zhihu.com/p/132573100)

[git命令总结](https://zhuanlan.zhihu.com/p/25892137)

[github + vscode](https://www.bilibili.com/video/BV1dK411p7RF?from=search&seid=8066546361897202470&spm_id_from=333.337.0.0)

[git](https://git-scm.com/book/zh/v2)

[远程版本仓库退回](https://zhuanlan.zhihu.com/p/56843134)
