## 部署
- 用`git clone --recursive`拉取部署仓库与子模块
- 安装 Docker 与 Docker-Compose
- 修改根目录下的`.env`文件，将`BASE_URL`与`VUE_APP_BASE_URL`改为部署的服务器的URL
- 运行`docker compose up -d`，服务将运行在80端口