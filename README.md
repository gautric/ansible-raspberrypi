# How to use it

## To update Raspberry Pi

```
ansible-playbook -i hosts pi.yml
```

## To configure Hotspot Raspberry Pi

Change the ssid into the correct hosts_var.
The _wpa_passphrase_ will be prompted. 

```
ansible-playbook pi_hotspot.yml -i hosts
```
