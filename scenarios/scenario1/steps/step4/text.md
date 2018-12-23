# Step 4 - 提交缓存
git commit命令将缓存的快照提交到项目历史。提交的快照可以认为是项目安全的版本，Git 永远不会改变它们，除非你这么要求。和 git add 一样，这是最重要的 Git 命令之一。

## 任务
用命令 git commit -m <message> 告诉Git，把文件提交到仓库：
```bash
git commit -m "wrote a readme file"
```

## 小贴士
git commit 命令中， -m 后面输入的是本次提交的说明，可以输入任意内容，当然最好是有意义的，这样你就能从历史记录里方便地找到改动记录。

git add、git status 和 git commit 这三个命令通常一起使用，将 Git 项目当前的状态保存成一份快照。
