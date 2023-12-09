## Setup
- Use DietPi: https://dietpi.com/docs/install/

## When disk space full because of `/overlay2` folders being full 
- run commands in this img
- ![image](https://github.com/skelstar/homeautomation-dockerstuff/assets/16521921/3089056b-1e5d-4459-9a9e-57809b7e2c1e)

# Setting up SD card (before booting)

**NOTE: are you plugged into the ethernet port on the router?!?**

Mac address: `B8:27:EB:53:DC:E0`

- Search SD card (just burned and plugged out/in) for "STATIC" to set static ip
- Set `AUTO_SETUP_TIMEZONE=Pacific/Auckland`
- `AUTO_SETUP_NET_ETHERNET_ENABLED=0`
- `AUTO_SETUP_NET_WIFI_ENABLED=1`
- `AUTO_SETUP_NET_USESTATIC=1`
- `AUTO_SETUP_NET_STATIC_IP=192.168.1.105`
- `AUTO_SETUP_NET_STATIC_MASK=255.255.255.0`
- `AUTO_SETUP_NET_STATIC_GATEWAY=192.168.1.1`

### Not trying yet!
- Set `AUTO_SETUP_NET_HOSTNAME=HomeAutomation`
- Set `AUTO_SETUP_HEADLESS=1`

```#---------------------------------------------------------------
# Entry 0
# - WiFi SSID: required, case sensitive
aWIFI_SSID[0]='LeilaNet2_5G'
# - WiFi key: If no key/open, leave this blank
# - In case of WPA-PSK, alternatively enter the 64-digit hexadecimal key returned by wpa_passphrase
# - Please replace single quote characters ' in your key with '\''. No other escaping is required.
aWIFI_KEY[0]='ec1122%f*&'
# - Key type: NONE (no key/open) | WPA-PSK | WEP | WPA-EAP (then use settings below)
aWIFI_KEYMGR[0]='WPA-PSK'
# - WPA-EAP options: Only fill if WPA-EAP is set above
aWIFI_PROTO[0]=''
aWIFI_PAIRWISE[0]=''
aWIFI_AUTH_ALG[0]=''
aWIFI_EAP[0]=''
aWIFI_IDENTITY[0]=''
aWIFI_PASSWORD[0]=''
aWIFI_PHASE1[0]=''
aWIFI_PHASE2[0]=''
# - Path to the certificate file, e.g.: /boot/mycert.cer
aWIFI_CERT[0]=''```
