# 个人博客

基于 Jekyll + GitHub Pages 的静态博客。

## 快速开始

### 1. 上传到 GitHub

1. 在 GitHub 创建一个新仓库，命名为 `yourusername.github.io`
2. 将所有文件上传到该仓库
3. 进入仓库 **Settings → Pages**，确保 Source 设置为 "Deploy from a branch"，分支选择 `main`
4. 等待几分钟，访问 `https://yourusername.github.io` 即可看到博客

### 2. 本地预览（可选）

```bash
# 安装 Jekyll
gem install bundler jekyll

# 进入博客目录
cd yourusername.github.io

# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve

# 访问 http://localhost:4000
```

### 3. 写作

在 `_posts` 目录下创建新文件，文件名格式：`YYYY-MM-DD-标题.md`

```markdown
---
layout: post
title: "文章标题"
date: 2026-04-27 12:00:00 +0800
categories: 分类名
tags: [标签1, 标签2]
---

文章内容，支持 Markdown 语法...
```

### 4. 自定义

- 修改 `_config.yml` 配置站点信息
- 修改 `assets/css/style.css` 调整样式
- 修改 `_layouts/` 下的文件调整页面结构

## 目录结构

```
.
├── _config.yml          # 站点配置
├── _layouts/            # 页面模板
│   ├── default.html     # 默认布局
│   └── post.html        # 文章布局
├── _posts/              # 博客文章
│   ├── 2026-04-27-欢迎来到我的新博客.md
│   └── 2026-04-26-Markdown-写作指南.md
├── assets/
│   └── css/
│       └── style.css    # 自定义样式
├── about.md             # 关于页面
├── index.md             # 首页
└── README.md            # 本文件
```

## 技术栈

- [Jekyll](https://jekyllrb.com/) - 静态网站生成器
- [GitHub Pages](https://pages.github.com/) - 免费托管
- Markdown - 内容写作

## License

MIT
