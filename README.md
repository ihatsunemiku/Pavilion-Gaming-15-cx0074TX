# 光影精灵4 i5-8300H clover EFI

**使用方法

把 CLOVER 和 Boot 拷贝到 EFI 分区内和 Microsoft 同级的文件夹中即可

****已确认工作****

Intel UHD Graphics 630 正常驱动

通过设置或者键盘上快捷键正常调节亮度，记忆亮度信息

144hz 刷新率可调

有线上网，无线上网（ clover 版本需要软件支持），蓝牙

内置键盘，触控板，键盘灯及键盘灯开关工作正常

蓝牙耳机，type-c 耳机，外放正常工作 （注入 ID 为 28 ）并可以通过键盘上的快捷键快速调节

前置摄像头工作正常（tested via FaceTime & WeChat video ）

Nvidia 独显已屏蔽

****已知问题****

休眠时风扇会间歇性转动，不是真正休眠

HDMI 接口暂时不可用，可用 type-c 转 USB 代替

Android USB 网络共享暂不可用

Android Type-C 传文件存在问题

****其他****

开机后有极小概率出现小于 0.1s 的雪花屏

如果遇见 开机后外置扬声器没有声音的情况，请首先检查注入之 驱动 ID。如果都不行，请备份 CLOVER/kexts/Others/CodecCommander.kext 备份到别处，并将对应文件从 EFI 分区删除

键盘暂时无法调整亮度

tested with 10.15.5 & 10.15.7 ，可在线升级到 10.15.7，相关驱动已更新

*TODO

解决某些 DRM 版权内容暂时无法播到问题

转移到 opencore 并且支持 Big Sur

键盘暂时无法调整亮度

****感谢****

https://github.com/mechtifs/hackintosh-hp-15-cx0/ 

https://github.com/acidanthera/AppleALC

https://github.com/acidanthera/virtualsmc/

**联系我

Telegram https://t.me/tg_cn_chatBot

