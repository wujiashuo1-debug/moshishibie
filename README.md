# 现代模式识别刷题网站｜最终稳定单文件版

重新建仓库用这个版本。核心只有一个 `index.html`，题库、解析、样式、逻辑全部内联。

## 上传方式

新建 GitHub 仓库后，只需要把 `index.html` 上传到仓库根目录。README 可传可不传。

Settings → Pages：

- Source: Deploy from a branch
- Branch: main
- Folder: / root

等 Actions 变绿即可访问。

## 特点

- 150 道题：100 道单选 + 50 道多选。
- 每道题都有简短解析。
- 不使用 Service Worker，不会被旧 PWA 缓存干扰。
- 不依赖 questions.js、app.js、style.css，不会出现题库加载 0 的问题。
