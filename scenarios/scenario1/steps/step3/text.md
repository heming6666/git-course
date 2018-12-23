# Step 3 - 添加到暂存区 git add
git add 命令将工作目录中的变化添加到暂存区。它告诉 Git 你想要在下一次提交时包含这个文件的更新。但是，git add 不会实质上地影响你的仓库——在你运行 git commit 前更改都还没有真正被记录。

使用这些命令的同时，你还需要 git status 来查看工作目录和暂存区的状态。

## 任务
使用 git add <file|directory> 命令将 readme.txt 添加到暂存区：
```bash
git add readme.txt
```
并使用git status 来查看工作目录和暂存区的状态：
```bash
git status
```
