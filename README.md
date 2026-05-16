# OpenWrt Custom Firmware for Cudy WR1300 v4

## 中文教程 | [English Tutorial](#english-tutorial)

我已经将固件编译完成了，而且所有功能正常使用。LED灯也正常点亮。

这是原厂固件和我编译好的固件

- [openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-sysupgrade.bin](https://github.com/GuoShuangyan/Openwrt-Cudy-WR1300-v4/raw/master/openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-sysupgrade.bin)
- [openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-flash.bin](https://github.com/GuoShuangyan/Openwrt-Cudy-WR1300-v4/raw/master/openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-flash.bin) 

首先将官方给的openwrt和我编译的openwrt准备好

然后进入官方原厂固件，点击固件升级，将官方给的openwrt固件上传上去，进行刷写。

![固件升级](images/固件升级.png)

![浏览](images/浏览.png)

![上传官方固件](images/上传官方固件.png)

刷写成功后，进入openwrt的首页，接下来再次进行固件升级。将我编译的固件上传，进行升级。

![再次选择-1](images/再次选择-1.png)

![再次选择-2](images/再次选择-2.png)

![再次选择-3](images/再次选择-3.png)

![再次选择-4](images/再次选择-4.png)

![再次选择-5](images/再次选择-5.png)

![再次选择-6](images/再次选择-6.png)

这里不要保留任何配置，将对号取消掉。然后点击 continue进行升级。

![再次选择-7](images/再次选择-7.png)

升级完成后进入首页。不习惯中文的可以将中文包移除。

![首页](images/首页.png)

这是你会发现路由器的led灯正常了，但是还有两个灯没有亮2.4G和5G的信号灯没有亮，那是因为WIFI还没有启用。

![WiFi灯不正常](images/WiFi灯不正常.png)

接下来我们启用WiFi。

![WiFi](images/WiFi.png)

WiFi启动后，路由器的信号灯也亮了起来。

![WiFi灯正常](images/WiFi灯正常.png)

---

## English Tutorial

I have finished compiling the firmware, and all functions are working properly. The LED lights are also functioning normally.

Here are the original factory firmware and the firmware I compiled:

- [openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-sysupgrade.bin](https://github.com/GuoShuangyan/Openwrt-Cudy-WR1300-v4/raw/master/openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-sysupgrade.bin)
- [openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-flash.bin](https://github.com/GuoShuangyan/Openwrt-Cudy-WR1300-v4/raw/master/openwrt-ramips-mt7621-cudy_wr1300-v4-squashfs-flash.bin) 

First, prepare the official OpenWrt firmware and the one I compiled.

Then enter the official factory firmware interface, click on "Firmware Upgrade", upload the official OpenWrt firmware, and flash it.

![Firmware Upgrade](images/固件升级.png)

![Browse](images/浏览.png)

![Upload Official Firmware](images/上传官方固件.png)

After flashing is complete, enter the OpenWrt homepage. Next, perform the firmware upgrade again. Upload the firmware I compiled and proceed with the upgrade.

![Select Again - 1](images/再次选择-1.png)

![Select Again - 2](images/再次选择-2.png)

![Select Again - 3](images/再次选择-3.png)

![Select Again - 4](images/再次选择-4.png)

![Select Again - 5](images/再次选择-5.png)

![Select Again - 6](images/再次选择-6.png)

Do not keep any configuration here — uncheck the checkbox. Then click "Continue" to proceed with the upgrade.

![Select Again - 7](images/再次选择-7.png)

After the upgrade is complete, enter the homepage. If you are not comfortable with Chinese, you can remove the Chinese language pack.

![Homepage](images/首页.png)

At this point, you will notice that the router's LED lights are working normally, but two lights are still off — the 2.4G and 5G signal indicators are not lit. This is because WiFi has not been enabled yet.

![WiFi Lights Not Working](images/WiFi灯不正常.png)

Next, let's enable WiFi.

![WiFi](images/WiFi.png)

After WiFi is enabled, the router's signal lights will turn on as well.

![WiFi Lights Working](images/WiFi灯正常.png)
