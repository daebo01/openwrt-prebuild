ASUS RT-AC59U V1 OpenWrt 21.02.1 Pre-release
============================================

Hardware
--------
- SoC: QCN5502
- Flash: 16 MiB
- RAM: 128 MiB
- Ethernet: 1 * GE WAN, 4 * GE LAN
- Wireless No1: QCN5502 on-chip 2.4GHz 4x4
- Wireless No2: QCA9888 pcie 5GHz 2x2
- USB: 1 * USB 2.0

Installation
------------
- Flash Initramfs image using OEM Firmware's web GUI
- Boot into OpenWrt and perform Sysupgrade with sysupgrade image.

What doesn't work
-----------------
- 2.4GHz wifi (QCN5502 on-chip)
  (I was not able to make this work, probably because ath9k requires
  some changes to support QCN5502.)

includes luci.
