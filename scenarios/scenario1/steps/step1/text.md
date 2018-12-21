# 运行第一个容器

第一个任务是运行一个 `Redis` 容器。首先我们需要确定 Docker 镜像的名称。在 Doker 中，所有容器都是基于 Doker 镜像启动的。这些镜像包含了启动该过程所需的一切而不需要任何配置或依赖项。 

Jane 可以在 registry.hub.docker.com/ 找到现有的镜像，或者使用 `docker search <name>`命令 。例如，要查找`Redis`的镜像，可以使用以下 docker 命令：
```bash
docker search redis
```
## 任务

通过使用`search`命令，Jane 知道了`Redis` 的Docker 镜像是 `Redis`，并希望运行该镜像的最新版本。因为`Redis`是一个数据库，Jane 希望将其作为后台服务运行。 

我们可以使用 `docker run <options> <image-name>` 命令来启动一个容器。该命令默认在前台运行。为了能让容器在后台运行，需要指定`-d`参数。

```bash
docker run -d redis
```
Docker 默认将会运行该镜像的`latest`最新版本。如果需要指定某个版本，需要添加该版本的标签。例如：
```bash
docker run -d redis：3.2
```
因为这是 Jane 第一次使用 `Redis` 镜像, 该镜像将会被下载到 Docker Host machine 中.
