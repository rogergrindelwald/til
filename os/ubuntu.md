# Dual boot Ubuntu with Windows 10 (UEFI)
http://www.everydaylinuxuser.com/2015/11/how-to-install-ubuntu-linux-alongside.html

# Dual boot Ubuntu with Windows 10 on Acer Aspire
# NOTE: Acer Aspire is a bit different.
http://askubuntu.com/questions/627416/acer-aspire-e15-will-not-dual-boot

# List the Wireless Card
lspci -knn | grep Net -A2 && rfkill list

# Fix the Qualcomm Atheros Wireless Card issue
http://askubuntu.com/questions/708061/qualcomm-atheros-device-168c0042-rev-30-wi-fi-driver-installation
