# AN515-52-OC-EFI-BigSur
efi也是我在别人的基础上改的，基本能驱动的都驱动了。同时我是解锁了cfg lock的。
机型：宏碁AN515-52 暗影骑士3
+ cpu:i5-8300h
+ gpu:1060
+ 网卡 bcm94352z 原来的intel网卡9560可以直接换
+ 声卡 alc255 

不工作：
+ 显卡1060
+ hdmi接口（外接显示器走displaylink方案，使用外置显卡，我在闲鱼买的是睿音usb3.0扩展坞，最高支持2k 60hz）
+ 换网卡可以隔空投送不换就不能


效果图：

使用原装intel网卡9560需要把对应打勾的kext取消掉，把标出来的三个打上勾

![](https://github.com/bigboysuper6/AN515-52-OC-EFI-BigSur/blob/main/image/1.png)

使用原装intel网卡9560声卡无法驱动的话需要将alc layout id 改为13，或试试其他

![](https://github.com/bigboysuper6/AN515-52-OC-EFI-BigSur/blob/main/image/2.png)

cpu变频正常，不正常的话去搜下如何解决，比较简单

![](https://github.com/bigboysuper6/AN515-52-OC-EFI-BigSur/blob/main/image/3.png)

预览图

![](https://github.com/bigboysuper6/AN515-52-OC-EFI-BigSur/blob/main/image/4.png)


