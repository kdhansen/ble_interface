# Bluetooth Low Energy Interface for Robots

This service depends on experimental Bluez features. Turn them on by modifying /lib/systemd/system/bluetooth.service 

ExecStart=/usr/lib/bluetooth/bluetoothd

to

ExecStart=/usr/lib/bluetooth/bluetoothd --experimental
