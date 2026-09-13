# 狼人杀 · SCARLET WITCH edition

纯静态网站，无需安装依赖或构建。包含全部六张卡图及自定义角色数量功能。

## 部署到 GitHub Pages

1. 解压压缩包。
2. 将 index.html、style.css、app.js 和 assets 文件夹上传到 GitHub 仓库根目录，保持目录结构。不要只上传 ZIP 文件，也不要套一层文件夹。
3. 在仓库 Settings → Pages 中，Source 选择 Deploy from a branch。
4. Branch 选择 main，目录选择 / (root)，点击 Save。
5. 等待 GitHub Pages 完成部署，从 Pages 页面打开网站链接。

.nojekyll 可一同提交；本项目不使用 Jekyll 特性。

官方说明：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 使用

设置每种角色数量后，点击“应用配置 · 开始新一轮”。每种角色可为 0–30，总人数为 1–60。轮流抽牌、查看并收起身份，再交给下一位。

本网站适合同一设备轮流抽牌；没有联机房间或服务器。刷新页面会重置当前牌局。
