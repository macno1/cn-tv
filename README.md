# 中文台直播源（香港可用）

7 个公开源、3465 条直播流逐条实测后筛出的可用列表。

## 粘贴地址

| 播放器 | 地址 | 内容 |
|---|---|---|
| TiviMate | https://macno1.github.io/cn-tv/zh-lite.m3u | 精简版 204 条线路 |
| TiviMate | https://macno1.github.io/cn-tv/zh-hd.m3u | 高清专版 43 条（实测 1080P/4K） |
| TiviMate（完整） | https://macno1.github.io/cn-tv/zh.m3u | 完整版 426 条 |
| 影视仓 / TVBox | https://macno1.github.io/cn-tv/zh.txt | TXT 387 条（保留多线路） |

镜像（github.io 打不开时）：
https://cdn.jsdelivr.net/gh/macno1/cn-tv@main/zh-lite.m3u

## 标记说明

-  = 裸 IP 中转源（个人美国 VPS 中转），能用但晚高峰会卡
-  /  = 实测画质，来自 HLS 主播放列表的 RESOLUTION 字段，**不是**频道名里自称的高清
- 频道分组：① 香港 ② 凤凰 ③ 央视 ④ 卫视 ⑤ 港澳台/海外中文 ⑥ 地方台

## 实测数据

- 3465 条去重 → 668 条可连（19%）
- 筛后精简版复测：204 条线路可连 **194 条（95%）**
- 已剔除：蜻蜓FM 广播音频流（电视上无画面）、宗教/购物/宠物等噪音台
- 香港组 RTHK 31-35 / HOY 76-78 实测 **1080P** 且为官方 CDN 直连

## 限制（如实说明）

- CCTV-1 ~ 8 主力台没有官方 CDN 直连，只能走 ⚠ 中转
- 台湾主流台（台视/中视/华视/民视/东森/三立）公开源里没有
- 公开源平均 2-4 周失效一批，需定期重跑脚本刷新

内容仅为公开可访问的直播流地址。
