# Aseprite 简体中文汉化指南

> 本文档提供 Aseprite 云端编译产物的简体中文汉化方法及常见问题解决方案。

## 快速开始

### 1. 下载汉化文件

从本仓库的 [`extensions/`](https://github.com/chenhaolove89/aseprite-builder/tree/main/extensions) 目录下载以下文件：

| 文件名 | 说明 | 适用平台 |
|---|---|---|
| [`hanhua-1.2.23.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/hanhua-1.2.23.aseprite-extension) | 简体中文语言包 | 全平台 |
| [`zhuti-Win.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/zhuti-Win.aseprite-extension) | Windows 常规字体主题 | Windows |
| [`zhuti-xiangsu.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/zhuti-xiangsu.aseprite-extension) | 像素字体主题（备用） | 全平台 |

> 语言包版本对应 Aseprite v1.2.23，但通常兼容 v1.3.x 版本。

### 2. 安装汉化包

1. 打开 Aseprite
2. 菜单栏选择 **编辑(Edit) > 首选项(Preferences)**（或按 `Ctrl+K`）
3. 左侧选择 **扩展(Extensions)**
4. 点击 **添加扩展(Add Extension)** 按钮
5. 选择 `hanhua-1.2.23.aseprite-extension` 文件
6. 重启 Aseprite

### 3. 安装主题包（必须！否则中文显示为方框）

1. 打开 Aseprite
2. 菜单栏 **编辑 > 首选项 > 扩展**
3. 点击 **添加扩展**，选择 `zhuti-Win.aseprite-extension`
4. 重启 Aseprite

### 4. 切换语言和主题

1. 菜单栏 **编辑 > 首选项 > 常规(General)**
2. **语言(Language)** 下拉框选择 **Simplified Chinese**
3. 左侧切换到 **主题(Theme)**
4. 在列表中找到 **Aseprite-theme-nomal**
5. **选中它，然后点击下方的 "选择(Select)" 按钮**（关键步骤！）
6. 点击 **确定(OK)**
7. 重启 Aseprite

## 常见问题

### Q1: 安装语言包后界面还是英文？
- 确认在 **编辑 > 首选项 > 常规 > 语言** 中选择了 **Simplified Chinese**
- 修改后需要重启 Aseprite

### Q2: 中文显示为方框/乱码？
**原因**：只安装了语言包，没有安装/选择中文主题包。Aseprite 默认字体不支持中文。

**解决**：
1. 确保已安装 `zhuti-Win.aseprite-extension` 主题包
2. 在 **编辑 > 首选项 > 主题** 中选择 **Aseprite-theme-nomal**，点击 **Select** 按钮
3. 重启 Aseprite

### Q3: 主题包安装后仍乱码？
- 尝试安装备用主题包 `zhuti-xiangsu.aseprite-extension`（像素字体主题）
- 确保系统安装了常见中文字体（如微软雅黑、宋体）

### Q4: 扩展安装失败？
- 确认下载的文件完整（未被浏览器拦截或损坏）
- 尝试重新下载并安装
- 如安装过旧版本，先在 **首选项 > 扩展** 中删除旧扩展再重新安装

## 参考链接

- 汉化项目源码: https://github.com/J-11/Aseprite-Simplified-Chinese
- Aseprite 官方文档: https://aseprite.org/docs
