# MSI H110M Pro D

![Logo](https://github.com/x0u1/MSI-H110-PRO-D-Opencore-Hackintosh/assets/170177748/d00e8ef6-14f2-4230-81b4-86894c625b7b)


# Specs:

|         Hardware       |                   Model                     | 
|-------------------:|:------------------------------------------|
|               Motherboard | MSI H110M Pro D                               |
|             CPU | Intel Xeon E3-1220 v5                           |
|               GPU | AMD Radeon RX 580            |
|               SSD |  CRUCIAL BX500 CT120BX500SSD1 120Gb                         |
|        Network | Realtek RTL8111H  |


### What works

- [x] **Audio**: Realtek ALC887
- [x] **USB:** All ports

## Making the Bootable USB

### From macOS:
[**Link to Apple's Guide**](https://support.apple.com/en-us/HT201372)


1. Connect a >=16 GB pendrive.
2. Open *Disk Utility* and Erase the USB with the name: *MyVolume*.
3. Open *Terminal* and use the proper commands for your macOS installer:
- Monterey: `sudo /Applications/Install\ macOS\ Monterey.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Big Sur: `sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Catalina: `sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- Mojave: `sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`
- High Sierra: `sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/MyVolume`

![macos-big-sur-terminal-create-bootable-installer](https://user-images.githubusercontent.com/70513735/138585740-c3b1c801-a946-40d2-9a1f-7584b5e04af2.jpg)


### From Windows:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html)

### From Linux:

[**Link to Dortania's Guide**](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/linux-install.html)
