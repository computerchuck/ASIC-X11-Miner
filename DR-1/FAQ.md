## Frequently Asked Questions


### Is Power Supply Included?

No. A power supply unit is not included, and you will need to provide an ATX PSU. There are 2 PCI-e connectors for +12V DC input and only one of them is required. You can use either PCI-e 6 Pin or 8 Pin.

### Is Rasperry Pi Required for running? 

No. The mining software can run on Windows, Linux (Ubuntu) and [Raspbian](http://www.raspbian.org/) on Rasperry Pi. So either one would work.

### Can I use a cgminer downloaded from somewhere other than this repo?

No. You can only use the binaries provided by us to mining X11 coins. The current binary we are using is forked from cgminer and custom made to be able to talk with our miners. Downloading from other sources won't have the code we added. 

### Can I use the ethernet port to connect the miner?

No. You cannot do that currently. That port is used for a future module we're planing to release in future. The current ethernet port won't do anything.

### Where should I connect with the miner?

You will use the port besides the ethernet port which is a [USB Type B port](http://pcsupport.about.com/od/termsu/a/usb-type-b.htm) for connecting to your Rasperry Pi or computer.

### What if I disconnect the USB when running, will the miner continue mining?

No. The miner would stop mining because it needs the mining software to send/receive jobs from the network. It's strongly discouraged for users to disconnect the device when it is actively mining.
