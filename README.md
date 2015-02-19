# RSSI signals without connecting

Fork from https://github.com/adamf/BLE/blob/master/ble-scanner.py

And some additional scripts to visualize it.

## Requirements

* bash 
* python
* python-bluez
* octave

On Ubuntu:

    sudo aptitude install python-bluez
    sudo aptitude install octave

## Running

    sudo python get-rssi.py

This will create a rssi.log file.

## Result

An example of result. With one node on my desk (red), one node on a desk of my colleague (blue), one node on the floor above ours (green), and one node on two floors down (magenta).

![RSSI signals](https://raw.githubusercontent.com/mrquincle/BLE/master/img/result.jpg)

## Copyrights

Everything that is not the python code is copyrighted:

* Author: Anne van Rossum
* License: LGPLv3, MIT, or BSD, your choice
* Date: Feb. 19, 2015
* Copyright: Distributed Organisms B.V. (https://dobots.nl)
