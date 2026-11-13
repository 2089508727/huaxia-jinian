# 华夏纪年

华夏纪年是一部可离线浏览的中国历史图鉴。从朝代时间轴进入，可以查看同时存在的政权，再沿着人物、事件、年份和地图继续探索。

**[打开网站](https://2089508727.github.io/huaxia-jinian/)** · [下载完整离线包（ZIP）](https://github.com/2089508727/huaxia-jinian/archive/refs/heads/main.zip)

## 从哪里开始

| 入口 | 可以做什么 |
| --- | --- |
| [历代王朝](https://2089508727.github.io/huaxia-jinian/#/dynasties) | 搜索朝代或时期。选择时期后，时间轴和朝代目录会一起更新。左右拖动、缩放时间轴，点击色条进入相应条目。 |
| [历史人物](https://2089508727.github.io/huaxia-jinian/#/people) | 按姓名、字号、朝代或身份查找人物。详情页可跳转到生平、关系、事件和史料。部分人物配有交互关系图。 |
| [重大事件](https://2089508727.github.io/huaxia-jinian/#/events) | 按朝代、类别或关键词筛选，在「编年事件」和「纪年未定」之间切换。 |
| [年份探索](https://2089508727.github.io/huaxia-jinian/#/years?year=1271) | 以 1271 年为例，查看该年收录的政权、都城、人物与事件，也可以跳到历史地图。 |
| [历史地图](https://2089508727.github.io/huaxia-jinian/#/map) | 使用「江山时序」按年份查看疆域演变、都城和并立政权。 |
| [朝代比较](https://2089508727.github.io/huaxia-jinian/#/compare) | 选择两个朝代或时期，并排查阅纪年、都城、制度和文化等资料。 |

## 在本地打开

1. 下载并解压完整 ZIP。
2. 双击解压目录里的 `index.html`。
3. 打开「历史地图」时，浏览器会读取同一目录下的 `jiangshan-atlas/index.html`。移动或备份时，请保留整个文件夹。

主站和地图均已打包。双击即可浏览，无需安装 Node.js、启动服务器或联网。外部参考文献链接需要联网打开。

## 更新 GitHub Pages

仓库发布的是静态网站文件。GitHub Pages 从 `main` 分支根目录发布。

- 更新主站时，用新版 `index.html` 替换仓库根目录的同名文件，再提交到 `main`。
- 更新地图时，将新版地图文件放在 `jiangshan-atlas/`，并同步检查来源和许可说明。
- 提交后，可在仓库的 [Actions](https://github.com/2089508727/huaxia-jinian/actions) 查看发布进度。发布完成后，打开网站检查首页和历史地图。

## 纪年、资料与致谢

时间轴按年代绘制，平行色条表示政权并存。早期年代、文献记载与考古材料之间的争议，见相应条目和[资料说明](https://2089508727.github.io/huaxia-jinian/#/about)。馆藏图像的出处与使用说明见[图像来源](https://2089508727.github.io/huaxia-jinian/#/about#image-sources)。

历史地图基于 DeanChensj 的[江山时序](https://github.com/DeanChensj/jiangshan-map)。地图目录随附 [GPL-3.0 许可](jiangshan-atlas/LICENSE)及[上游版本与修改说明](jiangshan-atlas/SOURCE.md)。
