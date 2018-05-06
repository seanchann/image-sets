# 安装部署jenkins

编译镜像

```bash
docker build -t tools/jenkins -f Dockerfile .
```

启动

```bash
docker-compose up -d
```

