# enterprise-ntp-server-setup

## Project Overview
This project demonstrates how to configure an NTP server in Linux using Chrony to synchronize system time across multiple systems.

## Technologies Used
- Linux
- Chrony
- Networking
- Systemctl

## Project Architecture
Client Machines --> NTP Server

## Installation Steps
1. Install chrony
2. Configure chrony.conf
3. Enable chrony service
4. Verify synchronization

## Verification Commands

chronyc sources
chronyc tracking
timedatectl
