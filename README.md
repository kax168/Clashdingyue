# 📄 Clash Reality 订阅示例 - goodvpn.shop

---

## 🔑 内容简介

这是我的 Clash Reality 配置仓库，专门用来托管 **可自动订阅的节点与分流规则**，适用于：
- 社交媒体：X（Twitter）、TikTok、Telegram、Facebook、Discord、Instagram
- 流媒体：YouTube、Netflix
- AI：ChatGPT（OpenAI）、MidJourney（含 Discord 入口）
- 其他全局兜底代理

---

## ✅ 节点说明

- **入口域名**：`goodvpn.shop`（已解析到 VPS）
- **Reality 伪装域名（SNI）**：`www.cloudflare.com`
- **协议**：VLESS + Reality + uTLS 指纹伪装（`client-fingerprint: chrome`）
- **证书**：Reality 自动伪装大站 HTTPS，无需自己申请或签发

---

## ✅ 如何使用

1️⃣ **仓库已包含 `config.yaml`**
   - 节点已写好 Reality 主节点 + 备用节点
   - 分流已覆盖常用社交、AI、流媒体
   - 所有规则都走 `Proxy` 组，无裸奔直连

2️⃣ **启用 GitHub Pages**
   - `Settings → Pages`
   - `Source` 选择 `Deploy from a branch`
   - `Branch`：选择 `main`（或 `master`）
   - `Folder`：选择 `/ (root)`

3️⃣ GitHub Pages 会生成：
