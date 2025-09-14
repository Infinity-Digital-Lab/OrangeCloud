# 🍊 OrangeCloud

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)
[![GitHub Stars](https://img.shields.io/github/stars/Infinity-Digital-Lab/OrangeCloud?style=social)](https://github.com/Infinity-Digital-Lab/OrangeCloud/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Infinity-Digital-Lab/OrangeCloud?style=social)](https://github.com/Infinity-Digital-Lab/OrangeCloud/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/Infinity-Digital-Lab/OrangeCloud)](https://github.com/Infinity-Digital-Lab/OrangeCloud/issues)

**一个安全、开源的自托管云平台，为您所有的数据提供一个安全的家。**

---

## 📖 关于项目

**OrangeCloud** 是一个免费、开源的自托管云平台，旨在让您轻松掌控个人数据。在这个数据已成为商品的时代，OrangeCloud 提供了一个安全、私密且功能一体化的解决方案，完全由您托管和控制。

遵循简洁与易用的设计原则，为您带来无缝的云实例部署与维护体验。无论您是开发者、隐私倡导者，还是仅仅想为自己的文件寻找一个可靠的归宿，OrangeCloud 都能满足您的需求。

## ✨ 主要特性

* **🔒 安全与私密**: 您的数据只存在于您的服务器上。杜绝任何第三方访问、扫描或妥协 （将AI爬虫隔绝）。
* **🚀 轻松部署与维护**: 通过简化的安装流程，您可以在几分钟内启动并运行。将最核心的功能集成在单一实例中，力求简洁。
* **🌐 一体化解决方案**: 通过一个直观的界面，轻松管理您的文件、照片、日历、联系人等。
* **✨ 免费与开源**: OrangeCloud 将永远可以免费使用、修改和分发。采用 [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0) 许可证。

## 🚀 快速开始

推荐使用 Docker 来快速部署 OrangeCloud。

### 先决条件

* [Docker](https://www.docker.com/get-started)
* [Docker Compose](https://docs.docker.com/compose/install/)

### 安装步骤

1.  克隆本仓库到您的服务器：
    ```bash
    git clone [https://github.com/Infinity-Digital-Lab/OrangeCloud.git](https://github.com/Infinity-Digital-Lab/OrangeCloud.git)
    cd OrangeCloud
    ```

2.  配置您的环境（根据需要创建并编辑 `.env` 文件）：

3.  使用 Docker Compose 启动服务：
    ```bash
    docker-compose up -d
    ```

4.  恭喜！现在您可以通过浏览器访问 `http://localhost:5200` (或您配置的端口) 来访问您的 OrangeCloud 实例。

## 🤝 如何贡献

热烈欢迎各种形式的贡献！无论是提交代码、报告 Bug、建议新功能，还是改进文档，都对项目至关重要。

在您开始之前，请先阅读 **[贡献指南](./CONTRIBUTING.md)**。

您可以在 [Issues](https://github.com/Infinity-Digital-Lab/OrangeCloud/issues) 页面查看待办任务和已知问题。

## 📜 开源许可证

本项目基于 [AGPL-3.0 License](./LICENSE) 许可证开源。

---

** kavin.c.liu@gmail.com 构建一个更加私密和去中心化的互联网 **
