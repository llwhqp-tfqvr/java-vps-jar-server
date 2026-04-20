# 🚀 Java VPS JAR Server

<p align="center">
  <strong>高性能多协议 VPS 后端中转服务</strong>
  <br />
  支持 TUIC、Hysteria2 与 Reality 协议，专为复杂网络环境下的流量转发设计。
</p>

---

## ✨ 项目特性

- ⚡ **多协议支持**：原生支持 TUIC / HY2 / REALITY 等现代高速传输协议。
- 🛠️ **极简配置**：通过单一 `config.yml` 即可快速完成多端口监听设置。
- 📦 **轻量部署**：单个 JAR 文件，无需安装复杂的系统依赖。
- 🛡️ **SNI 伪装**：支持自定义 SNI 设置，提升服务的隐蔽性与安全性。

---

## 📂 文件结构说明

| 文件名 | 类型 | 说明 |
| :--- | :--- | :--- |
| `server.jar` | **二进制程序** | 核心服务端主程序，负责流量调度与解密。 |
| `config.yml` | **配置文件** | 定义各协议监听端口及伪装域名。 |
| `README.md` | **文档** | 您当前看到的项目使用指南。 |

---

## ⚙️ 快速配置

请编辑根目录下的 `config.yml` 文件，填入您需要开放的端口和伪装域名：

```yaml
# --- Java VPS Server 核心配置 ---

# 🔹 TUIC 协议监听端口 (UDP)
tuic_port: "25755"

# 🔹 Hysteria2 协议监听端口 (UDP)
hy2_port: ""

# 🔹 Reality 协议监听端口 (TCP)
reality_port: ""

# 🌐 SNI 伪装域名 (用于 TLS 握手伪装)
sni: "[www.baidu.com](https://www.baidu.com)"
