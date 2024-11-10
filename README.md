This is a fork from LineageOS [repo](https://github.com/LineageOS/android_kernel_oneplus_sm8350)

## About this repo 
Aiming to config and build a kernel meet [Nethunter](https://www.kali.org/docs/nethunter/) requirements
Support Oneplus9 aka lemonade.(Should also works on OPlus9 pro,technically)
## Features
#### Kernel:
- Load/Unload kernel modules support
- System V IPC
- Android Binder IPC Driver

#### Bluetooth:
- HCI USB driver
- Broadcom protocol support
- Realtek protocol support
- HCI VHCI (Virtual HCI device) driver
- HCI UART driver
- UART (H4) protocol support
- HCI BCM203x USB driver
- HCI BPA10x USB driver
- HCI BlueFRITZ! USB driver

#### 802.11
- cfg80211 wireless extensions compatibility
- Generic IEEE 802.11 Networking Stack (mac80211)
- mac80211 mesh networking (pre-802.11s) support

#### Ethernet
- Ethernet drivers

#### Wireless LAN
- WLAN devices USB drivers

#### SDR
- Built in SDR support
- SDR drivers: Hackrf,Airspy

### USB control
- Host side USB
- USB Modem (CDC ACM) support
- Generic serial bulk in/out
- Abstract Control Model (CDC ACM)
- Object Exchange Model (CDC OBEX)
- Network Control Model (CDC NCM)
- Ethernet Control Model (CDC ECM)
- Ethernet Control Model (CDC ECM) subset
- RNDIS
- Ethernet Emulation Model (EEM)
- Mass Storage
- HID function

#### File System
- NFS support:client and server, version 2-4

## WARNING:CUSTOM KERNEL MAY BRICK YOUR DEVICE
**USE IT ON YOUR OWN RISK**
