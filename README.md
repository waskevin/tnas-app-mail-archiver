# mail-archiver for TerraMaster TOS

用于 TerraMaster TOS 的容器应用说明与发布准备材料。

## 应用信息

- 上游项目：https://github.com/s1t5/mail-archiver
- Docker 镜像：`leplusorg/mail:sha-4061b9f`
- 架构：linux/amd64、linux/arm64（已通过 Docker Hub 多架构标签核验）

## 运行示例

```bash
docker run -d --name mail-archiver --restart unless-stopped -e TZ=Asia/Shanghai leplusorg/mail:sha-4061b9f
```

请按上游文档配置持久化目录和端口；仓库不包含密码、令牌或私钥。

## 状态

- 本地说明材料已准备。
- TerraMaster 审核：未提交。
- 本仓库仅用于应用说明与打包准备。
