# 找到正在运行中的容器
被启动起来的容器正在后台运行，`docker ps`命令可以列出所有正在运行中的容器及其相关信息，例如用于启动该容器的镜像、该容器的ID及别名。

以下命令提供关于该容器的更多信息，比如 IP 地址。
```bash
docker inspect <friendly-name|container-id>
```

以下命令将会输出该容器的日志信息：
```bash
docker logs <friendly-name|container-id>
```