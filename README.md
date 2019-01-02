#### Forked version of @adrianmihalko 
#### Original can be found here: https://github.com/MPParsley/ch340g-ch34g-ch34x-mac-os-x-driver

# ch340g-ch34g-ch34x-mac-os-x-driver

**OSX Yosemite 10.10.5**
Compatible driver for devices using the CH340G, CH34G or CH34X chipset. This chipset is used in several Arduino-clones.

## Introduction
On uploading sketches to CH340G arduinos **OS X Yosemite** will crash. To resolve this issue, please download and install the driver in this repo.

## Installation

* Relocate the old driver by issuing one of the following commands (my installation had both):
  * `mkdir ~/Desktop/arduino_usb_backup`
  * `sudo mv /System/Library/Extensions/usb.kext ~/Desktop/arduino_usb_backup`
  * `sudo mv /Library/Extensions/usbserial.kext ~/Desktop/arduino_usb_backup`
*  Restart your Mac.
*  Double-click on the `CH34x_Install_V1.3.pkg` file.
*  Restart your Mac.
*  Plug in your device. It should now be listed under the `/dev` directory. Examples:
  * `/dev/cu.wchusbserial1410`
  * `/dev/cu.wchusbserial1420`

## Troubleshooting

* Removed the troubleshooting section from the original document, as the directions solved my problem. 

Share this page to your friends working with CH340G arduinos working on Yosemite 10.10.5

Best,  
Carl Crott

p.s:
I have enough coffee but Adrian Mihalko could use more.

Buy him one at:   
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=adriankoooo%40gmail%2ecom&lc=SK&item_name=Adrian%20Mihalko&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)
