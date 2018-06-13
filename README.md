# Nano-Bakery
* Check device list if there is any connection
```
sudo nmcli dev
```
* Start WiFi
```
sudo nmcli r wifi on
```
* Scan Surrounding WiFi Sources
```
sudo nmcli dev wifi
```
* Connect to a WiFi Source (SSID and PASSWORD need to be replaced with your actual SSID and password)
```
sudo nmcli dev wifi connect "SSID" password "PASSWORD" ifname wlan0
```
* Check device is connected to relevant SSID
```
sudo nmcli dev
```
