# Hi, I'm Aaron 👋

一名写 Java 的开发者，曾在互联网大厂搬砖，也会写一点 Swift。

- ☕ **Java** · 我的主力语言。
- 🍎 **Swift** · 会写一点，还在慢慢探索。
- 🛠️ **经历** · 曾在互联网大厂从事开发工作。
- ✍️ **博客** · 在 [SightCorner · 视角](https://sightcorner.com/) 记录技术与生活。


---

<details>
<summary>关于这个仓库 · 博客本地运行指南</summary>

这是本人的静态博客源码，基于 Jekyll 和 Chirpy 主题搭建，同时用作 GitHub 个人主页介绍。

## 本地启动

在 IntelliJ IDEA 底部的 Terminal 或 macOS 终端中执行：

```bash
cd ~/Documents/github/aaronzhengfc
export PATH="/opt/homebrew/opt/ruby/bin:$PATH"
bash tools/run.sh
```

以上路径适用于当前 Mac：项目位于 `~/Documents/github/aaronzhengfc`，Ruby 使用 Homebrew 安装的版本。如果项目位置不同，请调整 `cd` 路径。

首次运行或提示缺少依赖时，先在项目目录执行：

```bash
bundle install
```

启动成功后，在浏览器打开 [本地博客](http://127.0.0.1:4000/)。

- 保持启动服务的终端运行。
- 修改文章后，Jekyll 会自动重新生成页面，并通过 LiveReload 刷新浏览器。
- 按 `Ctrl+C` 停止服务。

## 写文章

文章保存在 `_posts` 目录中，文件名使用 `YYYY-MM-DD-文章标题.md` 格式。

</details>
