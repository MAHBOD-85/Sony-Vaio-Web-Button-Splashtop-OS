# Splashtop OS for Sony Vaio laptops
A copy of Splashtop OS for the Sony Vaio laptops with installation instructions

## DISCLAIMER
Vaio is a trademark of Sony Corporation and Splashtop OS is a trademark of Splastop Inc. This repository is for archival purposes.

## Installation instructions
Step 1: Copy SPLASH.DAT SPLASH.000 and splash.idx to the root of your C: drive.

Step 2: get the UUID of the C: drive partition using blkid

Step 3: Open splash.idx in notepad and replace UUIDGOESHERE with your actual UUID of the partition (for NTFS it should be 16 characters formatted like 0123456789ABCDEF)

Step 4: Shut off your laptop, Press the web button and go through the first time wizard (if the browser does not open after that you can reboot)

Step 5: Enjoy this piece of computer history

### Attention
The installation here has outdated browsers meaning only old compatible sites like frogfind, google, the old net, etc. will work with it. If you can find a way to hack in a more recent version send a pull request.
