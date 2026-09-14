# 单小航的个人主页

这是一个零依赖的静态个人主页，内容位于 `dist/`，可直接部署到 Cloudflare Pages 或 GitHub Pages。

## 修改内容

- 页面文字：编辑 `dist/index.html`
- 视觉样式：编辑 `dist/assets/styles.css`
- 页面交互：编辑 `dist/assets/main.js`
- 个人照片：替换 `dist/assets/personal-photo.jpg`，建议保留竖版比例

当前页面仅公开学校、研究方向和邮箱。手机号、出生年月等个人隐私信息未写入公开页面。

## Cloudflare Pages

连接 GitHub 仓库后，构建命令留空，输出目录填写 `dist`。之后每次推送到默认分支都会自动发布。

## GitHub Pages

仓库已经包含 `.github/workflows/pages.yml`。在仓库的 **Settings → Pages** 中将 Source 设为 **GitHub Actions**，推送到 `main` 分支后即可发布。

