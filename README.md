# raspi-headless-conf
## turn on ssh
create blank "ssh" file on SD card

## wifi setup
create "wpa_supplicant.conf" on SD card:

>ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
>update_config=1
>country=<Insert 2 letter ISO 3166-1 country code here>
>
>network={
> ssid="<Name of your wireless LAN>"
> psk="<Password for your wireless LAN>"
>}
