# Creeper998 Projects

使用原生 Markdown 管理的个人项目展示页，通过 GitHub Pages 免费发布。

## 文档管理

- `index.md`：项目展示首页。
- `_config.yml`：网站标题、搜索和主题配置。
- 新项目可以直接在 `index.md` 中增加一个二级标题。
- 如需为项目编写独立详情页，可新建 Markdown 文件并添加：

```yaml
---
title: 项目名称
layout: default
nav_order: 2
---
```

提交并推送到 `main` 后，GitHub Pages 会自动更新。
