此项目基于flippy的57+o打包N1(s905d)的openwrt，为个人正在使用的固件版本。

N1的openwrt来自我自己的另一个项目[N1Openwrt](https://github.com/myvmiao/N1)
# 默认IP及密码
默认IP 192.168.2.5  密码 password

* 将固件写入U盘或TF卡 推荐写盘软件 [rufu](https://rufus.ie/zh/)
* 插入U盘启动盒子，输入192.168.2.5进入后台
* 在系统——TTYD终端——输入用户名root；密码password
* 输入安装命令 `./install-to-emmc.sh`
* 如果显示挂载失败，重新执行上述安装命令`./install-to-emmc.sh`

# N1在线升级方法
* cd /mnt/mmcblk2p4
* wget 升级脚本下载.sh后缀文件
* wget .gz后缀名的固件链接,鼠标右击后缀.gz文件获取链接地址
* gzip -d 上一步下载的固件全名
* chmod +x *.sh
* ./升级脚本名字 img固件名

# 感激
 * [flippy](https://www.right.com.cn/forum/space-uid-285101.html)
 * [coolsnowwolf/Lede](https://github.com/coolsnowwolf/lede)
 * [mingxiaoyu](https://github.com/mingxiaoyu)
 * [hibuddies](https://github.com/hibuddies/openwrt/)
 * [jcny](https://github.com/Netflixxp/N1dabao/)
