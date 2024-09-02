# NetManager Wazuh
Netmanager Wazuh is an extension to Netmanager used to automate network appliances log integration into wazuh.

### Requirements
This script requires a GNU/Linux environment to execute. Additionally, it also requires:
1. [NetManager](https://github.com/MuhamadAjiW/NetManager) (Ver. 1.0)
2. Wazuh (Ver. 4.8.2)
3. Rsyslog (Ver. 8.2112.0)

### Installation
This script requires placement inside NetManager's extension folder. Allow execution of script using
```
./chmod +x netmgr_wazuh
```

### Usage
This script is cli based, show list of commands using
```
./netmgr_wazuh -h
```

### Notable Features
- Device log addition and removal
- Registered device data management
- Extension abstraction using library interfaces to add support to more devices

## Credits
> [MuhamadAjiW](https://github.com/MuhamadAjiW) <br/>
> [akmaldika](https://github.com/akmaldika)