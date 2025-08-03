# 自用! 适用于mihomo内核（smart内核等）搭配nikki
## ❗❗❗无出站🈚和DNS配置等，只有🈶订阅导入、规则分组、分流规则！！！！
## 故障转移✅，自动选择✅
### 使用说明：
  Airport1:
    url: "" #这里填写订阅，可以是机场订阅，可以使sub-store聚合订阅

如何添加自己想要的规则？
1.rule-providers处找到一个订阅复制修改，是*domain还是*class自己领悟

2.rules处，添加rule-providers设定的规则名，RULE-SET,（rule-providers规则名）,（rules规则的名字）,no-resolve（不经过内核）

3.proxy-groups处，添加你的自定义rules，
例如：  - {name: 🚀 默认代理, type: select, proxies: [♻️ 香港智能, ♻️ 日本智能, ♻️ 狮城智能, ♻️ 美国智能, ♻️ 自动选择, 🇭🇰 香港节点, 🇯🇵 日本节点, 🇸🇬 狮城节点, 🇺🇲 美国节点, 🌐 全部节点, 直连]}

type: select（可以手动选择）

客户端：

1.路由：

openwrt:https://github.com/nikkinikki-org/OpenWrt-nikki

OpenClash：https://github.com/vernesong/OpenClash


2.客户端

mihomo-party:https://github.com/mihomo-party-org/mihomo-party

clash-verge-rev:https://github.com/clash-verge-rev/clash-verge-rev

FlClash：https://github.com/chen08209/FlClash


### 常用规则地址：
https://ruleset.skk.moe/

geoip https://github.com/MetaCubeX/meta-rules-dat

geosite https://github.com/MetaCubeX/meta-rules-dat/tree/meta/geo-lite/geosite

分流规则 https://github.com/blackmatrix7/ios_rule_script

订阅转换 https://github.com/ACL4SSR/ACL4SSR/tree/master

教程 https://github.com/DustinWin/dustinwin.github.io?tab=readme-ov-file
