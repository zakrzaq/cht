# NMCLI

NMCLI (Network Manager CLI) is a CLI tool for managing networks on Linux systems.

## Commands

**nmcli dev** - show all devices

**nmcli dev show** - device details

**nmcli dev status** - device status

**nmcli radio <device>** - radio status

**nmcli radio <device> on/off** - turn radio on / off

**nmcli dev <device> list** - list available networks

**sudo nmcli dev \<device\> connect <network-ssid>** - connect to network

**sudo nmcli dev <device> connect <network-ssid> password <password>** - connect with password

**nmcli con show** - show all saved networks

**nmcli con up / down <ssid/uuid>** - connect /  disconnect to network
