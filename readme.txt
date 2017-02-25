this is my first file。哈哈111
哈哈，hehe
22
git init 将目录初始化成为git管理的目录。即成功git仓库
git add xxx.xx (例如：git add liudong.txt) 将文件添加到git管理
git add . 将当前目录所有文件增加到git管理
git commit -m "我今天提交了第一个git文件" 增加注释
git status 查看当前git库中的变化状态，能看到所有受管理的文件变化列表
git diff liudong.txt 能看看具体修改了什么内容
xiexie

git init 将目录初始化成为git管理的目录。即成功git仓库
git add xxx.xx (例如：git add liudong.txt) 将文件添加到git管理
git add . 将当前目录所有文件增加到git管理
git commit -m "我今天提交了第一个git文件" 增加注释
git status 查看当前git库中的变化状态，能看到所有受管理的文件变化列表
git diff liudong.txt 能看看具体修改了什么内容
git log 查看日志
git log --pretty=oneline 行显示日志
git reset --hard HEAD^ 回退至上个版本
git reset --hard HEAD~100 回退至前100个版本
git reset --hard oiqwerqwkejroq123123412 回退至指定的commit ID版本
git reflog 命令日志
git checkout -- liudong.txt 在工作区的修改撤销
git reset HEAD liudong.txt 可以把暂存区的修改撤销掉。当我们用HEAD时，表示最新的版本。
git add -f App.class	强制增加一个文件到git管理

ssh-keygen -t rsa -C "jiahuihb@126.com"	创建Key，用于github
git push -u origin master	（第一次）把本地库的内容推送到远程
git push origin master	把本地master分支的最新修改推送至GitHub
git clone https://github.com/jiahuei2cs/test.git	克隆github上面的项目到本地
git checkout -b dev	创建新的分支，并把指针指向新的分支
git checkout master	将指针指向主分支master
git branch	查看git的分支情况，并查看指针指向哪个分支
git	merge dev	将指定分支合并到现在的分支上(快速合并)
git branch -d dev	删除指定分支
git merge --no-ff -m "我在合并分支" dev 普通模式合并,可以看到详细合并内容
git push origin dev	从本地推送分支到github
git checkout -b dev origin/dev	在本地创建和远程分支对应的分支
git branch --set-upstream dev origin/dev	建立本地分支和远程分支的关联
git pull	从远程抓取分支

git tag v1.0	给当前分支打标签
git tag v0.9 6224937	给当前分支打标签，是将历史提交的commitid 作为打标签的指针
git tag -d v0.9	删除指定标签
git push origin v1.0	提交某个标签到远程库
git push origin --tags	将本地的标签，全部推送到远程库
git push origin :refs/tags/v1.0	删除远程的标签(首先要删除本地的这个标签)

git config --global alias.co checkout	配置命令别名	(--global 是全局参数)
git config --global alias.ci commit	配置命令别名
git config --global alias.br branch	配置命令别名