# Dell Optiplex 7060 OpenCore EFI

![](https://github.com/lehonning/Optiplex-7060-SFF-OpenCore-EFI/blob/main/Ventura%2013.6.6.png)

## Tested macOS version:
macOS 13.6.6 Ventura using OpenCore 0.9.8

## System configuration
- Intel Core i5-8500 3.0GHz
- 8GB DDR4-2666MHz RAM
- Intel UHD Graphics 630
- WD SN720 512GB SSD

## Confirmed working
1) Ethernet
2) FileVault
3) Turbo boost and CPU frequency
4) iGPU Acceleration
5) HDMI output
6) DisplayPort output
7) USB and USB-C ports


## Not working or might not work
1) Sleep (sometimes it works, working on fix)
2) DRM (working on fix)


## Unknown (not tested)
1) Dual Monitor
2) iCloud
3) iMessage
4) Dual Boot

## SMBIOS
Remember to generate your own SMBIOS, you can use the following tool:
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
