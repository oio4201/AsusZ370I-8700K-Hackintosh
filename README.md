# 8700K-AsusZ370I-UHD630 for macOS HighSierra/Sierra
## 硬件配置
| 硬件 | 型号 | 价格 | 入手 |
| --- | --- | --- | --- |
| CPU | i7 8700K | ￥2153 | 天猫 |
| 主板 | Asus ROG Strix Z370-i | ￥1649 | 京东 |
| 内存 | 影驰 8GB DDR4 3000MHz | ￥484 | 天猫 |
| 固态 | Crucial BX300 240GB<br>Samsung PM981 256GB | ￥324<br>￥543 | 京东<br>天猫 |
| 显示器 | AOC LV273HUPX 27英寸4K | ￥1949 | 京东 |
| 电源 | 全汉 MS450 SF电源 | ￥369 | 京东 |
| 散热 | 利民APX100RH<br>暴力熊散热硅脂 | ￥297<br>￥39.8 | 京东<br>天猫 |
| 机箱 | 屌丝伯 U1 Plus | ￥344 | 京东 |
| 线材 | 飞利浦 DP线1.2版 4K高清线 | ￥52 | 京东 |

## Install Info
* HighSierra无法安装在PM981上，看大家都说无法正常在10.13上工作
* BIOS设置关闭CSM，DMVT设为128MB（不要再放[IntelGraphicsDVMTFixup](https://github.com/BarbaraPalvin/IntelGraphicsDVMTFixup)，会导致分辨率不正常）
* 机型需要设置为iMac17.1 / iMac18.1, iMac18.3显卡无法正常工作，拖动卡顿或者说有残影
* 驱动显卡勾选Intel Inject+[IntelGraphicsFixup](https://github.com/lvs1974/IntelGraphicsFixup)即可
* 声卡驱动使用[AppleALC](https://github.com/vit9696/AppleALC)+[Lilu](https://github.com/vit9696/Lilu)，Clover注入ID 5




