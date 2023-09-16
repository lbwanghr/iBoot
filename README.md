# iBoot
A shortcut on the menubar to the Startup Disk panel, which is the shortest and safest path to boot from Windows on macOS.

## TestFlight
Please visit the following testflight link to install the app for free.

https://testflight.apple.com/join/yjWEwvq1 

Demo on YouTube:

https://www.youtube.com/watch?v=te4bWl2PwoM&t=12s

## AppStore
If you like it, you can buy it on the App Store:

https://apps.apple.com/cn/app/iboot-startupdisk-shortcut/id6465744342?l=en&mt=12

## Advanced Usage
In **geekmode**, you can reach the destination with one click on the icon, but you will lose access to the pull-down menu.

In AppStore version, there is no Geekmode entry due to the Apple Review Guideline. 

However you can open **Terminal** and type the following command to enable the geekmode.

`defaults write top.mightycounty.BootCampSwitcher geekmode true`

Or you can type the following command to disable the geekmode. 

`defaults write top.mightycounty.BootCampSwitcher geekmode false`

Changes to geekmode will take effect after the next launch.

Additionally, you can type `sudo killall iBoot` to quit **iBoot** if you can't find a quit button.

---
Any questions please email lbwanghr@icloud.com.
