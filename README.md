# ESXI_Cloned_VM_Reset_ID

- shell command:

        hostnamectl set-hostname 'newname'
        hostname
        sudo rm /etc/machine-id 
        sudo systemd-machine-id-setup
        cat /etc/machine-id
        reboot
