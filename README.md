创建token保存好，进入项目的workspace

docker login --username github用户名 --password token ghcr.io    登录

docker build . -t ghcr.io/github用户名/镜像名:tag名             构建

docker push ghcr.io/github用户名/镜像名:tag名                推送

将package设为公开
