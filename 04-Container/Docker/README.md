# Docker/Compose 部署 Demo

目标：一条命令启动一个可被运维的小服务（含反向代理与健康检查）。

## 启动
- docker compose up -d

## 验证
- 访问 http://<vm-ip>/
- 查看日志：docker logs -f <container>

## 常见问题
- 端口占用
- 容器未启动
- 反向代理配置错误
