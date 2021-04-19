# AnberPorts-Joystick
Emulated keyboard / mouse / joystick for the RK2020/OGA 1.0

# How to build
## Prereqs
libevdev-dev

### Build
```
git clone https://github.com/christianhaitian/oga_controls.git -b rk2020
cd oga_controls
make all
```
# Howto
Launch with `sudo ./oga_controls` or add current user to uinput via udev rule.

# /etc/udev/rules.d
```
SUBSYSTEM=="misc", KERNEL=="uinput", MODE="0660", GROUP="uinput"
```

## Support the project

[<img src="https://raw.githubusercontent.com/krishenriksen/AnberPorts/master/sponsor.png" width="200"/>](https://github.com/sponsors/krishenriksen)

[Become a sponsor to Kris Henriksen](https://github.com/sponsors/krishenriksen)
