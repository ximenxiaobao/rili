# 黄历日历

2026–2035 年的黄历日历，每天一条全天事件：农历、干支、节气节日、宜忌、冲煞、建除十二神、二十八星宿、吉神凶煞、喜福财神方位。

## 订阅

在 iPhone：设置 → 日历 → 账户 → 添加账户 → 其他 → 添加已订阅的日历，服务器填：

```
https://raw.githubusercontent.com/ximenxiaobao/rili/main/huangli.ics
```

国内网络直连不稳时，可以改用 jsDelivr 加速地址：

```
https://cdn.jsdelivr.net/gh/ximenxiaobao/rili@main/huangli.ics
```

也可以把 `huangli.ics` 下载后直接打开，选择「添加全部」，得到一份固定副本。

## 生成

由 [jizhang](https://github.com/ximenxiaobao/jizhang) 仓库里的 `scripts/gen_huangli.py` 生成，数据来自开源库 `lunar_python`。宜忌按传统黄历规则计算，不同流派之间会有出入。
