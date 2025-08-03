# 自用适用于mihomo内核（smart内核）搭配nikki
## 使用说明：
  Airport1:
    url: "" #这里填写订阅，可以是机场订阅，可以使sub-store聚合订阅

如何添加自己想要的规则？
1.rule-providers处找到一个订阅复制修改，是*domain还是*class自己领悟

2.rules处，添加rule-providers设定的规则名，RULE-SET,（rule-providers规则名）,（rules规则的名字）,no-resolve（不经过内核）

3.proxy-groups处，添加你的自定义rules，
例如：  - {name: 🚀 默认代理, type: select, proxies: [♻️ 香港智能, ♻️ 日本智能, ♻️ 狮城智能, ♻️ 美国智能, ♻️ 自动选择, 🇭🇰 香港节点, 🇯🇵 日本节点, 🇸🇬 狮城节点, 🇺🇲 美国节点, 🌐 全部节点, 直连]}

type: select（可以手动选择）
