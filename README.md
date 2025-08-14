# TP-Link-Mr-6400-VX.X-Debrick-guide
How to Debrick TP-Link Mr-6400 
Some users tried to install openwrt on this model and then findout its useless because of this device limits on Size of overlay for installing needed plugins
and then cant install original firmware and stuck on openwrt just read this simple guide and done.

# Requirements:
- TFTP App
- Router Original Firmware

# How to:
 First download your MR-6400 just the version on the router label from here : https://www.tp-link.com/uk/support/download/tl-mr6400/
 for example if router is v5 you download v5 not v7.
 extract the archive file in a folder rename the .bin file to original.bin
 open cmd:
   cd /where/yourfile
- or you can right click in directory where .bin file is when holding Left Shift button and select open cmd here
 in cmd command :
    powershell
-now you should copy the commands from file in repo command.txt  in powershell

- a new .bin file will created there named tp_recovery.bin run tftp select the file directory and let it flash it
