# Sunflex

Sunflex 是一款 Obsidian 主题，将 Sunflex 配色方案转换为 Obsidian 原生颜色变量，可直接作为独立主题使用。

## 截图

![Sunflex 主题截图](screenshot.png)

## 主题特性

- 基于 Sunflex 配色方案，提供舒适的阅读与写作体验
- 支持亮色（Light）与暗色（Dark）两种模式
- 内置 true-black 暗色变体（通过 `minimal-dark-black` 或 `black` 类启用）
- 色彩调色板涵盖红、橙、黄、绿、青、蓝、紫、粉八种语义色

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

## 安装方式

1. 将整个 `Sunflex` 文件夹放入 Obsidian 仓库的 `.obsidian/themes/` 目录下
2. 打开 Obsidian 设置 → 外观 → 主题，选择 **Sunflex**

## 许可证

MIT License

Copyright (c) 2023 Sunflex
