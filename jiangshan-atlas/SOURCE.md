# 江山时序 · 来源与修改说明 / Source & Modifications

本目录（`/jiangshan-atlas/`）是「华夏纪年」站内「历史地图」页面所使用的地图应用。

## 上游项目 / Upstream

- 名称：江山时序 · Jiangshan Atlas（中国历史地图时间轴）
- 仓库：<https://github.com/DeanChensj/jiangshan-map>
- 在线演示：<https://deanchen.me/jiangshan-map/>
- 作者：DeanChensj
- 许可证：**GNU General Public License v3.0**（全文见同目录 [`LICENSE`](./LICENSE)）

## 本目录对应的上游版本 / Pinned revision

| 项目 | 值 |
|---|---|
| commit | `6a781e180c5c67e95e5da3af4c96fee963ef19f6` |
| 同步日期 | 2026-11-08 |
| 形态 | 上游的**离线单文件打包产物**（CSS / JS / 数据 / 地形瓦片全部内联） |

获取对应源码：

```bash
git clone https://github.com/DeanChensj/jiangshan-map.git
cd jiangshan-map && git checkout 6a781e180c5c67e95e5da3af4c96fee963ef19f6
```

## 对上游所做的修改 / Modifications

1. **拆分发布**：把原本内联在「华夏纪年」主文件
   `<script type="application/json" id="offline-atlas">` 中的这份 HTML 解出，
   作为独立页面发布到 `/jiangshan-atlas/index.html`。页面内容本身未改动。
2. **主题对齐**：在 `<head>` 末尾追加 `<style id="huaxia-atlas-skin">`，
   把 `--bg-parchment` / `--vermilion` / `--text-main` 等变量对齐到「华夏纪年」的纸色—墨色—朱红体系，
   并调整 `#nav-bar` 的左内边距使工具条与站点容器对齐。
   该样式块是本项目的修改，同样以 GPL-3.0 提供。
3. 其余 HTML / CSS / JS / 数据与上游该 commit 一致。

## 分发说明 / Distribution

- 本目录内容（含上述修改）按 **GPL-3.0** 分发；完整对应源码 = 上游仓库上述 commit + 本目录 `index.html` 中的样式块。
- 「华夏纪年」主站通过**同源 iframe** 引用本目录，两者是独立程序的聚合，主站其余内容不受本许可证约束。
- 上游问题请提交至上游仓库；本站接入相关的问题可提到 <https://github.com/2089508727/huaxia-jinian/issues>。
