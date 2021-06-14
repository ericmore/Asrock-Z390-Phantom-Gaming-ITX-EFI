#HackinTosh(黑苹果） Asrock-Z390-Phantom-Gaming-ITX-EFI
华擎 Z390 Phantom Gaming-ITX/ac ( Z390 芯片组 )， 英特尔 Core i7-9700K @ 3.60GHz 八核，MD Radeon RX 560 ( 4 GB / 蓝宝石 )

| Component（组件）  | Hardware（型号）| Price（价格）|
|:----------|:----------|:--|
| CPU  处理器 | Intel Core i7-9700K @ 3.60GHz 八核    | 1900 |
| MotherBoard 主板   | Asrock 华擎 Z390 Phantom Gaming-ITX/ac ( Z390 芯片组 )    | 1599|
| RAM 内存   | 32 GB ( Corsair DDR4 3000MHz )    | 600*2 =1200 |
| SSD  硬盘  | INTEL 660p 1TB    | 850|
| GPU 显卡   | AMD Radeon RX 460/560 ( 4 GB / 蓝宝石 )    | 650 |
| Wifi 无线网卡 | 博通黑苹果无线网卡 BCM94352Z 4DB | 295 （无线蓝牙一体信号差，推荐加USB免驱动蓝牙）|
| Bluetooth蓝牙| IOGEAR Bluetooth 4.0 USB Micro Adapter | 300|
| CPU风扇|DARK ROCK PRO 4 CPU | 619|
|电源|振华（SUPER FLOWER）额定750W LEADEX G 750| 700|
|显示器| 双4K显示器 Dell U2720QM typec 90w + | 4199 + 1899|
|机箱|乔思伯 JONSBO V8桌面迷你抽拉式机箱| 599

BIOS / 主板设置
- 高级（Advanced） > 芯片配置（Chipset Configuration） > VT-d -> Disabled
- 高级（Advanced） > USB 配置（USB Configuration） > XHCI Hand-off -> Enabled

Install Hackintonsh/ 安装教程.请参考icyleaf的[华擎 Z390 Gaming ITX 黑苹果安装教程](https://icyleaf.com/2019/03/asrock-z390-gaming-itx-install-hackintosh-tutorial/)    
MacOS 11.4 镜像 黑果小兵 [macOS Big Sur 11.4 20F71](https://blog.daliansky.net/macOS-BigSur-11.4-20F71-Release-version-with-OC-0.6.9-and-Clover-5134-and-PE-original-image.html)  
  
软件/工具下载  
[OpenCore 原版0.6.9](https://github.com/acidanthera/OpenCorePkg/releases)  
[Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip) [使用教程](https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html)
[ProperTree](https://github.com/corpnewt/ProperTree)  

功能验收，99%完美。
- [x] 显卡，蓝牙，无线，罗技摄像头，鼠标键盘免驱动
- [x] Airdrop/Handoff,睡眠/唤醒，USB3.0完美
- [x] DP/HDMI 显卡输出双4K，显示完美4k@60hz
- [ ] Typec口是唯一无法运作的接口

OpenCore开机画面（optional/可选）
https://blog.csdn.net/lxyoucan/article/details/110919429  
Official - https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html#setting-up-opencore-s-gui  

USB 定制
![z390 usb](https://github.com/ericmore/Asrock-Z390-Phantom-Gaming-ITX-EFI/blob/main/Image/usbport.jpeg)

- HS01: Internal/Case USB2 
- HS02: Internal/Case USB2 
- HS03: Rear USB3 (left of HDMI)
- HS04: Rear USB3 (left of DP)
- HS05: Rear USB3 (right of HDMI)
- HS06: Rear USB3 (right of DP)
- HS07: ??? possibly USB2 device on USB-C?
- HS08: Rear USB3 (right of Thunderbolt)
- HS09: Rear USB3 (under Ethernet)
- HS10: Internal/Case USB3 
- HS11: Internal/Case USB3 
- HS12-13: ???
- HS14: Bluetooth
- SS01: Rear USB3 (left of HDMI)
- SS02: Rear USB3 (left of DisplayPort)
- SS03: Rear USB3 (right of HDMI)
- SS04: Rear USB3 (right of DisplayPort)
- SS05: Rear USB3 (right of Thunderbolt)
- SS06: Rear USB3 (under Ethernet)
- SS07: Internal/Case USB3 
- SS08: Internal/Case USB3 
- SS09: ??? possibly USB3 device on USB-C?
- SS10: ??? possibly USB3 device on USB-C?


跑个分
GeekBench 5  
单核成绩**1137** 高于MacBook Pro (16-inch Late 2019)i9-9980HK @ 2.4 GHz (8 cores) 1098.  
多核成绩**6621** 高于MacBook Pro (16-inch Late 2019)i9-9980HK @ 2.4 GHz (8 cores) 6555.  
 
![GeekBench](https://github.com/ericmore/Asrock-Z390-Phantom-Gaming-ITX-EFI/blob/main/Image/GeekBench.png)

Disk Speed Test  
![ssd](https://github.com/ericmore/Asrock-Z390-Phantom-Gaming-ITX-EFI/blob/main/Image/ssd.png)

CINEBENCH R23.  
![cinebench](https://github.com/ericmore/Asrock-Z390-Phantom-Gaming-ITX-EFI/blob/main/Image/cinebench.png)
