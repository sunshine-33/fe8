step1:
    创建一个空文件夹
    git init
    git status 查看git的文件状态
    //git remote rm origin 删除远程 Git 仓库
    git add . 把本地的文件添加到本地仓库
    git commit -am"init" 提交到本地仓库
    git remote add origin https://github.com/sunshine-33/fe8.git 给本地的仓库添加远程地址
    git push origin master

在本地配置ssh密钥
ssh-keygen -t rsa -C "594859064@qq.com"
cd ~ 切换家目录
cd .ssh
cat id_rsa.pub

把这个公钥复制到github页面

git命令
git checkout -b sunshine 创建分支
git checkout master

git branch 把所有分支列出来
git branch sunshine 创建分支
git checkout -b sunshine 创建并且切换到分支 相当于git branch sunshine + git checkout sunshine

想知道自己在这个分支上做了哪些动作
git status
git diff 查看自己修改了哪些东西
执行完这个命令之后，类似于vim模式
怎么退出？
:q!
shift zz 就是大写的ZZ