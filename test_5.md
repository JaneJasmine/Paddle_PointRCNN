1、拉取某分支
`git pull origin main`

2、查看状态
`git status`

3、状态改变的提交到缓存
所有：
`git add .`

修改过的、被跟踪的：
`git add -u 路径`

修改过的、未被跟踪的：
`git add -A 路径`

4、提交到本地仓库
`git commit -m "增加了功能"`

5、将缓存区代码push到远程仓库某分支
`git push origin main`

6、切换到另一分支，再删除某分支
切换：
`git checkout main`

删本地：
`git branch -d v1.0`

删远程：
`git push origin --delete v1.0`

删追踪分支（删本地对远程的引用，对远程无影响）：
`git branch -d -r origin/v1.0`

7、列出远程跟踪分支
`git branch -r`

8、查看本地仓库未跟踪的远程分支
`git remote show origin -a * remote origin`