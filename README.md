# GitHub Pages 部署说明

这是一个不依赖框架的最小静态博客骨架，适合先把 `fuurinko.github.io` 接管回来。

## 用法

1. 新建或接管 GitHub 仓库：

   - 仓库名必须是 `fuurinko.github.io`

2. 将当前目录中的这些文件推到仓库根目录：

   - `index.html`
   - `posts.html`
   - `about.html`
   - `404.html`
   - `styles.css`

3. 打开 GitHub 仓库设置：

   - `Settings` -> `Pages`

4. 在 `Build and deployment` 中选择：

   - `Source: Deploy from a branch`
   - `Branch: main`
   - `/ (root)`

5. 保存后，等待 GitHub Pages 发布。

## 当前版本的定位

这个版本先解决：

- 原 URL 可以重新访问
- 有首页、文章入口、关于页和 404 页
- 后续可以逐步替换成更完整的博客系统

## 后续建议

1. 为文章生成真实页面，并把链接补到 `posts.html`
2. 如果想要更强的内容管理，再迁移到 Astro / Hugo
3. 为旧博客路径补静态跳转页
