installation steps:
# NTP Server Setup Using Chrony

## Install Chrony

sudo apt update
sudo apt install chrony

## Enable Service

sudo systemctl enable chronyd
sudo systemctl start chronyd
