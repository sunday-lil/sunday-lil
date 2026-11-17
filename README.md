<h1 align="center">sunday-lil</h1>

<p align="center">
  <em>把一件事做透，就不做成两件。</em><br/>
  <sub>本地优先的工具 · 能把协议摸清再动手 · 每个项目自带测试</sub>
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="Vue3" src="https://img.shields.io/badge/Vue3-4FC08D?logo=vuedotjs&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img alt="C%23" src="https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
</p>

---

## 我在做什么

- **本地优先**：能跑在自己机器上的，就不塞服务器；能不联网的，就不联网。
- **先摸协议再写代码**：抓包、读前端 bundle、必要时逆向客户端——但只做**互操作性**和**安全研究**，不搬运厂商代码。
- **交付 = 代码 + 测试**：几个主力仓库都有离线用例，CI 在 ubuntu / windows 双平台跑。
- **桌面端**偏爱 PySide6 / WPF，**Web 端**就是 FastAPI + Vue3 + SQLite，不引入多余中间件。

---

## 精选项目

### 🎬 [grabdown](https://github.com/sunday-lil/grabdown) · [![CI](https://github.com/sunday-lil/grabdown/actions/workflows/ci.yml/badge.svg)](https://github.com/sunday-lil/grabdown/actions)

IDM 式多线程下载器 + Chrome/Edge 扩展。

- **分段引擎**：Range 切块、线程池并发、断点续传、实时进度
- **HLS**：master 选码率 → 分片并发 → AES-128 解密 → `ffmpeg -c copy` 合流
- **失败自救**：码率自动降级、410/403 回页面取新链、Referer/UA/Cookie 自动补
- **21 站平台识别**：B 站 / YouTube / 抖音 / TikTok / X / Instagram … 交 yt-dlp；PornHub 原生解析；DRM 站点只识别不下载
- **浏览器扩展**：页面浮标、右键菜单、自动捕获所有标签页、WebSocket 实时进度

`Python` · `Manifest V3` · `yt-dlp` · `ffmpeg` · 45 个用例 · CI 覆盖 Python 3.12/3.15 × ubuntu/windows · MIT

### 📦 [panl](https://github.com/sunday-lil/panl) · [![CI](https://github.com/sunday-lil/panl/actions/workflows/ci.yml/badge.svg)](https://github.com/sunday-lil/panl/actions)

10 家网盘的分享直链提取器：粘贴链接 → 直链 + **它需要的请求头**（Referer / UA / Cookie）。

- 桌面 GUI（Chromium `--app` 独立窗口）/ CLI / 本地 Web，三个入口一套内核
- 阿里 / 百度 / 123 / 夸克 / UC / 蓝奏 / 天翼 / 115 / 微云 / 迅雷
- `transfer` 转存、`endpoints` 端点可覆盖（厂商换域名不用改代码）
- 和 grabdown 联动：GUI 里点「下载」，直链交给本地下载器，SSE 推进度

`Python` · 36 个用例 · MIT

### 🌿 [jingyu](https://github.com/sunday-lil/jingyu) ★3

**静屿** —— 非商业治愈系疗愈平台：古琴五音疗愈、端到端加密漂流日记瓶、AI 心语树洞、罗素情绪环日历、花田养成。FastAPI + Vue3 + Three.js，两步自部署，数据留在自己机器上。

### 🧠 [ZhangMoxuan](https://github.com/sunday-lil/ZhangMoxuan) ★1

**550W / MOSS 智能量子计算机系统** —— 流浪地球风格的 WPF 原生桌面应用，纯视觉复刻，不接任何真实算力。

### 🗂 [project-manager](https://github.com/sunday-lil/project-manager)

任务看板 + 本地仓库 + GitHub 集成 + IDE 工作区同步，PySide6 单机版。

---

## 全部仓库

| 项目 | 是什么 | 技术 |
|---|---|---|
| [grabdown](https://github.com/sunday-lil/grabdown) | 多线程下载器 + 浏览器扩展 + 21 站平台识别 | Python · MV3 · yt-dlp |
| [panl](https://github.com/sunday-lil/panl) | 10 家网盘直链提取（GUI / CLI / Web） | Python |
| [jingyu](https://github.com/sunday-lil/jingyu) | 静屿：隐私优先的疗愈 Web 应用 | FastAPI · Vue3 · Three.js |
| [project-manager](https://github.com/sunday-lil/project-manager) | 任务看板 + GitHub 集成 + IDE 同步 | PySide6 |
| [ai-memory-manager](https://github.com/sunday-lil/ai-memory-manager) | 本地 AI 对话记录（JSON）管理 GUI，零依赖 | Python 标准库 |
| [LingHuiBot](https://github.com/sunday-lil/LingHuiBot) | 凌辉 Bot —— 一只无害的 py 海龟维护的开源机器人 | Python |
| [my-plugin](https://github.com/sunday-lil/my-plugin) | EssentialsX-Clone：Minecraft 服务器管理插件 | Java |
| [ZhangMoxuan](https://github.com/sunday-lil/ZhangMoxuan) | 550W/MOSS 风格 WPF 桌面系统 | C# · WPF |
| [ntpx-rust-sim](https://github.com/sunday-lil/ntpx-rust-sim) | 分布式压测控制台的**视觉模拟器**（影视道具，不产生真实流量） | C# · WPF |
| [music-spatial-sessions](https://github.com/sunday-lil/music-spatial-sessions) | Apple Music 风格的空间听歌房间，生成式 Web Audio | JavaScript · Web Audio |
| [mars-outpost-cadquery](https://github.com/sunday-lil/mars-outpost-cadquery) | CadQuery 参数化三维建模脚本 | Python · CadQuery |
| [dazhaomofang-analysis](https://github.com/sunday-lil/dazhaomofang-analysis) | 学生端 v10.8.2 逆向分析报告（互操作/安全研究，不含厂商代码） | JavaScript · CC BY-NC 4.0 |
| [comfy-backup](https://github.com/sunday-lil/comfy-backup) | 自用备份 | — |

---

## 技术栈

```text
语言      Python · C# · Java · JavaScript · Vue3
后端      FastAPI · SQLite · 标准库优先
桌面      PySide6 · WPF · Chromium --app
前端      Vue3 · Vite · Three.js · Web Audio
工具链    GitHub Actions（ubuntu + windows 双平台）· unittest · Node 自写测试
领域      网络协议 / 媒体流（HLS·DASH）· 逆向与互操作 · 本地优先架构
```

---

## 最近动态

- 🆕 `grabdown` v0.3.1 — 分段下载 + HLS/AES + 21 站平台识别 + 扩展（[release](https://github.com/sunday-lil/grabdown/releases/latest)）
- 🆕 `panl` v0.1.1 — 10 家网盘直链 + 桌面 GUI + 转存（[release](https://github.com/sunday-lil/panl/releases/latest)）
- 🌿 `jingyu` — 隐私优先的疗愈平台，仍在迭代
- 🔧 两个工具的 CI 现已覆盖 **Python 3.12 与 3.15**（ubuntu + windows 双平台）

---

## 说明

- 各仓库许可以仓库内 `LICENSE` 为准：多数是 **MIT**，`dazhaomofang-analysis` 为 **CC BY-NC 4.0**。
- 含 DRM 的流媒体（Netflix / Disney+ / Spotify）**只做平台识别，不做下载**。
- 逆向相关仓库仅用于互操作性与安全研究，不包含、不分发任何厂商代码或数据。

<p align="center"><sub>Thanks for stopping by 🌱</sub></p>
