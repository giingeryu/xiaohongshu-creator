---
name: kitchen-compile
description: Kitchen Wiki 食谱编译 - 扫描 01.raw/ 新文件，自动分类归档，增量编译更新 02.wiki
---

# kitchen-compile

扫描 Kitchen Wiki 的 01.raw/ 根目录，对新食谱进行分类归档，并增量编译更新 02.wiki。

## 使用方法

```
/kitchen-compile
```

## 功能

- 扫描 01.raw/ 根目录下未处理的文件
- 自动判断分类（recipes / ingredients / techniques / misc）
- 生成结构化 wiki 条目，更新 02.wiki/
- 更新 02.wiki/recipes/index.md 索引
- 更新 .manifest.json 记录处理历史

## 前置要求

- Kitchen Wiki vault 路径：`~/Library/Mobile Documents/iCloud~md~obsidian/Documents/Kitchen Wiki`
