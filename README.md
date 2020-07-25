# Disclaimer
I am not responsible for any damage caused to your components, data loss, or anything else that may happen throughout this process. Follow this guide at your own risk! The steps listed below worked for my components.

This is an educational purpose only, potential mac users can try the flavor before investing in that ecosystem.

**Use EFI(GPU FIXED)** folder as your EFI folder, that fixed the iGPU acceleration issue\
I have tested this on **macOS Mojave 10.14.6**

I didn't have access to a mac\
I have used .raw from [Olarila](https://www.olarila.com/topic/6278-new-vanilla-olarila-images/) to make my boot image

## My Hardware
- CPU: Intel i5 8400
- GPU: intel UHD 630
- Motherboard: Gigabyte B360M-HD3
- HDD: 119GB ADATA SU800NS38 (SSD)
- RAM: Leven 8GB Single-Channel @ 1197MHz (17-17-17-39)
- Monitor: LG IPS FULLHD (1920x1080@59Hz) connected via HDMI 1.4

## Bios Settings
- Bios Version: F11
- Loaded optimised default then

### disabled

### enabled

## What's Working
- Sleep/Restart/Shut Down
- Audio
- Ethernet
- USB Mouse/Keyboard

## What's Not Working
~~GPU only 7 MB~~ GPU is working fine

## Task List

- [X] Get full acceleration from iGPU
- [X] Built it using Olarial High Sierra Package

**** You need to generate SmUUID, SerialNumber, BoardSerialNumber (MLB same) using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) 

and input that into config.plist using [ProperTree](https://github.com/corpnewt/ProperTree)****
