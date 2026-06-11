# 自媒体一人公司主站

基于 Jekyll 构建，部署于 GitHub Pages，域名映射访问。

## 目录结构

```
company-website/
├── _config.yml          # Jekyll 配置
├── _layouts/            # 页面模板
├── _pages/              # 页面（关于、已发表、主题页）
├── _posts/              # 已发布文章
├── assets/css/          # 样式
└── assets/js/           # 脚本
```

## 写作规范

每篇文章放在 `_posts/` 目录，文件名格式：

```
YYYY-MM-DD-文章标题.md
```

文章头部 front matter：

```yaml
---
layout: post
title: 文章标题
date: 2026-06-11
topic: ETF投资 / 中医健康 / AI创作
platforms: [公众号, 小红书, B站]
excerpt: 文章摘要
---
```

## 本地预览

```bash
bundle install
bundle exec jekyll serve
```

## 部署

推送到 GitHub 后自动通过 GitHub Pages 发布。

