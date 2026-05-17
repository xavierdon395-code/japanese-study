# 森林里的日语小屋 · JLPT 单词学习网页

一个面向日语学习者的 JLPT 词汇学习 Web 应用。项目以森林小屋为视觉主题，提供轻量、治愈、可持续使用的学习体验：你可以通过翻牌记忆进行词汇训练，记录“认识 / 不认识”，管理收藏词条，查看学习进度，并在本地持久化保存学习状态。登录 Google 账号后，支持基于 Firebase Realtime Database 的云端同步，在多设备间延续学习进度。右下角小松鼠吉祥物与互动气泡也为学习过程提供了陪伴感。

## 在线访问

- 在线体验：`https://xavierdon395-code.github.io/japanese-study/`

> 若仓库 GitHub Pages 地址后续调整，请以仓库 Pages 实际配置为准。

## 功能特点

- 支持 JLPT `N1 / N2 / N3 / N4 / N5` 词库学习
- 支持 `N4+N5` 合并学习与全部词库混合学习
- 单词卡片翻牌学习，正反面展示日语词条与释义/读音等信息
- “认识 / 不认识”学习反馈机制，辅助记忆强化
- 收藏单词功能，便于后续定向复习
- 学习进度与答题数据统计（含阶段结果展示）
- 基于 `localStorage` 的本地学习状态持久化
- Google 登录后支持 Firebase Realtime Database 云端同步
- 右下角小松鼠吉祥物与气泡互动，提升学习陪伴感
- 响应式网页设计，兼容电脑与手机浏览器

## 技术栈

- HTML5
- CSS3
- JavaScript
- JSON 词库数据
- LocalStorage
- Firebase Authentication
- Firebase Realtime Database
- GitHub Pages

## 项目结构

```bash
japanese-study/
├── index.html
├── squirrel.png
├── words_n1.json
├── words_n2.json
├── words_n3.json
├── words_n4.json
├── words_n5.json
└── README.md
```
