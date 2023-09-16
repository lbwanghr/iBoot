# iBoot
A shortcut on the menubar to the Startup Disk panel, which is the shortest and safest path to boot from Windows on macOS.

## TestFlight
Please visit the following testflight link for free trials.

https://testflight.apple.com/join/yjWEwvq1 

## AppStore
If you like it, you can buy it on the App Store.

https://apps.apple.com/cn/app/iboot-startupdisk-shortcut/id6465744342?l=en&mt=12

## Advanced Usage
In **geek mode**, you can reach the destination with one click on the icon, but you will lose access to the pull-down menu.

There is no entry for the geek mode in the GUI due to the Apple Review Guideline, however you can open **Terminal** and type the following command to enable geek mode.

`defaults write top.mightycounty.BootCampSwitcher geekmode true`

Or you can type the following command to disable geek mode. 

`defaults write top.mightycounty.BootCampSwitcher geekmode false`

Changes to geekmode will take effect after the next launch.

Additionally, you can type `sudo killall iBoot` to quit **iBoot** if you can't find a quit button.

---
Any questions please email lbwanghr@icloud.com.
