# ansible-aruba-sw-cx
ansible aruba switch cx

# requirement
ansible

pyhton

ansible-galaxy collection install arubanetworks.aoscx

pip install --user ansible-pylibssh

pip install paramiko

# run using public key
ansible-playbook @your.ansible.yaml -i @your.inventory.yaml

# run using encyrypted password
ansible-playbook @your.ansible.yaml -i @your.inventory.yaml -vault-password-file @your.vault.password.file

# guide
https://github.com/aruba/aoscx-ansible-collection