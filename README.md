# raspberryPiZeroWWifiClientAPMode
Raspberry Pi Zero W Wifi Client AP Mode (AP-STA)    

[https://github.com/billz/raspap-webgui/wiki/RPi-Zero-W-AP-STA-mode]    

## connect to your WiFi network in headless mode    
[https://github.com/billz/raspap-webgui/wiki/FAQs#how-do-i-prepare-the-sd-card-to-connect-to-wifi-in-headless-mode]    
```
/boot/wpa_supplicant.conf    

ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
country=GB

network={
    ssid="my_SSID"
    psk="my_PSK"
    key_mgmt=WPA-PSK
}
```

## create ssh in boot folder

## 
