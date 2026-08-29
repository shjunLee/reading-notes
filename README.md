# 阿玉王的读书笔记 📚

读一本，留一本书的痕迹。这里记录我读过的书——重点是**认知、决策与成长**，每本笔记都包含核心框架拆解、认知偏误卡片、金句摘录，以及我自己的划线与想法。

## 在线阅读

**👉 https://shjunlee.github.io/reading-notes/**

## 书目

| 书名 | 作者 | 笔记 | 链接 |
|---|---|---|---|
| 《思考，快与慢》 | 丹尼尔·卡尼曼 | 38 条（3 划线 + 35 想法） | [阅读笔记](https://shjunlee.github.io/reading-notes/books/thinking-fast-and-slow.html) |

## 结构

```
├── index.html                          # 首页 · 书架导航（卡片与「已读完」统计由 JS 动态生成）
├── books/
│   ├── manifest.json                   # 书目清单：首页统计与卡片的数据源
│   └── thinking-fast-and-slow.html     # 《思考，快与慢》
└── README.md
```

每本书的页面都是**单文件、自包含**（图片 base64 内嵌），无外部依赖，可直接下载离线阅读。

## 新增一本书

1. 把新书笔记页（自包含 HTML）放进 `books/`，文件名用英文 slug，例如 `books/xxx.html`
2. 在 `books/manifest.json` 数组里加一条：
   `{"slug":"xxx","emoji":"📘","title":"书名","author":"作者","en":"英文名","desc":"一句话简介","notes":N,"tags":["标签1","标签2"]}`
3. 提交并推送：`git add -A && git commit -m "新增《xxx》" && git push`

首页的书架卡片和「已读完」统计会**自动**更新，无需手动改数字。

## 笔记来源

书页中的「我的划线与想法」部分来自我在微信读书中的真实批注。

---

*持续更新中 · 下一本书正在路上*
