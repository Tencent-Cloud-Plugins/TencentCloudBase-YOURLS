<p align="center">
  <img height="100px" src="./logo.svg" />
</p>

# [YOURLS](https://github.com/YOURLS/YOURLS)

YOURLS是一款开源免费的URL短链接管理平台，可利用它构建URL缩短服务并追踪访问效果。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-YOURLS&branch=master)

### 配置
- `YOURLS_DB_HOST`: 数据库地址
- `YOURLS_DB_NAME`: 数据库名称
- `YOURLS_DB_USER`: 数据库用户名
- `YOURLS_DB_PASS`：数据库密码
- `YOURLS_SITE`：应用站点
- `YOURLS_USER`：用户账号
- `YOURLS_PASS`：用户密码

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/admin`
