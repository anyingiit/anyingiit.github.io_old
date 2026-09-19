[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:9207d95f61da5b2a -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# anyingiit.github.io_old

本仓库是 anyingiit.github.io 这个 GitHub Pages 站点的一份已归档、已被取代的旧副本，其中只保存了过去某次部署时 Hexo 生成的静态 HTML、CSS 和 JavaScript 输出文件，而不是该站点的源码。

[![License](https://img.shields.io/github/license/anyingiit/anyingiit.github.io_old)](LICENSE)

[提交 Bug](https://github.com/anyingiit/anyingiit.github.io_old/issues/new?template=bug_report.yml) · [提出新功能建议](https://github.com/anyingiit/anyingiit.github.io_old/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">快速开始</a></li>
    <li><a href="#usage">使用方法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

仓库中的每一个页面——`index.html`、`2019/`、`2021/`、`2022/` 目录下按日期归档的文章页面，以及 `archives/` 和 `tags/` 下的每一页——都带有相同的 `<meta name="generator" content="Hexo 5.4.0">` 标签，仓库里同时还带有已经编译好的 `css/main.css`、`js/` 目录下的脚本，以及 `lib/` 目录下的第三方库。这些都是 Hexo 渲染出来的产物，而不是一个可以拿来构建的工程。

`CNAME` 文件记录着 `blog.anyingiit.com`——这份输出过去曾经被部署到的域名。真正生成这些页面所需要的 Hexo 配置、NexT 主题设置和 Markdown 文章源码，都保存在另一个独立的仓库里，并不在这个仓库中——这个仓库从来就只接收过构建完成后的产物，这也是为什么它自己的 `pages build and deployment` 运行记录会失败：本仓库里已经没有任何东西可以让 GitHub Pages 重新构建了。

未来计划的功能和已知问题，请参见[未解决的 Issue 列表](https://github.com/anyingiit/anyingiit.github.io_old/issues)。

## 快速开始

### 前置条件

- 不需要安装任何东西：每一个页面都已经是渲染完成的静态 HTML、CSS 和 JavaScript（例如 `index.html` 和 `css/main.css`），所以任何一款现代浏览器，或者任意一个静态文件服务器，都可以原样把它提供出去。
- 不需要版本控制工具、包管理器或构建工具——这个仓库里根本没有任何清单文件可供它们操作。

### 安装

```sh
git clone https://github.com/anyingiit/anyingiit.github.io_old.git
cd anyingiit.github.io_old
python3 -m http.server 8000
```

然后在浏览器中打开 `http://localhost:8000/` 即可。这里没有依赖需要安装，也没有构建步骤需要执行：仓库里的每一个文件，包括 `index.html`，本身就已经是 Hexo 生成好的最终产物。

## 使用方法

直接在浏览器中打开 `index.html`，或者按上面的方法启动一个静态服务器后访问 `/archives/` 或 `/tags/`，翻阅这份旧文章列表。这里不接受任何命令行参数：它是一份博客的静态快照，而不是一个程序。

## 参与贡献

欢迎任何形式的贡献。如何提交 Issue 或 Pull Request，请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)；参与本项目期望遵守的行为准则，请阅读 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)。

请不要在公开的 Issue 或 Pull Request 中报告安全问题。[SECURITY.md](SECURITY.md) 说明了应该如何私下报告安全问题。

## 许可证

本项目基于 MIT 许可证发布，详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/anyingiit.github.io_old](https://github.com/anyingiit/anyingiit.github.io_old)

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>
