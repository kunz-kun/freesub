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

> 经 MaxMind ASN 数据库与核心运营商白名单严格甄别，剔除所有机房与云厂商，保留正宗民用宽带。当前可用家宽节点：**0** 个。

| 家宽地区 | 数量 | V2RayN 订阅 | Clash 订阅 | sing-box 订阅 |
| :--- | :---: | :--- | :--- | :--- |
| <nobr>暂无家宽</nobr> | 0 | - | - | - |



















---

## 按照国家分类节点订阅

| 地区代码 | 数量 | V2RayN 订阅 | Clash 订阅 | sing-box 订阅 |
| :--- | :---: | :--- | :--- | :--- |
| <nobr><img src="https://flagcdn.com/20x15/us.png" width="20" height="15" alt="US"> US 美国</nobr> | 45 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/US.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/US.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-US.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-US.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-US.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-US.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/nl.png" width="20" height="15" alt="NL"> NL 荷兰</nobr> | 17 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/NL.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/NL.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-NL.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-NL.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-NL.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-NL.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/sg.png" width="20" height="15" alt="SG"> SG 新加坡</nobr> | 8 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/SG.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/SG.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-SG.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-SG.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-SG.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-SG.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/hk.png" width="20" height="15" alt="HK"> HK 中国香港</nobr> | 6 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/HK.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/HK.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-HK.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-HK.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-HK.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-HK.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/tw.png" width="20" height="15" alt="TW"> TW 中国台湾</nobr> | 5 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/TW.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/TW.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-TW.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-TW.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-TW.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-TW.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/fr.png" width="20" height="15" alt="FR"> FR 法国</nobr> | 4 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/FR.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/FR.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-FR.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-FR.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-FR.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-FR.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/au.png" width="20" height="15" alt="AU"> AU 澳大利亚</nobr> | 4 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/AU.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/AU.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-AU.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-AU.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-AU.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-AU.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/sc.png" width="20" height="15" alt="SC"> SC SC</nobr> | 3 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/SC.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/SC.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-SC.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-SC.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-SC.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-SC.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/ca.png" width="20" height="15" alt="CA"> CA 加拿大</nobr> | 3 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/CA.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/CA.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-CA.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-CA.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-CA.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-CA.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/jp.png" width="20" height="15" alt="JP"> JP 日本</nobr> | 3 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/JP.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/JP.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-JP.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-JP.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-JP.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-JP.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/kr.png" width="20" height="15" alt="KR"> KR 韩国</nobr> | 2 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/KR.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/KR.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-KR.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-KR.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-KR.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-KR.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/pl.png" width="20" height="15" alt="PL"> PL PL</nobr> | 2 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/PL.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/PL.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-PL.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-PL.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-PL.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-PL.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/ro.png" width="20" height="15" alt="RO"> RO RO</nobr> | 2 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/RO.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/RO.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-RO.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-RO.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-RO.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-RO.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/bg.png" width="20" height="15" alt="BG"> BG BG</nobr> | 2 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/BG.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/BG.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-BG.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-BG.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-BG.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-BG.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/br.png" width="20" height="15" alt="BR"> BR 巴西</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/BR.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/BR.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-BR.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-BR.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-BR.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-BR.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/de.png" width="20" height="15" alt="DE"> DE 德国</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/DE.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/DE.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-DE.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-DE.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-DE.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-DE.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/cy.png" width="20" height="15" alt="CY"> CY CY</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/CY.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/CY.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-CY.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-CY.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-CY.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-CY.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/gr.png" width="20" height="15" alt="GR"> GR GR</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/GR.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/GR.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-GR.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-GR.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-GR.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-GR.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/ch.png" width="20" height="15" alt="CH"> CH CH</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/CH.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/CH.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-CH.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-CH.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-CH.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-CH.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/tr.png" width="20" height="15" alt="TR"> TR 土耳其</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/TR.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/TR.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-TR.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-TR.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-TR.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-TR.json)</nobr> |
| <nobr><img src="https://flagcdn.com/20x15/my.png" width="20" height="15" alt="MY"> MY 马来西亚</nobr> | 1 | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/MY.txt) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/MY.txt)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/clash-MY.yaml) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/clash-MY.yaml)</nobr> | <nobr>[⚡CDN](https://fastly.jsdelivr.net/gh/kunz-kun/freesub@main/output/by-country/singbox-MY.json) · [🌐Raw](https://raw.githubusercontent.com/kunz-kun/freesub/main/output/by-country/singbox-MY.json)</nobr> |



















---

## 配置

- 订阅源：`scripts/main.py` 中的 `SUBSCRIBE_SOURCES`。
- 节点后缀：`personalize_nodes` 函数中的 `kunz-kun`。
- 更新间隔：`.github/workflows/update.yml` 的 `cron`。
- 定时任务为 UTC 00、06、12、18 点（北京时间 08、14、20、次日 02 点），实际执行可能延迟。
- 无可用节点时报告失败并保留上次产物。
