# connect_wifi
For mobilePC with Alpine Linux. As it is a little annoying to connect to a wireless access point, i made this to make it easy.

Put all in the path, and "chmod +x".

initwifi
Find the wireless access points around your device and shows their ssids.

setssid $1
Give ssid that you want to connect as a parameter.
And then input a password for it.
Then you will connect to the access point.

startssid $1
Give ssid that you want to connect.
If you have connected to the point once, you can connect to it without input password.


The informations about ssid and password are saved in the same directory.
