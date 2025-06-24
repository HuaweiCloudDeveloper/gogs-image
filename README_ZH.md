<p align="center">
  <h1 align="center">gogs自助git服务</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[Gogs](https://github.com/gogs/gogs) 是一款极易搭建的自助 Git 服务。

**主要特性：**
- 控制面板、用户页面以及活动时间线
- 通过 SSH、HTTP 和 HTTPS 协议操作仓库
- 管理用户、组织和仓库
- 仓库和组织级 Webhook，包括 Slack、Discord 和钉钉
- 仓库 Git 钩子、部署密钥和 Git LFS
- 仓库工单（Issue）、合并请求（Pull Request）、Wiki、保护分支和多人协作
- 从其它代码平台迁移和镜像仓库以及 Wiki
- 在线编辑仓库文件和 Wiki
- Jupyter Notebook 和 PDF 的渲染
- 通过 SMTP、LDAP、反向代理、GitHub.com 和 GitHub 企业版进行用户认证
- 开启两步验证（2FA）登录
- 自定义 HTML 模板、静态文件和许多其它组件
- 多样的数据库后端，包括 PostgreSQL、MySQL、SQLite3 和 TiDB
- 超过 [31 种语言](https://crowdin.com/project/gogs) 的本地化

本项目提供的开源镜像商品 [**Gogs**]()，已预先安装 Gogs 及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                    | 特性说明                                           | 备注 |
|-------------------------|------------------------------------------------| --- |
| [gogs-0.13.3-鲲鹏-v1.0]() | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/gogs-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
