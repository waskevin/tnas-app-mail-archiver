# mail-archiver for TerraMaster TOS

用于 TerraMaster TOS 的容器应用说明与发布准备材料。

## 应用信息

- 上游项目：https://github.com/s1t5/mail-archiver
- Docker 镜像：`s1t5/mailarchiver:latest`
- 架构：linux/amd64、linux/arm64（已通过 Docker Hub 多架构标签核验）

## 运行示例

```bash
docker compose up -d
```

编排包含 PostgreSQL 依赖和数据保护密钥目录；请先复制 `.env.example` 并设置管理员与数据库密码。仓库不包含真实凭证。

- x86_64 预检截图：`precheck-screenshots/mail-archiver/x86_64/reprecheck.png`
- NAS x86_64 实测：HTTP 200，显示 Mail Archiver 登录页。

## 状态

- 本地说明材料已准备。
- TerraMaster 审核：未提交。
- 本仓库仅用于应用说明与打包准备。
