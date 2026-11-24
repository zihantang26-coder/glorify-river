# Glorify · River 版本册（V1 / V2 / V3）

这个文件夹是一个纯静态网站，不需要安装任何东西。

- `index.html`：版本册首页，顶部切换 V1 / V2 / V3
- `v1/`：V1 · Soft light（现有美术，来自 river-prototype 的构建）
- `v2/`：V2 · 梦境河谷（Soul 柔焦）
- `v3/`：V3 · 纸上的河（手绘插画）

## 部署（任选一种，约 1 分钟）

**Netlify Drop（最简单）**
1. 打开 https://app.netlify.com/drop
2. 把整个 `Glorify-River-Versions` 文件夹拖进页面
3. 得到一个 `https://xxx.netlify.app` 的网址

**Vercel**：在 vercel.com 新建项目，选择 “Deploy without Git / Upload”，上传这个文件夹。

**GitHub Pages**：把文件夹内容推到一个仓库，在 Settings → Pages 里选择分支即可。

## 在 iPhone 上像 App 一样看

1. 用 **Safari** 打开部署后的网址
2. 点底部 “分享” → “添加到主屏幕”
3. 从主屏幕的 River 图标打开：全屏、没有地址栏

在手机上 V2 / V3 会自动进入全屏模式（去掉手机外框和说明面板）。
单独打开某个版本时，可在网址后加 `?frame` 强制显示手机外框，或加 `?full` 强制全屏。

## 注意

- 部署后任何拿到网址的人都能打开；演示里的日期、日记和情绪都是虚构数据。
- V2 / V3 的衬线字体从 Google Fonts 加载，需要联网；Tiempos / Helvetica Now 为商业字体，未打包，会显示替代字体。
- 不要直接在手机“文件”App 里打开 HTML，iOS 的预览不会运行页面里的代码。
- 本地预览：在这个文件夹里运行 `python3 -m http.server`，再打开 http://localhost:8000
