此项目基于flippy的55+o打包N1和s905X3 （hk1等）的openwrt，为jcnf个人正在使用的固件版本。

openwrt来自我自己的另一个项目[N1Openwrt](https://github.com/Netflixxp/op-)

# 更新说明
固件采用自动编译，Acrions将会在每天监控上游代码是否更新，如passwall ssrp等，一旦检测到上游代码更加将会自动编译打包，于每天上午7时发布最新版固件。

# 插件下载
点击右面的 “Releases”，然后会看到N1和s905x3的固件，根据自己需求下载就好！

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
