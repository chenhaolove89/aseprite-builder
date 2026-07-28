# aseprite-builder

Build Aseprite using Github action

# What should you do?
- fork this repo
- **enable workflow `Build and release Aseprite` in `Actions -- Workflows`**
- click `Action > Build and release Aseprite > run workflow` as the figure shows
  ![trigger the workflow](https://github.com/user-attachments/assets/5174f407-4daf-4e28-996e-5efb4f8751cb)
  
- now you should see the building process via `Actions` and you can find the product in `Release`

accroding to [Eula](https://github.com/aseprite/aseprite/blob/main/EULA.txt) :

> (b) Distribution.
> 
> You may not distribute copies of the SOFTWARE PRODUCT to third parties. Evaluation versions available for download from the Licensor's websites may be freely distributed.

we need to remove the product in `Releases` .

# Aseprite 简体中文汉化

本仓库同时提供 Aseprite 简体中文汉化所需的语言包和主题包，位于 [`extensions/`](https://github.com/chenhaolove89/aseprite-builder/tree/main/extensions) 目录。

## 资源列表

| 文件 | 说明 |
|---|---|
| [`extensions/hanhua-1.2.23.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/hanhua-1.2.23.aseprite-extension) | 简体中文语言包 |
| [`extensions/zhuti-Win.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/zhuti-Win.aseprite-extension) | Windows 常规字体主题 |
| [`extensions/zhuti-xiangsu.aseprite-extension`](https://github.com/chenhaolove89/aseprite-builder/raw/main/extensions/zhuti-xiangsu.aseprite-extension) | 像素字体主题（备用） |

## 详细汉化步骤

请参阅 [`docs/Chinese-Localization.md`](https://github.com/chenhaolove89/aseprite-builder/blob/main/docs/Chinese-Localization.md)，其中包含：

- 快速开始指南
- 常见问题解决方案（如中文显示为方框/乱码）
- 文件说明与版本兼容信息

# Aseprite 学习指南

如果你是像素画新手，推荐阅读 [`docs/Aseprite-Learning-Guide.md`](https://github.com/chenhaolove89/aseprite-builder/blob/main/docs/Aseprite-Learning-Guide.md)，内含：

- Aseprite 基础操作与快捷键
- 像素画核心知识（线条、明暗、抖动、调色板）
- 临摹学习方法与推荐素材网站
- 30天练习计划
