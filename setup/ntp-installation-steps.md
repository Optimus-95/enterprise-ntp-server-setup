# Installation steps for RHEL:

dnf install chrony*

vi /etc/chrony.conf

# Installation steps for Ubuntu:

apt install chrony*

vi /etc/chrony/chrony.conf

timedatectl set-timezone Asia/Kolkata

timedatectl set-ntp true
