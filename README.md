# Zayia 的个人博客

欢迎来到我个人博客的源代码仓库。此博客托管在 [zayia.github.io](https://zayia.github.io)，是我分享思考、文章和技术探索的空间。

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/Zayia/zayia.github.io/blob/master/LICENSE)
[![Jekyll Version](https://img.shields.io/badge/Jekyll-4.x-brightgreen.svg)](https://jekyllrb.com)
[![Theme](https://img.shields.io/badge/Theme-Type%20on%20Strap-blue)](https://github.com/sylhare/Type-on-Strap)

## 关于本站

这是一个使用 [**Jekyll**](https://jekyllrb.com/) 构建的静态网站。Jekyll 是一个简单、支持博客的静态站点生成器，非常适合用于个人网站和项目。

本站采用了优美而简约的 **"Type on Strap"** 主题，为访客提供了干净、易于阅读的浏览体验。

内容主要包括：
-   个人随笔与思考。
-   技术类文章与教程。
-   一些想法的归档。

## 主要特性

-   **简洁的响应式设计**: "Type on Strap" 主题确保了在桌面电脑、平板和手机上都能获得出色的阅读体验。
-   **基于 Markdown**: 所有文章都使用简单的 Markdown (`.md`) 格式编写，并存放在 `_posts` 目录下。
-   **GitHub Pages 托管**: 网站通过 [GitHub Pages](https://pages.github.com/) 免费托管，并实现自动部署。
-   **Disqus 评论集成**: 文章的评论功能通过 Disqus 平台实现。

## 如何在本地运行

如果你想在自己的电脑上运行这个网站，你需要先安装 Ruby 和 Jekyll 环境。

1.  **克隆仓库:**
    ```bash
    git clone [https://github.com/Zayia/zayia.github.io.git](https://github.com/Zayia/zayia.github.io.git)
    cd zayia.github.io
    ```

2.  **安装依赖:**
    确保你已经安装了 [Bundler](https://bundler.io/) (`gem install bundler`)。然后，在项目根目录下运行以下命令来安装所有必需的 gem 包：
    ```bash
    bundle install
    ```

3.  **启动 Jekyll 服务:**
    ```bash
    bundle exec jekyll serve
    ```

4.  **访问网站:**
    打开你的浏览器并访问 `http://127.0.0.1:4000`。网站应该已经在你的本地成功运行。此时，你对项目文件的任何修改都会被自动检测并重新生成。

## 如何发布新文章

创建一篇新的博客文章非常简单：

1.  进入 `_posts` 文件夹。
2.  按照 Jekyll 的命名规范创建一个新文件：`YYYY-MM-DD-你的文章标题.md`。
3.  在文件的最上方添加所需的 Front Matter（头部信息），例如：
    ```yaml
    ---
    layout: post
    title: "一篇很棒的文章标题"
    date: YYYY-MM-DD HH:MM:SS +0800
    categories: [分类一, 分类二]
    ---
    ```
4.  在头部信息下方，使用 Markdown 语法编写你的正文内容。
5.  将修改提交 (commit) 并推送 (push) 到 `master` 分支。GitHub Pages 会自动重新构建并部署你的网站。

## 许可协议

本项目基于 [MIT](LICENSE) 许可协议开源。

---
*这份 README 文档由 AI 辅助生成。*
