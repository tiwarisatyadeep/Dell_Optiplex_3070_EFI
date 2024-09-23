**macOS  Sonoma 14.7 (23H124) on DELL-OptiPlex-3070-MiniPC**
=============================================================

![System_Info](https://github.com/user-attachments/assets/b30d94f2-b9e6-4c81-be38-1093f3225365)

Configuration
=============

![image](https://github.com/user-attachments/assets/d8a076a6-1393-4b36-a851-8793b20396e7)


Repository
==========
Please download EFI from below path for Dell Optiplex 3070 (Intel core i3 9100T, 16GB RAM, Intel UHD Graphics 630)
https://drive.google.com/drive/folders/1vs8QYadZYyjsNeBjuN31kf9FZIY0Z5Zw?usp=sharing

Disclaimer:: We do not take any responsibility if your computer stops responding or stops booting. Please try at your own risk.

**BOOT Menu Changes**
=====================

**Disable**
Fast Boot
Secure Boot
Serial/COM Port
Parallel Port
VT-d (can be enabled if you set DisableIoMapper to YES)
Compatibility Support Module (CSM) (Must be off in most cases, GPU errors/stalls like gIO are common when this option is enabled)
Thunderbolt (For initial install, as Thunderbolt can cause issues if not setup correctly)
Intel SGX
Intel Platform Trust
CFG Lock (MSR 0xE2 write protection)(This must be off, if you can't find the option then enable AppleXcpmCfgLock under Kernel -> Quirks. Your hack will not boot with CFG-Lock enabled)

**Enable**
VT-x
Above 4G Decoding
Hyper-Threading
Execute Disable Bit
EHCI/XHCI Hand-off
OS type: Windows 8.1/10 UEFI Mode (some motherboards may require "Other OS" instead)
DVMT Pre-Allocated(iGPU Memory): 64MB or higher
SATA Mode: AHCI
