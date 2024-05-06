# TWRP device tree for Xperia 1II

Xperia 1II (codenamed _"pdx203"_) is a high-end smartphone from Sony.

It was announced & released on February 2020.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Snapdragon® 865 (SM8250)
CPU     | 1x2.84 GHz Cortex-A77 & 3x2.42 GHz Cortex-A77 & 4x1.8 GHz Cortex-A55
GPU     | Adreno 650
Memory  | 8/12 GB RAM
Shipped Android Version | 10.0
Storage | 128/256 GB
Battery | Li-Ion 4000 mAh, non-removable, graphene-enhanced
Display | 1644 x 3840 pixels, 21:9 ratio (~642 ppi density), 6.50 inches, OLED, 60Hz, Dolby Vision, HDR10+

## Device picture

![Xperia 1II](https://www.sony.com.hk/image/7723dbfd94d35c7e9b9b854576fbe90d?fmt=pjpeg&wid=2000&bgcolor=F1F5F9&bgc=F1F5F9&qlt=85)

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator

## To use it:

```
fastboot flash recovery recovery.img
```


## Thanks

- [FsCrypt fix by mauronofrio](https://github.com/mauronofrio/android_bootable_recovery)

- [Decryption by bigbiff](https://github.com/bigbiff/android_bootable_recovery)

- [Oneplus 8 TWRP by mauronofrio](https://github.com/mauronofrio/android_device_oneplus_instantnoodle_TWRP)

- [Xiaomi sm8250 TWRP device tree by sekaiacg(aka.SKKK)](https://github.com/sekaiacg/android_device_xiaomi_umi_TWRP)

- [Sony SM8250 Kernel Source by hellobbn](https://github.com/hellobbn/android_kernel_sony_sm8250)

- [Xperia 1 II Old TWRP device tree by Cjybyjk](https://github.com/cjybyjk/sony_pdx203_twrp)

- [Xperia 1 II Old OrangeFox device tree by EggOxygen, although he delete it](https://github.com/ShirokaneShizuku/twrp_device_sony_pdx203)

- [Xperia 1 II lineage 17.1 device tree by sjllls, the origin one](https://github.com/sjllls/android_device_sony_pdx203))

## Credits

- [Sjllls](https://github.com/sjllls)
- [Hellobbn](https://github.com/hellobbn)
- [Cjybyjk](https://github.com/cjybyjk)
- [SekaiACG](https://github.com/sekaiacg)
- [EggOxygen](https://github.com/eggoxygen)
- [mauronofrio](https://github.com/mauronofrio)
- [lolipuru](https://github.com/lolipuru)
- Shion Kagurazaka, the suck one, it's me.
