# Article Annotator

> Obsidian 插件：文章批注 —— 像 Microsoft Word 一样高亮文本并添加批注

[![Release](https://img.shields.io/github/v/release/kilng235/article-annotator-plugin)](https://github.com/kilng235/article-annotator-plugin/releases)
[![Obsidian Plugins](https://img.shields.io/badge/Obsidian-Plugin-blue)](https://obsidian.md/plugins)

---

## 功能

- **文本高亮 + 批注**：在 Markdown 编辑器中高亮选中文字，添加类似 Word 的批注
- **侧边栏管理**：在侧边栏面板中查看所有批注，支持编辑、删除、导出
- **批注卡片拖拽排序**：在侧边栏中自由拖拽调整批注顺序
- **多端支持**：支持 **电脑（Desktop） / iPad / 手机（Android）** 三端使用
  - ⚠️ 跨设备需手动同步（通过 Remotely Save 等插件），自动同步功能后续更新
- **中英双语**：支持中英文界面切换
- **6 色高亮**：暖黄、浅绿、浅蓝、浅紫、浅红、橙色，支持自定义颜色
- **快捷键支持**：高亮、新建批注、删除批注均可绑定快捷键
- **移动端适配**：支持 Android 和 iPad 触摸操作

---

## 安装

### Obsidian 社区插件市场（推荐）

1. 打开 Obsidian → 设置 → 社区插件 → 浏览
2. 搜索 `Article Annotator`
3. 点击安装并启用

### 手动安装

1. 从 [Releases](https://github.com/kilng235/article-annotator-plugin/releases) 下载最新版本的 `main.js`、`manifest.json`、`styles.css`
2. 在 Obsidian vault 的 `.obsidian/plugins/` 目录下新建文件夹 `article-annotator`
3. 将三个文件放入该文件夹
4. 重启 Obsidian，在设置 → 社区插件中启用

---

## 使用说明

### 高亮文本

1. 在 **编辑模式** 下选中文字
2. 使用命令 `文章批注：高亮选中内容`（或绑定快捷键）
3. 高亮颜色在设置中可自定义

### 添加批注

1. 高亮后，在侧边栏 `Article Annotator` 面板点击 **新建批注**
2. 输入批注内容并保存
3. 批注卡片支持拖拽排序

### 管理批注

- **编辑**：在侧边栏点击批注卡片进入编辑
- **删除**：点击删除按钮（全局删除有二次确认）
- **清空**：可一键清空所有批注
- **导出**：支持导出为 JSON 格式

### 阅读模式

> ⚠️ 阅读模式当前不显示批注高亮，请在编辑模式下查看。

---

## 设置

| 设置项 | 说明 |
|--------|------|
| 默认高亮颜色 | 选择新批注的默认颜色 |
| 语言 | 中文 / English 界面切换 |
| 高亮颜色列表 | 6 种颜色可自定义 |
| 快捷键 | 在 Obsidian 设置 → 快捷键中绑定 |

---

## 版本历史

详见 [CHANGELOG](https://github.com/kilng235/article-annotator-plugin/blob/main/CHANGELOG.md)

---

## 注意事项

- 所有批注数据独立保存于 `.obsidian/plugins/article-annotator/data.json`，**不修改原文文件**
- 跨设备同步需手动操作（推荐 Remotely Save 插件），自动云同步功能正在开发中
- 阅读模式下高亮不显示，仅编辑模式可见

---

## 许可

MIT License
