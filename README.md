<h1>Reimage Sophos Firewall</h1>

<h2>Description</h2>
This is a lab demonstration on how to reimage sophos firewall. To reimage the firewall, we require a bootable USB flash drive. We can reimage Sophos Firewall with any firmware version.
<br />

<h2>Firmware installer and Utilities Used</h2>

- <b>[Sophos Firewall OS](https://www.sophos.com/en-us/support/downloads/firewall-installers)</b> 
- <b>[Win32DiskImager](https://sourceforge.net/projects/win32diskimager/)</b>, a free tool to create a bootable USB flash drive

<h2>Create a bootable USB flash drive </h2>

- Using this [link](https://www.sophos.com/en-us/support/downloads/firewall-installers), download Sophos firewall OS
- Install and run Win32DiskImager and maximize the window.
- Select the image file and device. Once selected click on write as shown in the screenshot below
<img src="https://i.imgur.com/gPOsp38.png"/>
- Once the write successful screen comes up, click ok and exit Win32 Disk Imager window

<h2>Reimage the firewall </h2>

- Connect a monitor to the SVGA or HDMI port of Sophos Firewall to monitor the installation and power off the firewall
- Insert the bootable USB flash drive you created
- Power on the firewall 
- To enter the BIOS, press the Delete key when Sophos Firewall is starting. Make sure USB Key is the first boot option in the BIOS.
<img src="https://i.imgur.com/yuw6tyb.png"/>
- Save the changes and exit the BIOS
- Sophos firewall will start reimaging Sophos firewall
- Monitor the installation.
<img src="https://i.imgur.com/JooXC0X.png"/>
- After the firmware is installed, remove the USB flash disk and type y to restart Sophos Firewall.
<img src="https://i.imgur.com/o6tpYTG.png"/>
- Now the firewall will restart. After that connect to the firewall using default IP and restore the device with backup configuration file. 


<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
