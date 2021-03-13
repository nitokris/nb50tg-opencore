# nb50tg-opencore
k670c-g6a1 黑苹果EFI

> 注意事项

* 当前oc版本为 0.6.7 配置时使用的opencore configrator 为2.30.0.0
* 理论上支持蓝天nb50tg的所有电脑，但是我手里只有k670c-g6a1 其他设备未作测试，若出现问题可尝试自行解决
* 使用时请务必解锁主板CFG，解锁教程请参照这个链接：https://zhuanlan.zhihu.com/p/121655468
* 目前仅支持 big sur，catalina以及更低版本能否使用未知
* efi中并未加入intel无线网卡驱动，如需要使用intel网卡和蓝牙请自行寻找对应驱动加载即可
* hdmi接口无法使用
* 使用时请务必使用 opencoreconfigrator 生成机型信息

> 已知问题

* 亮度补丁重启概率失效，因个人技术原因修复不了，若重启出现屏幕无亮度的情况，稍等一会儿（时长不确定）