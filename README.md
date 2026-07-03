# 深圳吃喝玩乐推荐

原生 Markdown + GitHub Pages，无前端工程、无后端、无运行费用。页面采用简洁的文档主题，打开后直接显示攻略正文，不显示“View the project”。

正文在 `index.md`，GitHub Pages 会使用 `_config.yml` 中指定的免费文档主题自动渲染。

## Markdown 文档管理

- `index.md`：当前首页及游玩攻略正文。
- `_config.yml`：网站名称、搜索、返回顶部等全局配置。
- 后续可在根目录增加 `吃.md`、`住.md` 等文档。
- 每份新增文档顶部添加以下信息，就会自动出现在左侧目录：

```yaml
---
title: 吃
layout: default
nav_order: 2
---
```

只需要编辑 Markdown 并推送，GitHub Pages 会自动重新发布。

## 免费发布

1. 在 GitHub 新建公开仓库，例如 `shenzhen-guide`。
2. 将本目录文件推送到仓库根目录。
3. 打开 `Settings → Pages`。
4. `Source` 选择 `Deploy from a branch`。
5. 分支选择 `main`，目录选择 `/ (root)`，保存。

发布地址通常是：`https://你的用户名.github.io/shenzhen-guide/`
