Loon   国内网站/IP合集规则由《某某某自动打造》自动生成。

规则说明
包含所有China、ChinaIPs、Mainland等类型的规则，定义为已收集的国内网站/IP合集。
排除Advertising规则，便于和去广告规则搭配使用。
引用此规则后，不要再引用其他的国内规则，否则可能造成大量规则重复。
实验性规则，效果待观察，请谨慎评估后使用。

文件区别
ChinaMax_Resolve.list与ChinaMax.list的区别仅在于后者IP-CIDR(6)类型带no-resolve。
ChinaMax.list与ChinaMax_No_IPv6.list的区别仅在于后者不带IPv6类型的规则，适用纯IPv4网络。
ChinaMax_Resolve.list与ChinaMax_No_IPv6_Resolve.list的区别仅在于后者不带IPv6类型的规则，且不带no-resolve，适用纯IPv4网络。

配置建议
ChinaMax.list、ChinaMax_Domain.list 共同使用。
ChinaMax_Resolve.list、ChinaMax_Domain.list 共同使用。
ChinaMax_No_IPv6.list、ChinaMax_Domain.list 共同使用。
ChinaMax_No_IPv6_Resolve.list、ChinaMax_Domain.list 共同使用。