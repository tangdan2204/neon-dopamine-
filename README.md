# 🎮 霓虹浪潮：多巴胺循环

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

> 一款色彩斑斓、节奏飞快的街机射击游戏，在不断涌来的敌潮中存活、收集经验、升级解锁毁灭性技能。

**[🕹️ 在线游玩](https://neon.tangdan.cc)**

![游戏截图](assets/images/screenshot.gif)

## 📸 游戏画廊

<p align="center">
  <img src="assets/gameplay_1.png" width="32%" alt="游戏画面 1" style="border-radius: 10px; margin-bottom: 5px;">
  <img src="assets/gameplay_2.png" width="32%" alt="游戏画面 2" style="border-radius: 10px; margin-bottom: 5px;">
  <img src="assets/gameplay_3.png" width="32%" alt="游戏画面 3" style="border-radius: 10px; margin-bottom: 5px;">
  <img src="assets/gameplay_4.png" width="49%" alt="游戏画面 4" style="border-radius: 10px; margin-bottom: 5px;">
  <img src="assets/gameplay_5.png" width="49%" alt="游戏画面 5" style="border-radius: 10px; margin-top: 5px;">
</p>

## 📖 关于游戏

**霓虹浪潮：多巴胺循环** 是一款纯浏览器游戏，完全使用原生 JavaScript 和 HTML5 Canvas API 构建。没有外部引擎、没有依赖——只有纯粹的逻辑和绚烂的霓虹视觉。

穿梭于无尽的敌群之中，收集经验宝石升级，从动态升级池中选择增强。你能在浪潮中存活多久？

## ✨ 特性

* **零依赖：** 纯 JS、HTML 和 CSS 从零构建。
* **流畅机制：** 自定义物理、碰撞检测和粒子系统。
* **动态升级：** Roguelite 升级系统让每一局都独一无二。
* **绚烂视效：** 霓虹视觉搭配爽快的命中反馈和屏幕震动。
* **响应式设计：** 自动适配不同屏幕尺寸。

## ⌨️ 操控方式

* **鼠标移动**：瞄准并移动角色。
* **自动射击**：角色自动向光标方向开火。
* **空格键**：触发"巨型新星"技能（解锁后可用）。
* **左键点击**：在升级界面选择升级。

## 🛠️ 本地运行

由于游戏使用本地资源，直接打开 `index.html` 可能出现 CORS（跨域资源共享）错误。

需要本地 Web 服务器来运行：

**方法 1：使用 VS Code**
1. 安装 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 扩展。
2. 在 VS Code 中打开项目文件夹。
3. 右键 `index.html` 选择 **"Open with Live Server"**。

**方法 2：使用 Python**
1. 在项目目录打开终端。
2. 运行：`python -m http.server 8000`
3. 浏览器访问 `http://localhost:8000`。

**方法 3：使用 Node.js**
1. 在项目根目录运行 `npx serve`。

## 📂 项目结构

```text
├── assets/         # 游戏截图
│   ├── gameplay_1.png
│   ├── gameplay_2.png
│   ├── gameplay_3.png
│   ├── gameplay_4.png
│   └── gameplay_5.png
├── src/            # 核心 JavaScript 逻辑
│   └── main.js     # 主游戏循环和机制
├── index.html      # 主入口
├── style.css       # UI 和画布样式
└── README.md       # 项目文档
```

## 👨‍💻 原作者

**Artem**
* GitHub: [@artryazanov](https://github.com/artryazanov)

## 📄 许可协议

本项目基于 MIT 许可协议 - 详见 [LICENSE](LICENSE) 文件。
