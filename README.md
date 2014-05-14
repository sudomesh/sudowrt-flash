# sudowrt-flash

This repository contains a script for flashing routers with the [sudowrt](https://github.com/sudomesh/sudowrt-firmware) firmware:

* flash_router.sh: Flashes your router with sudoWRT, based on OpenWRT

We plan to run this script on our build server in order to flash routers efficiently. I is also an expedient way for developers to get started quickly, over the manual process [documented on our wiki](https://sudoroom.org/wiki/Mesh/Firmware/Flash)

## Assumptions

The script makes the following assumptions:

* That the computer running the scripts have wget and tftp installed.
* That your router is a Ubiquiti Picostation 2.
* (Yes. We agree that this last one sucks. Please feel free to improve thise script.)

## Usage

1. Run the flash_router script as root:
    `sudo ./flash_router.sh`

The script will guide you through the entire process.

Happy Hacking!
