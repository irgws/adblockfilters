# AdBlock DNS Filters

去广告合并规则，每8个小时更新一次。

本项目为 [217heidai/adblockfilters](https://github.com/217heidai/adblockfilters) 的镜像仓库，自动同步上游规则，提供 jsDelivr CDN 加速订阅。

## 说明

1. 定时从上游 [217heidai/adblockfilters](https://github.com/217heidai/adblockfilters) 的 GitHub Release 同步规则，每 8 小时一次。
2. 本项目仅做同步分发，不做任何规则修改。如发现误拦截情况，可临时添加放行规则（如 `@@||www.example.com^$important`），并向上游规则反馈。
3. 订阅链接提供 raw 直连 + jsDelivr 双 CDN 加速，请根据网络情况选择。

## 订阅链接

1. 规则x' 为规则x的 Lite 版，仅针对国内域名拦截，体积较小（如添加完整规则报错数量限制，请尝试 Lite 规则）
2. AdGuard 等浏览器插件使用规则1 + 规则2（规则2为规则1的补充，仅适用浏览器插件）

| 规则 | 原始链接 | 加速链接1 | 加速链接2 | 适配说明 |
| --- | --- | --- | --- | --- |
| 规则1 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdns.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdns.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdns.txt) | AdGuard、AdGuard Home 等 |
| 规则1' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdnslite.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnslite.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnslite.txt) | AdGuard、AdGuard Home 等 |
| 规则2 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockfilters.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockfilters.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockfilters.txt) | AdGuard 等浏览器插件 |
| 规则2' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockfilterslite.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockfilterslite.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockfilterslite.txt) | AdGuard 等浏览器插件 |
| 规则3 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdnsfilter.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsfilter.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsfilter.txt) | InviZible Pro、personalDNSfilter |
| 规则3' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdnsfilterlite.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsfilterlite.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsfilterlite.txt) | InviZible Pro、personalDNSfilter |
| 规则4 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdnsmasq.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsmasq.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsmasq.txt) | DNSMasq |
| 规则4' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockdnsmasqlite.txt) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsmasqlite.txt) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockdnsmasqlite.txt) | DNSMasq |
| 规则5 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblocksmartdns.conf) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblocksmartdns.conf) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblocksmartdns.conf) | SmartDNS |
| 规则5' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblocksmartdnslite.conf) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblocksmartdnslite.conf) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblocksmartdnslite.conf) | SmartDNS |
| 规则6 | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockclash.list) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockclash.list) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockclash.list) | Shadowrocket |
| 规则6' | [raw](https://raw.githubusercontent.com/irgws/adblockfilters/main/rules/adblockclashlite.list) | [cdn.jsdelivr.net](https://cdn.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockclashlite.list) | [fastly.jsdelivr.net](https://fastly.jsdelivr.net/gh/irgws/adblockfilters@main/rules/adblockclashlite.list) | Shadowrocket |

## 上游规则源

1. 感谢各位广告过滤规则维护大佬们的辛苦付出。
2. 规则源及更新状态详见上游 [217heidai/adblockfilters](https://github.com/217heidai/adblockfilters)。

## 更新机制

- 由 GitHub Actions 定时任务驱动，每 8 小时自动从上游 Release 同步
- 仅在有变更时产生 commit，避免空提交
- jsDelivr 缓存存在一定刷新延时（通常几分钟到半小时），如刚更新后仍取到旧版本，稍后重试即可

## 致谢

本项目规则来源于 [217heidai/adblockfilters](https://github.com/217heidai/adblockfilters)，感谢原作者的持续维护。   
