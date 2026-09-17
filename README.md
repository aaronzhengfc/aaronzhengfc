# Aaron Zheng 的静态博客

这是本人的静态博客，基于 Jekyll 和 Chirpy 主题搭建，用于记录与分享个人文章。

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
