# XiaoyiZhang833.github.io

这是基于本地内容构建的 GitHub Pages 静态站点。仓库名应为 `XiaoyiZhang833.github.io`，GitHub 会直接把该仓库的 `main` 分支根目录作为用户名页面予以托管。

快速步骤（可复制到终端执行）：

- 推荐（使用 `gh` CLI，并已授权）
```bash
gh repo create XiaoyiZhang833/XiaoyiZhang833.github.io --public --source=. --remote=origin --push
```

- 手动在 GitHub 网站创建仓库后（仓库名为 `XiaoyiZhang833.github.io`），在本地执行：
```bash
git remote add origin https://github.com/XiaoyiZhang833/XiaoyiZhang833.github.io.git
git branch -M main
git push -u origin main
```

说明：
- 若仓库为 `XiaoyiZhang833.github.io`，GitHub Pages 会自动以 `https://XiaoyiZhang833.github.io` 提供页面（无需额外配置），推送到 `main` 分支后通常几分钟即可生效。
- 如果需要自定义域名或 HTTPS，登录 GitHub 仓库页面 → Settings → Pages 进行配置。

文件说明：
- 网站主页面：[index.html](index.html)
- 中文页面：[zh.html](zh.html)
- 资源目录：[assets/](assets/)

如需我代替你执行 `gh repo create` 并推送（需要你在本机已登录 `gh`），我可以继续执行。