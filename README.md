# hex.school · AI Native 课程笔记

单文件电影级叙事网页版课程笔记，每课一页 HTML，双击即看，零构建零依赖（CDN）。

在线阅读：**https://hexingxiang.github.io/hex/**

> 原版课程：**ha7ch.school** — 本仓库是 hex 的学习笔记版，品牌已换成 hex.school，内容忠于原讲义。

## 课程表

| 课 | 主题 | 链接 |
|---|---|---|
| 第 1 课 | 零 Token 设计（Zero-Token Design） | [01.html](https://hexingxiang.github.io/hex/01.html) |
| 第 2 课 | ChatGPT 之后，活儿怎么变 | 敬请期待 |

## 文件结构

```
01.html                     第 1 课单文件页面（交互模式直接打开；加 ?capture=1 为静态截图模式）
assets/lesson-01-full.png   第 1 课全页长图（1440×11495）
assets/lesson-01-hero.png   第 1 课首屏图（1440×900）
```

## 技术说明

- 单 HTML 文件：Tailwind CDN + three.js r128 立方体背景 + Web Audio 合成 BGM
- 六幕叙事结构：开场门 → 逐幕滚动揭示 → 每幕一个交互 widget → 结账压轴
- 截图模式：URL 加 `?capture=1`（或无头浏览器访问），所有交互呈完成态、跳过开场门
- 原文出处：Lawted, *Zero-Token Design*（2026-05-07）

---
HEX.SCHOOL · AI NATIVE 学习笔记 · 原版 HA7CH.SCHOOL
