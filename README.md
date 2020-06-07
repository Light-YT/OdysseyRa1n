# How to install odysseyra1n on your phone

1 Restore rootfs with checkra1n

2 Jailbreak (Don't open the loader !!)

3 connect your iphone through usb and on your mac/linux : insert those following commands

MAC USERS To install homebrew if you don't have it : /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)”

To install iproxy : brew install usbmuxd

LINUX USERS To install iproxy sudo apt install libusbmuxd-tools

To launch the script (Both Mac users and Linux Users): /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/coolstar/Odyssey-bootstrap/master/procursus-deploy-linux-macos.sh)"

4 After the script finish it's task, open sileo, do all the updates and install libhooker package. Then reboot (manually, not pressing the reboot button in sileo) and rejailbreak.

Or else, run su /etc/rc.d/libhooker in a terminal like new term to start libhooker then sbreload

5 enjoy a stable experience and powerful experience with latest apt 2.1.5, libhooker and all package manager working alongside without problems. (Cydia UI got a little ios13 update that you will like. Thanks to kronos.)

# NOTE : i heavly recommend to install those 2 package first before trying to install tweaks : rocketbootstrap and preference loader from odyssey repo and bigboss. Else you may have a little (not happy) surprise when you will try to queue 50 tweaks then find out that sileo won't install anything because of (apt fix missing error)
