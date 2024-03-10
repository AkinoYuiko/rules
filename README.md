# 配置示例

```config
[Proxy]
Proxy = select, policy-path=订阅链接

[Rule]
RULE-SET,https://github.com/AkinoYuiko/surge-list/raw/main/blocked.list,Proxy
RULE-SET,https://github.com/AkinoYuiko/surge-list/raw/main/cncidr.list,DIRECT
FINAL,Proxy,dns-failed
```
