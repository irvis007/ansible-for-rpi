# ansible roles for RPI

Here will be general overview

## Requirements

### to be adjusted,

- Flash a **clean** Raspbian Lite image on an SD card
  URL: https://www.raspberrypi.org/downloads/raspbian/
  Mac: Use [ApplePI-Baker](https://www.tweaking4all.com/software/macosx-software/macosx-apple-pi-baker/)
- Enable SSH on the Raspberry (it is disabled by default). You can:
    - use `raspi-config` to enable SSH
    - create a file `/boot/ssh`
- Find the IP address your router will give to the RPI
- You need Ansible installed on your local computer (not the Raspberry Pi)
- Install SSHPass:
  - Ubuntu: `sudo apt install sshpass`
  - MacOS: `brew install http://git.io/sshpass.rb`

## Installation


## History

## todo

- preparing control machine - install ansible-galaxy roles, packages, etc
- prepare first-run script, only user and password auth, setting up ssh keys
- make comments
- develop OpenVpn Installation
- develop OpenVpn Configuration
- develop Transmission Installation and configuration


## Materials
- https://github.com/stibbons/ansible-rpi-pihole.git
