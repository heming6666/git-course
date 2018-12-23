# Step 1 - Git Status

正如上一小节所述，`git status` 命令可以列出已缓存、未缓存、未追踪的文件。

## 任务

在上一小节中，我们已经成功地添加并提交了一个readme.txt文件，现在，是时候继续工作了，于是，我们继续修改readme.txt文件，改成如下内容：
```bash
echo 'Git is a distributed version control system.' > readme.txt 
```
现在，运行git status命令看看结果：
```bash
git status
```

## 小贴士
git status 命令可以让我们时刻掌握仓库当前的状态，上面的命令输出会告诉我们，readme.txt被修改过了，但还没有准备提交的修改。
