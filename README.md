# 数字资产交易平台（全栈项目）

一个完整的加密资产交易平台方案，覆盖 **前台桌面端（Tauri）**、**H5 移动端**、**管理后台** 与 **Java 后端服务**。适用于品牌官网展示、功能演示、二次开发与部署交付。

---

## ✨ 项目亮点

- **全端覆盖**：桌面端（Tauri）、H5、管理后台、后端服务一体化
- **交易形态齐全**：现货、交割、永续合约、C2C、闪兑
- **资产体系完整**：充币/提币/划转/资产统计
- **金融业务模块**：定期理财、质押借币、节点计划、跟单交易
- **国际化支持**：多语言切换
- **模块化架构**：前后端分离，便于扩展与定制

---

## 🧩 模块一览

| 模块 | 目录 | 技术栈 |
| --- | --- | --- |
| 桌面客户端 | nv-pc | Tauri + React + TypeScript |
| H5 前台 | nv-h5 | Vite + Vue |
| 管理后台 | nv-admin | Vue + Element 生态 |
| 后端服务 | nv | Java / Spring Boot 生态 |

---

## 🚀 功能概览

- **账号体系**：登录、注册、找回、KYC、账号安全
- **行情中心**：实时行情、K线、行业资讯
- **交易中心**：现货 / 交割 / 永续
- **资产中心**：我的资产、充币、提币、闪兑、C2C 交易
- **理财中心**：定期理财、质押借币、节点计划、跟单交易
- **NFT 模块**：NFT 展示与市场入口
- **慈善中心**：公益入口

---

## 🖼️ 界面预览

项目截图位于 `docs/screenshots/` 目录，包含以下核心页面：

| 页面 | 文件名 | 说明 |
| --- | --- | --- |
| 首页 | home.png | 平台概览与行情入口 |
| 交易 | trade.png | 现货/合约交易界面 |
| 资产 | assets.png | 资产管理与资金划转 |
| C2C | c2c.png | 法币交易市场 |
| 管理后台 | admin.png | 运营管理系统 |

**图片预览：**

### 首页
![首页](docs/screenshots/home.png)

### 交易
![交易](docs/screenshots/trade.png)

### 资产
![资产](docs/screenshots/assets.png)

### C2C
![C2C](docs/screenshots/c2c.png)

### 功能演示视频

![video](docs/screenshots/2026-01-28_12-27-31.mp4)
---

## 🛠️ 技术栈

**前端**
- React 19 / TypeScript / Tailwind
- Vite / Zustand / React Router

**桌面端**
- Tauri 2.x

**后端**
- Java / Spring Boot 生态

---

## ⚡ 快速开始

### 1) 桌面客户端（Tauri）

**下载地址：** [release/nv-pc_0.1.0_x64.dmg](release/nv-pc_0.1.0_x64.dmg)

```bash
cd nv-pc
npm install
npm run dev
```

### 2) H5 前台

```bash
cd nv-h5
pnpm install
pnpm dev
```

### 3) 管理后台

```bash
cd nv-admin
pnpm install
pnpm dev
```

### 4) 后端服务

```bash
cd nv
# 根据实际环境构建/启动
```

---

## 📄 文档

- [桌面端文档](nv-pc/README.md)
- [API 集成报告](nv-pc/API_INTEGRATION_REPORT.md)
- [API 快速参考](nv-pc/API_QUICK_REFERENCE.md)
- [部署与使用说明](Doc)

---

## 🔗 商业化合作 / 定制开发

如果你需要 **定制版本、私有化部署、功能扩展或商用授权**，欢迎联系。

**联系信息：**

- Telegram：@nv_exchange
- 邮箱：nvcha3901@proton.me

---

## 💝 请博主喝茶

如果这个项目对你有帮助，欢迎支持捐赠。你的支持将用于持续维护与功能优化。

**捐赠信息：**

- USDT(TRC20)：TQLmVxmAGXCqm6t2ab1P3rjehB8SuuUuUu
- USDT(ERC20)：0x9Da59FD96Bcb8700727038267de56380BeA72fb3
- BTC：bc1pzykrwx2xa84h04evtx0tp85a897kxvqdq98x07u50ejg57jeae4q3x4y8x
- ETH：0x9Da59FD96Bcb8700727038267de56380BeA72fb3
- BSC(BEP20)：0x9Da59FD96Bcb8700727038267de56380BeA72fb3

---

## 📜 免责声明

本项目仅用于技术演示与学习交流，不构成任何投资建议。
