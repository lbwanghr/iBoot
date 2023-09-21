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

## Known issues
### Missing disk?
Sometimes you may find some of your disks are missing in the StartupDisk panel, don't worry, it's just not well been displayed due to the macOS. Feel free to click on an empty area where you think the disk should be placed, and you will notice the prompt changes just as you imagined.


---
Any questions please email lbwanghr@icloud.com.
