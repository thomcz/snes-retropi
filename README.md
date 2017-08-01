# snes-retropi

based on: https://www.youtube.com/watch?v=j5dXx0NhLxg
## Hardware
parts:
- Raspberry PI Zero
- Super Nintendo Controller
- Powerboost 500c - https://www.adafruit.com/products/1944
- Lithium Ion Polymer Battery (3.7v 500mAh) - https://www.adafruit.com/products/1578
  - [instead bought this and took the electric](https://www.amazon.de/gp/product/B01DPBAYSS/ref=oh_aui_detailpage_o01_s00?ie=UTF8&psc=1)
- Slide Switch
- Mini HDMI to HDMI

[wiring](https://www.dropbox.com/s/ejuknjfanwvcx2d/sns-005z%20wiring.png?dl=0)

[case](https://www.dropbox.com/s/b372gvkajdp7i3q/sns-005z%20back.png?dl=0)

## Software
[install retropi 4.2 zero](https://github.com/retropie/retropie-setup/wiki/First-Installation#installation) 

press F4 to enter commandline

sudo raspi-config
 - localisation options -> change locale
 - localisation options -> change keyboard layout
 - interface options -> enable ssh
 - advanced options -> expand filesystem

reboot

[config wlan](https://github.com/thomcz/coding-collection/wiki/Raspberry-Pi)

reboot

start Retro pi setup
- sudo /home/pi/RetroPie-Setup/retropie_setup.sh
- manage packages -> manage driver packages -> gamecondriver
- configuration / options -> configure 2 snes controller

**Don't upgrade because gamecom diver won't work with newer version!!**

