`git add`

`git log`显示从最近到最远的提交日志

`git log --pretty=oneline`

`git reset --hard HEAD^ `回退到上一个版本，HEAD为当前版本，上一个版本是`HEAD^`，再上个版本是`HEAD^^`，上100个版本是`HEAD~100`

`git reflog`记录每一次命令

`git checkout -- file `撤销工作区修改

`git reset HEAD file`撤销暂存区修改

`git rm`从版本库中删除

`git remote add origin git@server-name:path/repo-name.git`关联远程库

`git push -u origin master`第一次推送master分支所有内容

`git push origin master`推送最新修改

---

`git checkout -b dev`创建`dev`分支然后切换到`dev`分支

`git checkout`命令加上`-b`参数表示创建并切换，相当于

```bash
$ git branch dev
$ git checkout dev
Switched to branch 'dev'
```

`git branch`列出所有分支，当前分支会标记`*`

`git branch <name>`创建分支

`git checkout <name>`切换分支

`git merge <name>`合并某分支到当前分支

`git branch -d <name>`删除分支

