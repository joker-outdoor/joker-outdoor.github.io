# Joker Outdoor

户外路线可视化目录：https://joker-outdoor.github.io/

纯静态页面，无构建依赖、脚本或外部资源。`index.html` 维护路线链接，`style.css` 维护显示样式；各赛道仍由原项目独立发布。

首页路线包括[剑门关 · 徒步](/JianmenPass-hike-2026-11-08/)。

GitHub Pages 设置使用 main 分支的根目录。首页改动走 feature 分支与 PR，合入后由 Pages 发布；回退使用正常 revert PR。

本地预览：`python3 -m http.server 8765 --bind 127.0.0.1`，然后打开 `http://127.0.0.1:8765/`。

设计采用 frontend-design，由 Cursor 的 claude-opus-5-5-high 生成。首页仅使用已发布的公开路线入口，不复制其他项目的轨迹或个人数据。
