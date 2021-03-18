此项目基于flippy的38+o和55+o打包Phicomm N1的openwrt

N1的openwrt来自我自己的另一个项目[N1Openwrt](https://github.com/Netflixxp/op-)

# 插件列表

 插件列表
├ SSR-Plus [183-8]
├ passwall[4-16]
├ openclash[0.42.02]
├ hello word[1.2-51]
├ Argon主題 
├ docker-ce
├ AdGuard Home
├ 实时监控
├TTYD终端
├动态DNS
├UPdp
├AdGuard Home
├网易音乐解锁
├京东薅羊毛
├Frp
├无线wifi
登陆：192.168.1.99
密码：password

# N1新版固件如何刷

[看教程](https://ybfl.xyz/100.html)

非54+o版升级到55+o版，如果一直卡在fdisk失败那里的解决办法：一是再多试几次，如果还不成功，则需要手动清空分区表然后再重试，具体命令:
```
  dd   if=/dev/zero   of=/dev/mmcblk2  bs=512  count=1  &&  sync
```

# 感激
 * [flippy](https://www.right.com.cn/forum/space-uid-285101.html)
 * [coolsnowwolf/Lede](https://github.com/coolsnowwolf/lede)
 * [mingxiaoyu](https://github.com/mingxiaoyu)
 * [hibuddies](https://github.com/hibuddies/openwrt/)

