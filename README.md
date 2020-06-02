# Prerequisites
Step 1: Get a freshly jailbroken device with checkra1n.

Rootfs (I used checkra1n). If there is an error, jailbreak with safe mode and roots (aka: Restore System) through the Loader App.

After rootfs, jailbreak (turn off safe-mode)

# DO NOT TOUCH THE LOADER APP

Step 2: Install macOS / Linux utils

# IMPORTANT: Make sure to have the latest version of libusbmuxd or it will not work. Version 2.0.1 worked flawlessly.

macOS users can use brew install libusbmuxd

Also, make sure to have curl and iproxy installed. (most machines will have it already)

# Installing Sileo with Chimera1n
Step 1: Get procursus-deploy-linux-macos.sh install script

Step 2: Assuming its in your Downloads folder, run the following commands a terminal:

sudo bash ~/Downloads/chimera1n-deploy-linux-macos.sh

Type in your password to run the script.

When it asks for an ssh password / when it says root@127.0.0.1’s password:, type alpine.

You are going to have to do the step above twice.

Once the script terminates, you should see Sileo on your device! 🎉

# Post Installation
Step 1: Refresh your sources and upgrade all of your packages. 📦

Step 2 (Caution): To get Tweak Injection, install libhooker in the chimera repo.

iPhone X users have reported of bootloops. (beware!)

Step 3 (optional): Install any iOS 13 compatible tweaks to install the tweak dependencies. I just installed Cylinder.

# Troubleshooting
If tweak injection is not working:

Start libhooker with: /etc/rc.d/libhooker using ssh.

If you are bootlooped: jailbreak with safemode to ssh.

ALTERNATE: Install NewTerm (iOS 13) and run libhooker.

If you get Failed to get task for pid 1! after running libhooker:

# Run libhooker with su:

Type su in NewTerm, enter alpine, then /etc/rc.d/libhooker.

DO NOT install RocketBootstrap from https://rpetri.ch/repo. Use the one from Chimera Repo
