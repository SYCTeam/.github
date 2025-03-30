# SYCTeam ![GitHub Org's stars](https://img.shields.io/github/stars/SYCTeam?style=social) ![License](https://img.shields.io/badge/License-AGPL--3.0-blue)

**SYCTeam** 是由三名开发者组成的独立团队，专注于 **构建自由、开放且有趣的开源项目**。我们秉持“小而精”的理念，致力于用代码实现创意，并通过 AGPL 许可证保障项目的开放性与协作性。

---

## 🌟 核心项目：SYCWorld

**[SYCWorld](https://github.com/SYCTeam/SYCWorld)** 是我们的首个开源项目，一个融合 **动态、聊天** 的跨平台应用。项目采用 AGPL-3.0 许可证，鼓励社区自由使用、修改与共享。

### 🚀 功能亮点
- **声明式 UI 架构**：通过 Compose 实现统一的 Android/Desktop UI 层，代码复用率超 85%。
- **跨平台逻辑共享**：使用 KMP (Kotlin Multiplatform) 在 Android、桌面端共享核心业务逻辑。
- **动态模块加载**：支持通过插件扩展功能，兼容 Gradle 依赖管理与自定义 JAR 模块。

### 🛠️ 技术栈
![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-blueviolet)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-1.6.0-4285f4)
![KMP](https://img.shields.io/badge/Kotlin%20Multiplatform-1.9.0-7F52FF)

- **核心框架**: Coroutines, Flow, Koin (DI)
- **构建工具**: Gradle + Version Catalogs
- **CI/CD**: GitHub Actions + Gradle

### ⚡ 快速开始（Android）
```bash
git clone https://github.com/SYCTeam/SYCWorld.git
cd SYCWorld
./gradlew :androidApp:assembleDebug
```

### 🖥️ 桌面端运行
```bash
./gradlew :desktopApp:run
```

---

## 🌱 如何参与

### 贡献指南
1. **Fork 仓库**：点击右上角 `Fork` 创建副本。
2. **本地开发**：
   ```bash
   git clone https://github.com/你的用户名/SYCWorld.git
   git checkout -b feature/your-idea
   ```
3. **提交代码**：遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范，并通过 Pull Request 提交到 `dev` 分支。
4. **代码审查**：团队成员将在 48 小时内反馈评审意见。

### 问题与建议
- 提交 Issue 时请标注类型（`bug` / `enhancement` / `question`）。
- 如需提案新功能，建议附上 **用例场景** 和 **技术可行性分析**。

---

## 🤝 社区协作

- **交流方式**：
  - [GitHub Discussions](https://github.com/SYCTeam/SYCWorld/discussions)：功能讨论与设计决策。
  - Issues 跟踪：透明化开发流程与问题修复。
- **支持我们**：
  - 点击 ⭐ **Star** 让更多人发现项目！
  - 通过 [Sponsor 渠道](https://github.com/sponsors/SYCTeam) 支持服务器费用。

---

## 📜 许可证与开源承诺

所有项目默认采用 **AGPL-3.0 许可证**，确保：
1. 代码修改必须开源。
2. 衍生作品需继承相同协议。
3. 禁止将代码用于闭源商业产品。

---

## 🔍 在线资源

- **实时预览**：通过 [github1s](https://github1s.com/SYCTeam/SYCWorld) 在线浏览代码。
- **统计看板**：![SYCWorld 活跃度](https://img.shields.io/github/commit-activity/m/SYCTeam/SYCWorld?label=月度提交)

---

## 🧑💻 团队愿景

> “我们相信，开源不仅是技术共享，更是创意碰撞的桥梁。  
> 即使三人成团，也要做改变世界的‘小齿轮’。”  
> —— SYCTeam 全体成员

**联系邮箱**: 3383787570@qq.com  

---

### 设计参考
- GitHub README 动态统计方案 [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) 
- 开源协作规范 [Fork 与 PR 流程]
- (https://www.ancii.com/ayuj5u6pl/)

---  

✨ **让 Compose 的魔法，点燃你的创造力！**
