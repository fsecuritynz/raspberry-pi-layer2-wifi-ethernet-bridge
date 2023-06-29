# raspberry-pi-layer2-wifi-ethernet-bridge
Raspberry Pi Layer2 WiFi Ethernet Bridge does just that:
- Takes a WPA2 PSK connection over WiFi and bridges it to ethernet
- This is a layer-2 bridge, and will place the connected ethernet computer in the same LAN
- NO NAT, NO ROUTING

[internet]-[router + wifi] ----wif---- [(wifi)raspberry-pi(ethernet)]-[pc-ethernet]

# requirements
apt update && apt install -y parprouted dhcp-helper


YOU NEED TO SETUP YOUR WIFI IN /etc/wpa-supplicant/wpa-supplicant.conf FIRST

