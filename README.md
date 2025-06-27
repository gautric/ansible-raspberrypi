# How to use it

## Push Local SSH key

    ansible-playbook -i inventory pi_upload_ssh_key.yml --ask-pass

## To update PiHole server

    ansible-playbook -i inventory pi_hole.yml

## To update Raspberry Pi

    ansible-playbook -i inventory pi_update.yml

## Register Raspberry Pi into AWS SSM

    ansible-playbook -i inventory pi_aws_ssm.yml

## To configure Hotspot Raspberry Pi

Change the ssid into the correct hosts_var.
The _wpa_passphrase_ will be prompted. 


    ansible-playbook -i inventory pi_hotspot.yml 

