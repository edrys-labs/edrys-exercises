# Edrys Labs
A couple of laboratories for [Edrys-Lite](https://edrys-labs.github.io).

To reuse a lab for your classroom, just click the deploy button of the desired lab. Or copy the configuration URL into the import dialog of the lab-configuration and upload it.  

Some labs use the [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs) terminal to upload the code to a connected arduino. For that the pyxtermjs server should run on localhost. 

The easiest way to do this, is by installing docker and running the following command:

```bash
docker run -it -p 5000:5000 --device=/dev/ttyACM0:/dev/ttyACM0 edrys-labs/pyxterm-server:latest
```
This will download the pyxtermjs terminal-server from docker-hub and run it in a secure environment.

Otherwise, you can install the server locally by following the instructions in the [module-pyxtermjs](https://github.com/edrys-labs/module-pyxtermjs).

## Arduino Blink

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/arduino_blink.yml)

https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/arduino_blink.yml

## Blockduino 

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/blockduino.yml)

https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/blockduino.yml

## Sum Of Two (C++)

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/sum_of_two(c++).yml)

https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/sum_of_two(c++).yml


## Arduino Blink - Windows

For Windows users, instead of the terminal, a NodeJs server is needed ro run locally on the station-machine.

Instructions on how to run the server can be found in the [edrys_windows_server](https://github.com/jh-488/edrys_server) repository.

[<img src="https://img.shields.io/badge/%F0%9F%9A%80%20-%20Deploy%20Lab%20-%20light?style=plastic" height="25" />](https://edrys-labs.github.io/?/deploy/https://raw.githubusercontent.com/edrys-labs/edrys-exercises/main/labs/blink_windows.yml)