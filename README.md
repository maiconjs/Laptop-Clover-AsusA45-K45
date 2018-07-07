# Laptop-Clover-AsusA45-K45
Clover with fixes for Asus A45 and K45

* Mic Fixed Witch my build AppleALC + Lilu.
* Full PowerManagment with XCPM
* USB Fixeds
* Sleep
* Others Fixeds in DSDT
* Webcam
* Kexts for Wifi Atheros AR9285 and Bluetooth AR3011

Install all kexts contained in Other folder, in the directory /Library/Extensions/. You can use the KCPM Utility Pro, which can be downloaded at this link:

https://www.firewolf.science/2016/09/kcpm-utility-pro-v6-brand-new-kexts-ezinstaller-macos-sierra-supported-repairing-permissions-configuring-rootless-and-more/


It is recommended that you have a patched bios with CFGLock (MSR 0xE2), and you want that. Perform the patch may not be so friendly, but it's not that complicated, but requires attention. You must have a bios dump, and for that, you need a bios programmer (maybe the arduino works), and you need to open your laptop, get to the motherboard, locate the bios chip, plug the programmer into the chip and extract a bios file. There are a few ways to apply the patch, here's a friendly:

https://www.insanelymac.com/forum/topic/285444-uefipatch-uefi-patching-utility/

The advantages of using the patch are:
you won't have to use nullcpu or patched AICPUPM. 
