# 配置示例

```config
[Proxy Group]
Proxy = select, policy-path=订阅链接

[Rule]
RULE-SET,https://github.com/AkinoYuiko/rules/raw/main/boost.list,Proxy
RULE-SET,LAN,DIRECT
GEOIP,CN,DIRECT
FINAL,Proxy
```
