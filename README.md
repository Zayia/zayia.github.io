# zayia.github.io

Zayia 的个人主页：<https://zayia.github.io>

## 这是什么

一个**零依赖的单页静态站点**——没有构建步骤、没有框架、没有外部 CDN 和字体请求，
只有一个 `index.html`（内联 CSS + 一行脚本），打开就能用。

- 深色 / 浅色主题跟随系统（`prefers-color-scheme`）
- 移动端自适应，`prefers-reduced-motion` 时关闭动效
- 无追踪、无 Cookie、无第三方脚本

## 目录

```
.
├── index.html          # 首页（样式内联，单文件）
├── 404.html            # 自定义 404
├── robots.txt
├── sitemap.xml
├── images/
│   └── avatar.jpg      # 头像
└── legacy/             # 2017 年的旧版站点（HTML5 UP "Dimension" 模板），仅作归档
```

`legacy/` 里的旧站仍然可以直接打开（`legacy/index.html`），但首页已经换成新版，
里面的外链（z5wl.com 等）多数已失效，保留只是为了留念。

## 本地预览

```bash
python3 -m http.server 8000
# 打开 http://127.0.0.1:8000
```

## 部署

GitHub Pages 直接从 `master` 分支根目录发布，推送即生效（通常 1 分钟内）。

## 改内容

| 想改什么 | 改哪里 |
| --- | --- |
| 头像 | 替换 `images/avatar.jpg` |
| 自我介绍 | `index.html` 里 `.hero .bio` |
| 项目卡片 | `index.html` 里 `section` → `.grid`，一个 `<a class="card">` 一张卡 |
| 技术栈 | `index.html` 里 `.chips` 的 `<li>` |
| 主题色 | `index.html` 顶部 `:root` 里的 `--accent` |

## 许可

页面代码 MIT；`legacy/` 里的模板来自 [HTML5 UP](https://html5up.net/)（CCA 3.0）。
