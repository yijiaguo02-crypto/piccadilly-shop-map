# Piccadilly Court 周边采购地图

以 Piccadilly Court（457-463 Caledonian Rd, London N7 9BJ）为中心，2.2 km 内 55 个采购点的地图，包含步行距离、性价比分析和导航链接。

- 纯静态站点：`index.html` + `data.js`（门店数据）+ `config.js`（可选的腾讯地图 key）
- 性价比算法：真实成本 = 篮子 × 门店价格指数 + 往返步行时间 × 时间价值
- 导航：高德 / 腾讯地图步行导航链接，复制地址 / 坐标

## 数据来源

- 门店位置：© OpenStreetMap contributors（ODbL），2026-10-03 抓取
- 价格指数：Which? Cheapest Supermarkets，2026 年 8 月，92 件商品
- 便利店溢价：Which? 便利店价格调查（42 件商品）
- 营业时间只核实了部分门店，以门店官网为准；步行时间为估算值
