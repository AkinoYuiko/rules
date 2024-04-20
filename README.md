# 配置示例

```config
[General]
ipv6 = true
proxy-test-url = http://1.1.1.1
internet-test-url = http://223.5.5.5

[Proxy Group]
Proxy = select, policy-path=订阅链接

[Rule]
RULE-SET,http://yuiko/boost,Proxy
RULE-SET,http://yuiko/cn,DIRECT
RULE-SET,LAN,DIRECT
FINAL,Proxy

[URL Rewrite]
^http://yuiko/(.*?)$ https://raw.githubusercontent.com/AkinoYuiko/rules/main/$1.list 302
```
