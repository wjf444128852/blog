> 一、常用命令

+ git status查看当前仓库状态(是否有文件改动)
+ git diff查看改动后新加的内容(在没有commit之前是可以的，commit之后看不到)
+ git log --pretty=oneline查看所有的提交信息
+ git checkout -- file放弃工作区的修改，没有--就是切换到另一个分支了
+ rm filename 删除文件(命令行删除还是手动删除都要重新add/commit)
+ 如果误删还没commit可以git checkout -- filename恢复文件
+ git show [commit]在命令行查看该次提交前后文件的对比，新增变化
+ git fetch -p origin   清除缓存
+ git branch -D branchName 删除本地分支	
+ git push origin -d branchName(分知名)  刪除远程分支

> 二、配置别名

+ 有时候会觉得git命令繁琐，可以自己配置别名如：
+ git config --global alias.st status，此时git st===git status
+ 当然还有别的命令可以简写，很多人都用co表示checkout，ci表示commit，br表示branch
+ git config --global alias.co checkout
+ git config --global alias.ci commit
+ git config --global alias.br branch



