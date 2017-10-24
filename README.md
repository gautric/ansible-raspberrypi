# How to use it


## to update Raspberry Pi

````
$> ansible-playbook pi_update.yml --inventory-file=./hosts -u pi
````


## to configure Hotspot Raspberry Pi


````
$> SSID=RASPBERRY_WIFI
$> PASSPHRASE=4slqvCIEbvhNd5dn

$> ansible-playbook pi_wifi.yml --inventory-file=./hosts -u pi  -v --diff -e "ssid=${SSID} wpa_passphrase=${PASSPHRASE}"
````
