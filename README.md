# ESXI_Cloned_VM_Reset_ID

- shell command:

    hostnamectl set-hostname 'newname'
    rm /etc/machine-id 
    systemd-machine-id-setup
    cat /etc/machine-id
