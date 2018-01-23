# Docker Image Ubuntu-CN
本镜像基于Ubuntu官方镜像，只是将apt源改成了阿里云的源，解决Ubuntu国内apt下载慢的问题。

### 用法

`docker run -it d87904488/ubuntu-cn bash`

首次使用请先 `apt update` 进行更新。