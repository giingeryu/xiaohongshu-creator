---
name: meal-plan
description: 一周餐饮规划 - 基于 Kitchen Wiki 生成周餐计划和购物清单
---

# meal-plan

基于 Kitchen Wiki 中已有的食谱，生成一周餐饮计划，并自动汇总购物清单。

## 使用方法

```
/meal-plan
```

## 功能

- 读取 02.wiki/recipes/ 中的食谱
- 生成一周早/午/晚餐计划
- 考虑食材复用、难度均衡、营养多样
- 自动汇总购物清单
- 保存到 03.plans/[YYYY-WW].md

## 前置要求

- Kitchen Wiki vault 路径：`~/Library/Mobile Documents/iCloud~md~obsidian/Documents/Kitchen Wiki`
