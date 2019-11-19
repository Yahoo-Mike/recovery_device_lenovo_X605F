# TWRP device tree for Lenovo Smart Tab M10 wifi (TB-X605F)

## Release info
DO NOT INSTALL - COMPLETELY AT YOUR OWN RISK

This is still in development.  It is currently pre-alpha.  There's a lot of testing to do.

This is an unofficial build.

### About Device

![Lenovo Smart Tab M10](https://static.lenovo.com/ww/campaigns/2019/smarttab/lenovo-smart-tab-gallery-5.jpg "Lenovo Smart Tab M10 (TB-X605F)")

Recovery Device Tree for Lenovo Tab/Smart Tab M10 wifi (TB-X605F)
=================================================================
Component   | Specs
-------:|:-------------------------
Chipset| Qualcomm Snapdragon 450 (SDM450)
CPU | ARM Cortex-A53, Octa-Core, 1.8 GHz
GPU     | Qualcomm Adreno 506, 650 MHz
Memory  | 3 GB (soldered)
Shipped Android Version | 8.0 (Oreo), upgrade to 9.0 (Pie)
Storage | 32 GB (eMPC)
MicroSD | Up to 256 GB
Battery | 4850 mAh, Li-Po (non-removable)
Display | 1920x1200 pixels, 10.1", 224 px/in
Front Camera | 2.0 MP, fixed focus
Rear Camera  | 5.0 MP, auto focus
Wifi | dual band, 802.11a/ac/b/g/n 802.11n 5GHz
Bluetooth | v4.2
USB | USB-C charging/storage/OTG
Release Date | August 2018


** This device tree can be used to build TWRP for Lenovo Smart Tab M10 wifi (TB-X605F)**
** This is experimental.  Do NOT install, until a RELEASE version is available **

To build:

```
. build/envsetup.sh
lunch omni_tb-x605f-eng
make clean 
mka recoveryimage
```
