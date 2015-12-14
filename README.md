DroneDirect
==============
This is a directional control library for [Dronekit](http://dronekit.io/).

## Run instructions

### Setting up your Solo development environment

1. Install solo-cli with `pip install -UI git+https://github.com/3drobotics/solo-cli` (you may need sudo for pip installs)
1. Install virtualenv with `pip install virtualenv`

### Preparing your directory

1. Git clone this directory, then navigate to it in your terminal
1. Run `sudo pip install -r requirements.txt` to install dependencies

### Running code on Solo

1. Run `solo script pack` while connected to the internet to bundle your script
1. Turn on your Solo and connect to its Wifi from your computer
1. Run `solo script run <myscript.py>`

**only applies to code run onboard solo(i.e. helloworld, not virtual joystick)**

## Examples
Examples can be found in the Example folders

### helloworld.py
This program will draw 3DR in the sky. It is designed to be run onboard solo.
It utilizes DroneDirect which allows for directional control using dronekit
Default size(scale = 5.0) is 22x8 meters. Change the scale factor to increase size.

### template.py
This program is a template for using DroneDirect.

### virtual_joystick.py
This program will allow you to control solo's xy using an on screen joystick.
It is designed to be run on a GCS.
It utilizes DroneDirect which allows for directional control using dronekit

## License
LGPLv3
