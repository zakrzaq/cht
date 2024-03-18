# BLUETOOTHCTL

Management of Bluetooth devices in Linux

## Requirements

`sudo apt install bluez*`

`sudo systemctl enable bluetooth.service`
`sudo systemctl start bluetooth.service`

`modprobe btusb`

`bluetoothctl`

## Commands

**help**

**exit**

**power on** / **power off**

**devices** - list devices

**paired-devices** - list available devices

**scan on** / **scan off** - enable scanning for new devices

**pair <mac:address>** - pair device

**connnect <mac:address>** - connect device

**trust / untrust <mac:address>** - trust device

**remove <mac:address>** - remove device
