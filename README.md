# kunz-kun 的 freesub

基于 [hezhanleiok/freesub](https://github.com/hezhanleiok/freesub) 配置，参考[小何的教程](https://blog.imxiaohe.com/2026/09/github-scriptsmain.html)。

自动收集公开订阅、检测连接并按国家和家宽运营商分类。节点后缀为 `kunz-kun`，每 6 小时更新，也可在 Actions → Update Subscriptions → Run workflow 手动运行。

首次运行成功后，下列订阅地址才会生成。可用性随上游节点变化，家宽分类为运营商信息推断。

## 总订阅

| 格式 | 地址 |
| --- | --- |
| V2Ray / Base64 | https://raw.githubusercontent.com/kunz-kun/freesub/main/output/v2ray.txt |
| Clash / Mihomo | https://raw.githubusercontent.com/kunz-kun/freesub/main/output/clash.yaml |
| sing-box（上游输出格式，请核对客户端兼容性） | https://raw.githubusercontent.com/kunz-kun/freesub/main/output/singbox.json |
| 家宽 V2Ray | https://raw.githubusercontent.com/kunz-kun/freesub/main/output/residential.txt |
| 家宽 Clash | https://raw.githubusercontent.com/kunz-kun/freesub/main/output/residential-clash.yaml |

## 按照家宽分类节点订阅

等待首次运行。

---

## 按照国家分类节点订阅

等待首次运行。

---

## 配置

- 订阅源：`scripts/main.py` 中的 `SUBSCRIBE_SOURCES`。
- 节点后缀：`personalize_nodes` 函数中的 `kunz-kun`。
- 更新间隔：`.github/workflows/update.yml` 的 `cron`。
- 定时任务为 UTC 00、06、12、18 点（北京时间 08、14、20、次日 02 点），实际执行可能延迟。
- 无可用节点时报告失败并保留上次产物。
