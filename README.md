# lepidopter raspi-config
Configuration tool for the Raspberry Pi

A customized version of raspi-config for 
[lepidopter](https://github.com/anadahz/lepidopter) Raspberry Pi image.

## Overview
Included functions in lepidopter raspi-config:
* Expand Filesystem - Ensures that all of the SD card storage is available to the OS
* Change Password
* Set up language and regional settings
* Configure Pi overclocking settings
* Addtional Options
  * Set NTP time
  * RaspberryPi Firmware Update
  * Upgrade installed programs
  * Configure Wifi settings
* Advanced configuration
  * Configure overscan if black bars are present on display
  * Change Hostname
  * Change the amount of memory made available to the GPU
  * Enable/disable SSH service
  * Update raspi-config
* ooniprobe related settings
  * Update ooniprobe

## TODO
You can find the TODO tasks by running from the root of the project:
  grep -rn TODO *

## Installation
```
wget https://raw.github.com/anadahz/raspi-config_lepidopter/master/raspi-config\
 -O /sbin/raspi-config
chmod +x /sbin/raspi-config
```

### Run
```
raspi-config
```

## Links
- raspi-config original [release](https://github.com/asb/raspi-config)
- [inspiration](http://www.raspberrypilabs.com/raspi-config-the-new-cli-tool-raspbian/)
- More information on [elinux.org](http://elinux.org/RPi_raspi-config)
