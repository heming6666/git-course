# Step 5 - .gitignore 文件
有时候你并不想把所有文件都提交到 Git 仓库中去，比如：
- 操作系统自动生成的文件，比如缩略图；
- 编译生成的中间文件，比如 Java 编译产生的 .class 文件；
- 自己的敏感信息，比如存放口令的配置文件。

.gitignore 文件允许设置忽略一些文件或目录，Git 将不会保存这些文件的任何更改。

## 任务
在仓库的根目录创建一个 .gitignore 文件，以忽略所有的 .tmp 文件，并提交到 Git 仓库：
```bash
echo '*.tmp' > .gitignore
```
```bash
git add .gitignore
```
```bash
git commit -m "gitignore file"
```
