# TP-Link MR-6400 VX.X Debrick Guide

How to debrick a TP-Link MR-6400 router after failed OpenWRT installation.

Some users try to install OpenWRT on this model but then find it useless due to the device's limitations on overlay size (for installing needed plugins). Afterward, they can't reinstall the original firmware and get stuck on OpenWRT. This simple guide will help you recover your device.

## Requirements:
- TFTP application
- Router's original firmware

## Instructions:

1. Download your MR-6400 firmware (matching the version on your router's label) from:
   https://www.tp-link.com/uk/support/download/tl-mr6400/
   - Example: If your router is v5, download v5 (not v7)

2. Extract the archive file to a folder and rename the `.bin` file to `original.bin`

3. Open Command Prompt:
   - Navigate to your file's directory: `cd /where/yourfile`
   - Alternative: Hold Left Shift + Right-click in the directory and select "Open command window here"

4. In Command Prompt, run:
   powesehll

5. Now copy and run the commands from the `command.txt` file (in this repository) in PowerShell.

6. A new `.bin` file named `tp_recovery.bin` will be created.

7. Run your TFTP application, select the file directory, and let it flash the recovery firmware.   
