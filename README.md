# LearningProgress
考核依据——提交每天的学习进度
2019年7月22日
学习分布式版本控制仓库Git。
1、安装Git,并完成本地版本控制仓库。
2、管理版本控制仓库。
   a.查看当前仓库状态 git status
   b.查看修改的内容  git diff
   c.版本回退 git reset --hard commitid
   d.将修改添加到缓存区  git add 
   e.将缓存区提交到仓库 git commit
   f.撤销修改 git checkout -- <file>(未添加到缓存区) git reset HEAD <file>(已添加到缓存区时，执行该命令后再执行撤销命令) 已提交修改时，直接版本回退。
   g.删除文件 先删除文件 rm <file> 再git rm <file> 将删除信息添加到缓存区，最后commit；删错可使用撤销修改
3.远程仓库和本地仓库的关联并实现push和clone
