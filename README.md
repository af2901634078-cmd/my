# 李飞 · 个人网站（3D 小房间）

一个单文件的 3D 场景个人网站：访客走进一个海上厨房，房间里每件东西对应网站的一个板块。

- **纯静态**：不需要构建、不需要 npm、没有后端
- **入口**：`index.html`（全部内容都在这一个文件里）
- `vendor/`：three.js 3D 引擎（本地副本，离线也能load）
- `media/`：照片压缩后的版本
- `.nojekyll`：告诉 GitHub Pages 不要跑 Jekyll，原样发布

## 部署到 GitHub Pages

1. 把本文件夹里的**全部内容**上传到仓库根目录
2. 仓库 → Settings → Pages
3. Source 选 `Deploy from a branch`，Branch 选 `main`，目录选 `/ (root)`，保存
4. 等 1–2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`

## 本地预览

双击 `index.html` 即可，完整 3D 效果都能正常显示。
