# How to use it

## To update Raspberry Pi

```
ansible-playbook -i hosts pi.yml
```

## To configure Hotspot Raspberry Pi

Create a secret.yaml file with two variables :

* ssid: RASPBERRY_PI_HOTSPOT
* wpa_passphrase: NOT_VALID_PASSWORD_TO_CHANGE

```
ansible-playbook -i hosts hotspot.yml
```
