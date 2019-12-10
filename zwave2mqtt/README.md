# Running Zwave2Mqtt on (SystemD) linux using docker

## Installation

```
wget -O - https://raw.githubusercontent.com/cliviu74/scripts/master/zwave2mqtt/install.sh | bash
```

## Update

Systemd will pull the "latest" zwave2mqtt image and run it. A simple service restart will run the newest available version

```
systemctl restart zwave2mqtt
```