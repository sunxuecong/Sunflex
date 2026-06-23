# Sunflex

Sunflex 是一款 Obsidian 主题，将 Sunflex 配色方案转换为 Obsidian 原生颜色变量，可直接作为独立主题使用。本主题基于 Minimal 主题的界面层构建。

## 截图

![Sunflex 主题截图](screenshot.png)

## 主题特性

- 基于 Sunflex 配色方案，提供舒适的阅读与写作体验
- 支持亮色（Light）与暗色（Dark）两种模式
- 内置 true-black 暗色变体（通过 `minimal-dark-black` 或 `black` 类启用）
- 色彩调色板涵盖红、橙、黄、绿、青、蓝、紫、粉八种语义色

## 安装方式

### 通过社区主题市场（推荐）

1. 打开 Obsidian → **设置** → **外观**
2. 点击「主题」旁边的 **管理**
3. 搜索 **Sunflex** 并点击 **安装**
4. 返回 **外观**，在主题下拉菜单中选择 **Sunflex**

### 手动安装

1. 将整个 `Sunflex` 文件夹（包含 `manifest.json`、`theme.css`、`README.md`）复制到仓库的 `.obsidian/themes/` 目录下
2. 重启 Obsidian
3. 打开 **设置** → **外观** → **主题**，选择 **Sunflex**

## 使用方式

安装后，在 **设置 → 外观 → 基础配色方案** 中切换亮/暗色。如需深度自定义，请安装 **Style Settings** 插件（见下文）。

## 自定义（Style Settings）

本主题完全兼容 [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) 插件，无需编辑 CSS 即可通过图形界面调整颜色、字体和功能。

### 启用 Style Settings

1. 安装 **Style Settings** 社区插件
2. 在 **设置** → **第三方插件** 中启用它
3. 打开 **设置** → **Style Settings** → **Minimal** 区域

### 可调节项

本主题的 Style Settings 面板包含以下分组：

| 分组 | 说明 |
| --- | --- |
| **界面颜色** | 基础色相/饱和度/亮度，以及主背景、次背景、激活背景（`bg1`、`bg2`、`bg3`）和边框颜色（`ui1`、`ui2`、`ui3`） |
| **强调色** | 主强调色（`ax1`）、悬停强调色（`ax2`）、交互强调色（`ax3`）以及强调色上的文字（`sp1`） |
| **扩展调色板** | 八种语义色（红、橙、黄、绿、青、蓝、紫、粉），用于进度条、语法高亮、彩色标题和图谱节点 |
| **组件** | 引用、标注块（描边）、复选框（方形、删除线）、代码滚动、嵌入（严格/下划线/隐藏标题）和表格的开关 |
| **排版** | 标题尺寸/字重/变体、正文字体及多种界面字体尺寸 |
| **布局** | 可读行宽、最大宽度和聚焦模式 |
| **配色方案** | 预设方案——Gruvbox、macOS、Nord、Notion、Rosé Pine、Sky、Solarized、Things 和 true-black，亮色与暗色可分别选择 |

每个设置项都分别提供亮色和暗色值，使两种模式保持独立。颜色可以用十六进制（`#rrggbb`）或 HSL 元组粘贴。

## 配色变量

主题在 `body` 中定义了以下基础变量：

| 变量 | 说明 |
| --- | --- |
| `--base-h` | 基础色相 |
| `--base-s` | 基础饱和度 |
| `--base-l` | 基础亮度（100 为纯白） |
| `--accent-h` | 强调色色相 |
| `--accent-s` | 强调色饱和度 |
| `--accent-l` | 强调色亮度 |

亮色与暗色模式分别在 `.theme-light` 与 `.theme-dark` 中覆盖上述变量，并提供完整的 `--color-base-*` 与 `--color-*` 语义色阶。

## 推荐插件

为获得最佳体验，支持以下社区插件：

- **Minimal Theme Settings** —— 快捷键、字体和配色方案预设
- **Style Settings** —— 细粒度的颜色与布局自定义
- **Hider** —— 隐藏界面元素，打造无干扰视图

## 许可证

MIT License

Copyright (c) 2023 Sunflex
