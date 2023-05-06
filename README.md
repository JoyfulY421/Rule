# Rule

`https://gitlab.com/cleanflash/installer/-/tree/master`

UBlock Rules

`https://easylist-downloads.adblockplus.org/easylist.txt`

`https://easylist-downloads.adblockplus.org/easylistchina.txt`

`https://easylist-downloads.adblockplus.org/easyprivacy.txt`

`https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt`

`https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-ublock.txt`

`https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/mv.txt`

`https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/rule.txt`


简易教程https://yattazen.com/tutorial/clash-custom-config.html

纯自用

DNS泄露测试
https://ipleak.net/

使用ACL4SSR规则
https://acl4ssr-sub.github.io/

https://bianyuan.xyz/

https://`后端配置`&url=`节点`&config=`远程配置`&`后面均为基本参数`filename=`输出文件名`&`······`

Clash后端配置：

`api.bianyuan.xyz/sub?`target=clash `客户端Clash、Surfboard、QuantumultX······`

`pub-api-1.bianyuan.xyz/sub?`target=clash 

远程配置：

| 基本参数 | 含义 |
| :------------: | :-------------: |
| exclude | 排除节点 |
| include | 包含节点 |
| filename | 输出文件名 |
| `ture` or `flase` |
| append_type | 节点类型 |
| emoji | 图 |
| fdn | 过滤非法节点 |
| sort | 排序节点 |
| udp | 启动 UDP |
| surge.doh |
| clash.doh |
| new_name | Clash New Field |
| insert | 网易云 |
| list |
| tfo |
| scv |

规则类型

| 基本参数 | 含义 |
| :----- | :----- |
| `DOMAIN` | 完全匹配域名，例如 `DOMAIN,google.com` 匹配 `google.com` 但不匹配 `www.google.com` |
| `DOMAIN-SUFFIX` | 匹配域名后缀，例如 `DOMAIN-SUFFIX,google.com` 匹配 `google.com` 和 `www.google.com` |
| `DOMAIN-KEYWORD` | 关键词匹配域名，例如 `DOMAIN-KEYWORD,google` 匹配 `google.com` 和 `google.jp` |
| `GEOIP` | 通过 MaxMind GeoIP 匹配国家代码，比如 `GEOIP,CN`，可以添加 `no-resolve` 避免触发 DNS 解析 |
| `IP-ASN` | 通过 IP 自治系统编号，比如 `IP-ASN,714`，可以添加 `no-resolve` 避免触发 DNS 解析 |
| `IP-CIDR /IP-CIdR6` | IP CIDR 范围，可以添加 `no-resolve` 避免触发 DNS 解析 |
| `DST-PORT` | 目标端口 |
| `RULE-SET` | 在引用大量规则时请使用[规则集合](https://stash.wiki/rules/rule-set) |
| `GEOSITE` | [domain-list-community](https://github.com/v2fly/domain-list-community) 是由 v2fly 社区维护的域名列表 |
| `PROCESS-NAME` | 进程名称，例如 `PROCESS-NAME,Telegram`，仅对本机进程有效 |
| `PROCESS-PATH` | 进程路径，例如 `PROCESS-PATH,/Applications/Telegram.app/Contents/MacOS/Telegram`，仅对本机进程有效 |
| `SCRIPT` | 
