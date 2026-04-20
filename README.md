# 🚀 Java VPS JAR Server

<p align="center">
  <img src="https://img.shields.io/github/languages/top/BoaHankok/java-vps-jar-server?style=for-the-badge&logo=java&logoColor=white&color=orange" alt="Java">
  <img src="https://img.shields.io/github/repo-size/BoaHankok/java-vps-jar-server?style=for-the-badge&logo=git&logoColor=white&color=blue" alt="Size">
  <img src="https://img.shields.io/github/license/BoaHankok/java-vps-jar-server?style=for-the-badge&color=green" alt="License">
  <img src="https://img.shields.io/github/last-commit/BoaHankok/java-vps-jar-server?style=for-the-badge&logo=github&logoColor=white" alt="Last Commit">
</p>

<p align="center">
  <strong>一款轻量级、高性能的 VPS 后端服务程序</strong>
  <br />
  通过简单的配置，快速在您的服务器上部署稳健的服务环境。
</p>

---

## ✨ 项目特性

- ⚡ **极速响应**：基于 Java 核心驱动，专为 VPS 环境优化。
- 🛠️ **极简配置**：通过单一的 `yml` 文件管理所有关键参数。
- 📦 **开箱即用**：无需复杂安装，直接运行 JAR 即可启动。
- 🛡️ **稳定运行**：支持长时间挂机运行，资源占用极低。

---

## 📂 文件说明

| 文件名 | 类型 | 说明 |
| :--- | :--- | :--- |
| `server.jar` | **可执行程序** | 核心服务端主程序。 |
| `config.yml` | **配置文件** | 用于定义端口、性能参数等关键设置。 |
| `README.md` | **文档** | 项目使用说明手册。 |

---

## ⚙️ 快速配置

在启动服务之前，请务必修改 `config.yml` 文件以确保端口正确：

```yaml
# Java VPS Server 配置文件
server:
  # 🌐 您希望服务器监听的端口
  port: 25755
  
  # 📂 日志级别 (INFO/DEBUG/ERROR)
  log_level: "INFO"


