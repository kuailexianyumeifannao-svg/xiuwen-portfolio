# 秀雯作品集 · 整理版

这是可直接部署的静态网站发布文件，保留原有页面、项目顺序、交互、项目图片及演示视频。

## 文件目录

| 路径 | 内容 |
|---|---|
| index.html | 网站首页入口 |
| assets/js/app.js | 网页交互程序 |
| assets/css/style.css | 页面样式 |
| assets/images/common/ | 首页、公共卡片与联系区域图片 |
| assets/projects/xiaoai_memory/ | 小爱记忆项目图片 |
| assets/projects/xiaolai_claw/ | 小来项目图片 |
| assets/projects/lemon_decompression/ | 柠檬解压项目图片 |
| assets/projects/technova_bduan/ | Technova B 端项目图片 |
| assets/projects/wuyouhuan/ | 无忧环项目图片 |
| assets/projects/ip_design/ | IP 设计项目图片 |
| assets/projects/vibe_coding/ | Vibe Coding 项目图片 |
| assets/projects/cursor/ | Cursor 项目图片 |
| assets/projects/zaojing/ | 藻井集图片和 demo.mp4 演示视频 |
| _redirects | Netlify 路由配置 |
| .nojekyll | GitHub Pages 静态文件标记 |

## 本次整理

删除了 13 张未被代码引用的旧公共图片。按编号动态加载的项目图片均已保留。
部分公共 PNG 转为无损 WebP，保留原分辨率、透明度，逐像素校验相同。
更新了资源路径，采用相对路径，可部署到域名根目录或 GitHub Pages 仓库子目录。
原压缩包为已构建文件，不包含 React 等开发工程源码；app.js 是编译后的发布程序。

## 部署方法

先解压本 ZIP，将 index.html 和 assets 等同层内容上传到仓库根目录，不能只上传 ZIP。
GitHub Pages 设置：Settings → Pages → Deploy from a branch → main → / (root) → Save。
项目文件夹内的文件名用于程序加载，请勿单独改名、删除或移动。
文件数量超过网页单批上传限制，建议用 GitHub Desktop 整体提交；也可按原目录分批上传。
所有单文件均小于 25 MiB；ZIP 总大小不是单个网页资源的大小。
Netlify 可直接使用本目录发布。

## 验证范围

已检查静态引用与按编号生成的资源路径全部存在，并验证转换图片像素一致。
当前环境未安装浏览器，未进行浏览器交互和视觉回归验证；部署后请点击项目卡片及播放视频检查。
