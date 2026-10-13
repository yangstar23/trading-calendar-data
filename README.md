# trading-calendar-data

「交易员日历」iOS app 的排期数据：各市场的交易时段、休市和半日市安排，以及港股通、北向的服务日。

- `schedule.json`：app 打开时从这里检查更新
- 每条例外都带 `source`，对应 `sources` 里的官方公告
- 发布新数据时 `generatedAt` 必须比上一版新，否则 app 会忽略

数据只描述交易所公布的计划交易阶段，不代表个股停牌、账户权限或券商系统状态。
