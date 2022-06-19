# Installation

I run oauth2-server on a server running <a href="https://www.raspberrypi.com/software/">Raspberry Pi OS</a>.

## Install Raspberry Pi OS

Insert the microSD card into your computer.

- Download the installer (<a href="https://www.raspberrypi.com/software/">Raspberry Pi Imager</a>).
- Run the Raspberry Pi Imager.
- For Operating System select "Raspberry Pi OS Lite (32-bit)" under "Raspberry Pi OS (other)".
- For Storage select the microSD card.
- Click the settings gear in the lower right.
- Check "Set hostname" and enter "pi-auth".
- Check "Enable SSH".
- Choose "Allow public-key authentication only".
- Check "set username and password".
- In "username" enter "oauth".
- Leave "Password" blank.
- Check "Configure wireless LAN".
- Enter your LAN's SSID.
- Enter your LAN's password.
- Select LAN country.
- Click "SAVE".
- Close "Advanced options" dialog.
- Click "WRITE".
- Click "YES" to erase and install the OS in the microSD card.
- (You may be asked for your admin password to authorize writing the microSD card.)
- When the "Write Successful" dialog pops up, click "CONTINUE".
- Quit the Raspberry Pi Imager application.

Remove the microSD card from the computer and insert it into the Raspberry Pi. Power up the Pi.

Log into the Pi:

ssh oauth@pi-auth.local
