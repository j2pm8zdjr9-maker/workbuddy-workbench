# 个人工作台 / Personal Workbench

一个**单文件**（zero-dependency）的纯前端个人工作台，涵盖打卡、待办、工作留痕、身体管理、影剧书、日程、日记、财务记账、备考、宝宝成长、物品管理、纪念日、愿望清单、家人/宠物档案等模块。

## 特性

- 单文件 `index.html`，无需构建、无需后端，双击即可打开
- 数据保存在浏览器 `localStorage`（含同步兼容旧版键名）
- 首页总览可自由配置统计面板（单条显隐 + 每行占 1/2/4 格）
- 设置项丰富：主题、字号、统计面板、分类管理等

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 部署

已通过 GitHub Pages 发布（见仓库 Settings → Pages）。

## 添加到手机主屏幕（PWA / 网页 APP）

iOS Safari：打开网址 → 底部「分享」 → 滑到「添加到主屏幕」→ 确认。会自动用 `apple-touch-icon.png`（180×180）作为图标。
Android Chrome：右上角菜单 → 「添加到主屏幕」/「安装应用」。会自动用 `icon-192.png` / `icon-512.png`，并以 `manifest.json` 启动为全屏 standalone 模式。

## 目录结构

```
index.html               主程序（全部 HTML/CSS/JS 内联）
apple-touch-icon.png     iOS 主屏图标（180×180）
icon-192.png             PWA 标准图标（192×192）
icon-512.png             PWA 大图标（512×512）
icon-maskable-512.png    PWA 安全边距版（512×512，适用于部分启动器）
manifest.json            PWA 清单（name / icons / theme_color / start_url）
.nojekyll                关闭 GitHub Pages 的 Jekyll 处理
```
