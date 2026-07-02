# 现代模式识别刷题网站｜公式渲染单文件版

这个版本只需要上传 `index.html` 即可使用。

特点：
- 150 道现代模式识别题库内置
- 每题包含简短解析
- 支持电脑端与手机端
- 不依赖 questions.js / app.js / style.css
- 不使用 Service Worker，避免旧缓存导致题库变 0
- 已接入 MathJax，支持渲染 LaTeX 公式，例如 `$P(\omega_i|x)$`、`$\frac{c(c-1)}{2}$`、`$S_w^{-1}S_b$`

部署方法：
1. 新建 GitHub 仓库。
2. 只上传 `index.html`。
3. Settings → Pages → Deploy from a branch → main / root。
4. 等 GitHub Pages 部署完成后访问网址。

注意：公式渲染使用 MathJax CDN。正常联网访问 GitHub Pages 时会自动加载。
