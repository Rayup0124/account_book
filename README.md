# 拾记(Shiji ): LifePicked 📖

一款功能强大、移动端的个人财务记事本应用，使用 Flutter 构建。它不仅能帮您记录每一笔收支，还能附上图片和心情故事，让记账变得有温度。

---

## ✨ 主要功能 (Key Features)

- **核心记账:**
  - 轻松记录**收入**与**支出**。
  - 支持**图片附件**功能，可从相册选择或直接拍照，为每笔账单留下生动回忆。
  - 可添加详细的文字备注。
- **数据管理:**
  - 所有数据安全地存储在**本地数据库**中 (`SQLite` for Mobile/Desktop, `IndexedDB` for Web)。
  - 支持按月筛选账单。
  - 实现了账单的删除功能。
- **数据可视化:**
  - 独立的**统计页面**，提供清晰的财务概览。
  - **饼状图**直观展示各类别的支出占比。
  - 月度收入与支出总额汇总。
- **高度自定义与良好体验:**
  - **自定义数字键盘**，并集成了**小型计算器**，金额输入更便捷。
  - 支持**主题切换**，个性化您的App外观。
  - 实现了平滑的动画效果，操作流畅。

---

## 🚀 如何安装 (Installation)

1. 前往本项目的 [Releases 页面](https://github.com/rayup0124/account_book/releases)。
2. 下载最新版本的 `app-release.apk` 文件。
3. 将文件传输到您的安卓手机上，点击安装即可。
   - *注意: 安装时可能需要您授权“允许安装来自未知来源的应用”。*

---

## 🛠️ 构建工具 (Built With)

- **[Flutter](https://flutter.dev/)** - Google 的开源 UI 工具包，用于从单一代码库为移动、Web和桌面构建美观、本地编译的应用程序。
- **[fl_chart](https://pub.dev/packages/fl_chart)** - 用于创建精美图表的库。
- **[sqflite](https://pub.dev/packages/sqflite)** - 用于在移动端进行 SQLite 数据库操作。
- **[image_picker](https://pub.dev/packages/image_picker)** - 用于选择图片和拍照。
