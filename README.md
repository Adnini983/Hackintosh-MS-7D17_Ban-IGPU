# 黑苹果EFI：MAG B560M MORTAR WIFI(屏蔽核显)

EFI由RapidEFI生成 三码未定制
因本人没有可以免驱的10代酷睿CPU 故默认屏蔽了核显 转而由独显负责计算与画面输出

兼容性注意：RX580 2048SP默认不支持黑苹果免驱 需要重新刷写成RX570
刷写显卡vBIOS有风险 这里不提供任何教程 仅提供自用显卡的vBIOS备份数据

# 配置清单： #
|部件|品牌型号|支持情况|
|---|---|---|
|CPU|英特尔 i5-11400|核显不可|
|主板|微星MAG B560M MORTAR WIFI|CFG可关|
|内存|金士顿DDR4 2400HMz 8GB*2|正常|
|GPU|宏想Commander AMD Radeon RX580 8G(2048SP)|需要刷写成RX570|
|硬盘|昂达SATA A-48 512G|正常|
|网卡|Realtek RTL8125 2.5G|正常|
|Wi-Fi|英特尔 Wi-Fi 6E AX210E 160MHz|建议更换为BCM94360系列|
|声卡|Realtek ALC897|正常|
|macOS版本|Ventura 13.6|大部分正常|
|OpenCore版本|1.0.1|RapidEFI生成|
|机型|iMacPro1,1|正常 理论可装Sequoia|

# 待完善问题： #
- [ ] AX210的蓝牙功能