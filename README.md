# 把你的GoreBox gbmap转换成工程文件
## 简介 (Chinese)
这是一个前端静态页面，可以在浏览器中将 GoreBox 的 .gbmap 文件（FGMTP V1/V2）批量转换为工程文件（ProjectFile.json + MapData.json），并打包下载。界面有中/英双语支持。

## Overview (English)
A static web page that converts GoreBox .gbmap files (FGMTP V1/V2) into project files (ProjectFile.json + MapData.json) in-browser, with bilingual Chinese/English UI. Exports results as a ZIP.

---

## 部署 (Deployment)
推荐三种方式 / Three easy ways:

1. GitHub Pages（免费）
   - 在 GitHub 仓库中上传本项目文件。
   - 进入 Settings -> Pages，选择 main 分支 / root 目录即可启用。
   - 网站会发布到： https://<用户名>.github.io/gorebox-gbmap-converter/

2. Netlify（拖拽或 Git 集成）
   - 直接拖入静态文件夹或连接 Git 仓库自动部署。

3. Vercel（零配置）
   - 连接仓库后，选择静态站点即可自动部署。

---

## 使用说明 (Usage)
- 打开页面 → 选择或拖拽 .gbmap 文件 → 点击 "开始转换" / "Convert" → 转换完成后点击 "下载全部" / "Download All" 保存 ZIP。
- 支持同时添加多个 .gbmap 文件，支持 V1 与 V2 自动识别。

---

## 说明 (Notes)
该项目是纯前端静态网站，无需后端服务，适合直接部署到 GitHub Pages、Netlify 或 Vercel。
