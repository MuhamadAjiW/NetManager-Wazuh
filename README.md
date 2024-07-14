# Wazuh Netmanager
> by MuhamadAjiW

## What is this?
Simple Bash script to automate [wazuh](https://wazuh.com/) and network appliance integration and management. Automates the chore of managing `rsyslog.conf`, `ossec.conf`, and the hardwares itself for external network appliances

## Features
- File input (assign/remove nodes in batch)
- Remote command execution using ssh
- Describe and track all connected nodes
- Currently only supports Cisco-vIOS, but it is designed to be extendable to other vendors using a separate `lib` file

## Requirements
This script is written in a virtual Ubuntu 22.04.4 server environment
- bash
- a working ssh client
- sed
- grep
- sshpass

## Installation
Clone the repo, setup `./etc/wazuh_netmgr.conf` from the example, call `./wazuh_netmgr init`, and you are all set!