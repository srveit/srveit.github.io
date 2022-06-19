layout: page
title: "Install Raspberry Pi OS"
permalink: https://srvet.github.io/installing-raspberry-pi-os

# Installation

I run oauth2-server on a server running [Raspberry Pi OS](https://www.raspberrypi.com/software).

## Install Raspberry Pi OS

Insert the microSD card into your computer.

- Download the installer [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
- Run the Raspberry Pi Imager.
- For Operating System select "Raspberry Pi OS Lite (32-bit)" under "Raspberry Pi OS (other)".
- For Storage select the microSD card.
- Click the settings gear in the lower right.
- Check "Set hostname" and enter "pi-auth".
- Check "Enable SSH".
- Choose "Allow public-key authentication only".
- Enter your public key, usually found in `~/.ssh/id_rsa.pub`.
- Check "set username and password".
- In "username" enter "oauth".
- Leave "Password" blank.
- Check "Configure wireless LAN".
- Enter your LAN's SSID.
- Enter your LAN's password.
- Select LAN country.
- Click "SAVE".
- Close "Advanced options" dialog by clicking "SAVE" button.
- Click "WRITE".
- Click "YES" to erase and install the OS in the microSD card.
- (You may be asked for your admin password to authorize writing the microSD card.)
- When the "Write Successful" dialog pops up, click "CONTINUE".
- Quit the Raspberry Pi Imager application.

Remove the microSD card from the computer and insert it into the Raspberry Pi. Power up the Pi.

Log into the Pi:

ssh oauth@pi-auth.local
