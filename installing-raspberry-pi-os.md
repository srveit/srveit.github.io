<h2>Installation</h2>

<p>I run oauth2-server on a server running <a href="https://www.raspberrypi.com/software/">Raspberry Pi OS</a>.</p>

<h2>Install Raspberry Pi OS</h2>

<ul><li>Insert the microSD card into your computer.</li><li>Download the installer (<a href="https://www.raspberrypi.com/software/">Raspberry Pi Imager</a>).</li><li>Run the Raspberry Pi Imager.</li><li>For Operating System select "Raspberry Pi OS Lite (32-bit)" under "Raspberry Pi OS (other)".</li><li>For Storage select the microSD card.</li><li>Click the settings gear in the lower right.</li><li>Check "Set hostname" and enter "pi-auth".</li><li>Check "Enable SSH".</li><li>Choose "Allow public-key authentication only".</li><li>Check "set username and password".</li><li>In "username" enter "oauth".</li><li>Leave "Password" blank.</li><li>Check "Configure wireless LAN".</li><li>Enter your LAN's SSID.</li><li>Enter your LAN's password.</li><li>Select LAN country.</li><li>Click "SAVE".</li><li>Close "Advanced options" dialog.</li><li>Click "WRITE".</li><li>Click "YES" to erase and install the OS in the microSD card.</li><li>(You may be asked for your admin password to authorize writing the microSD card.)</li><li>When the "Write Successful" dialog pops up, click "CONTINUE".</li><li>Quit the Raspberry Pi Imager application.</li></ul>

<p>Remove the microSD card from the computer and insert it into the Raspberry Pi. Power up the Pi.</p>

<p>Log into the Pi:</p>

<p>ssh oauth@pi-auth.local</p>
