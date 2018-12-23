# Step 3 - 提交修改

知道了对readme.txt作了什么修改后，再把它提交到仓库就放心多了，提交修改和提交新文件是一样的两步，第一步是git add：
```bash
git add readme.txt
```

在执行第二步git commit之前，我们再运行git status看看当前仓库的状态：
```bash
git status
```

git status告诉我们，将要被提交的修改包括readme.txt，下一步，就可以放心地提交了：
```bash
git commit -m "add distributed"
```

提交后，我们再用git status命令看看仓库的当前状态：
```bash
$ git status
On branch master
nothing to commit, working tree clean
```
Git告诉我们当前没有需要提交的修改，而且，工作目录是干净（working tree clean）的。


