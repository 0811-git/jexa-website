# jexa 网站

手机聊天软件 jexa 的官网设计。默认首页为清爽现代方案，包含极简 J 钩子图标、手机聊天示意和本地交互演示。

## 产品宣传片

首页和 `videos.html#launch-film` 可观看《Jexa — Stay close.》。成片为 35 秒 / 1920×1080 / 60fps，使用原生播放器、按需加载和移动端内联播放。影片包含配乐，默认不自动播放。配乐使用 Terror Jr《3 Strikes》的 Apple Music 官方预览片段；它不是本站六支早期影片的原创配乐。

## 内容

- 六套独立设计，`?view=gallery` 打开方案总览。
- 六支原版介绍视频，`videos.html` 打开视频页。视频保留早期设计，部分页面已更新。
- 蓝色像素方案的 FolderFloat 交互（React / Matter.js）。
- 页面是品牌与产品设计概念，没有账户服务和真实安装包。

## 开发

`npm ci` 后执行 `npm run build:folder`。用任意静态服务器提供 `dist/`。

## 发布

GitHub Pages 使用 GitHub Actions 工作流。推送 main 会自动构建并发布 dist。

网站中的图标与原创音乐来自本项目。FolderFloat 基于用户提供的 React Bits 组件代码；React、Matter.js、esbuild 等第三方依赖的许可见其包内声明。

