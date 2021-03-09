# How to use it

## Push Local SSH key

    ansible-playbook -i hosts pi_upload_ssh_key.yml --ask-pass

## To update PiHole server

    ansible-playbook -i hosts pi_hole.yml

## To update Raspberry Pi

    ansible-playbook -i hosts pi_update.yml

## To configure Hotspot Raspberry Pi

Change the ssid into the correct hosts_var.
The _wpa_passphrase_ will be prompted. 


    ansible-playbook -i hosts pi_hotspot.yml 

