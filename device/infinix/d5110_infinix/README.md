Infinix Hot 2 X510 (Android One)
===============================================

Specifications:
--------------
- CPU      : Mediatek MT6580 Quad-Core @ 1.3GHz
- CPU ARCH : ARM CORTEX-A7
- GPU      : ARM Mali-400MP2
- Memory   : 1GB or 2GB RAM
- OS       : Android 5.1 (Android One)
- Storage  : 16GB (Expendable up to 32GB)
- Battery  : 2500 mAh
- Display  : 5" 1280 x 720 px
- Camera   : 8MPx with LED Flash & 2MPx Front
- Colors   : Black, White and Gold


![Infinix](http://infinixmobility.com/wp-content/uploads/images/x510-kv-1.jpg "Infinix Hot 2")


Device Tree for compiling CyanogenMod 13.0


Note:
Before you compile, please take note of these
- We have the 1GB RAM version
- It came with Android One
- We used kernel and boot.img details from Android One ROM but the partitions size are from Infinix ROM
- If you have 2GB RAM version, you have to change [this](https://github.com/d5110-devs/android_device_infinix_d5110/blob/cm-13.0/device_d5110_infinix.mk#L141) line, changing `phone-xhdpi-1024-dalvik-heap.mk` to `phone-xhdpi-2048-dalvik-heap.mk`
- Or if you want to use Android One partitions scheme, you need to change [these](https://github.com/d5110-devs/android_device_infinix_d5110/blob/cm-13.0/BoardConfig.mk#L36-#L39) lines.


Work in progress ...

Will eat your cat !

