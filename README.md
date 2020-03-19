# Qualcomm_atheros_firmware
If you get "Load missing firmware: ath10k **", while insatlling any linux system. Then click "No" and after installation is completed just clone this repository and install .deb file in following way.


#cd Qualcomm_atheros_firmware
#sudo dpkg -i firmware-atheros_20161130-5_all.deb

If any error shows up with unresolved dependencies, run
#sudo apt-get install -f


Another way to install .deb file is
#sudo gdebi firmware-atheros_20161130-5_all.deb
(If you dont have gdebi install it using "apt install gdebi-core")

After this just reboot the machine and you can now see the Wi-Fi option.

ENJOY!!!
