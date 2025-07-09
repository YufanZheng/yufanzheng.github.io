# Yufan Zheng 个人主页 / Personal Homepage

本项目为 [Yufan Zheng](https://yufanzheng.github.io/index.html) 的个人学术主页，基于 HTML + CSS + JavaScript，支持 Markdown 内容动态加载，便于维护和扩展。

This project is the personal academic homepage of [Yufan Zheng](https://yufanzheng.github.io/index.html), built with HTML, CSS, and JavaScript. It supports dynamic loading of Markdown content for easy maintenance and extension.

---

## 使用方式 / How to Use

### 1. Fork 本仓库 / Fork this repository

点击右上角的 **Fork** 按钮，将本项目 Fork 到你的 GitHub 账号下。
Click the **Fork** button at the top right to fork this project to your own GitHub account.

### 2. 修改 `sections` 文件夹下的内容 / Edit files in the `sections` folder

在你的仓库中，进入 `sections` 文件夹，编辑或替换其中的 markdown 文件（如 `home.md`、`research.md` 等），即可自定义主页各个板块的内容。
Go to the `sections` folder in your repository and edit or replace the markdown files (such as `home.md`, `research.md`, etc.) to customize the content of each section of your homepage.

### 3. 启用 GitHub Pages / Enable GitHub Pages

在你的仓库设置（Settings）中，找到 **Pages**，选择分支为 `main`（或 `master`），目录为 `/root`，保存。参考github.io的[网页](https://pages.github.com/)。
In your repository settings, find **Pages**, select the branch as `main` (or `master`), and the folder as `/root`, then save. Please find more details on [github.io's website](https://pages.github.com/).

### 4. 访问你的主页 / Visit your homepage

几分钟后，你可以通过 `https://你的用户名.github.io` 访问你的个人主页。
After a few minutes, you can visit your homepage at `https://your-username.github.io`.

---

你只需 fork、改 markdown、开启 Pages 即可拥有自己的学术主页，无需写代码！
Just fork, edit markdown, enable Pages, and you’ll have your own academic homepage—no coding required!

## 本地预览 / Local Preview

**请使用本地服务器，否则 fetch 无法加载 markdown 文件。**
**Please use a local server. Otherwise, fetch cannot load markdown files.**

### Method: VS Code Live Server

1. 安装 [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) 插件。
2. 右键 `index.html`，选择“Open with Live Server”。
 
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension.
2. Right-click `index.html` and choose "Open with Live Server".
---

## 修改内容 / Edit Content

- 编辑 `sections/` 目录下的 markdown 文件即可更新主页内容。
- 如需调整样式，可修改 `index.html` 中的 `<style>` 部分或 `css/w3.css`。
- Edit markdown files in the `sections/` directory to update homepage content.
- To adjust styles, edit the `<style>` section in `index.html` or `css/w3.css`.

---

## 参考/致谢 / Reference & Credits

- 页面部分样式和结构参考自 [Yunhe Wang 的主页](https://github.com/YunheWang/HomePage) 和 [photo-gallery-img-template](https://github.com/singhofen/photo-gallery-img-template)。
- Markdown 渲染使用 [marked.js](https://github.com/markedjs/marked)。
- Some styles and structures are inspired by [Yunhe Wang's homepage](https://github.com/YunheWang/HomePage) and [photo-gallery-img-template](https://github.com/singhofen/photo-gallery-img-template).
- Markdown rendering uses [marked.js](https://github.com/markedjs/marked).

---

如有问题欢迎 issue 或 PR！
Feel free to open an issue or PR if you have any questions!
