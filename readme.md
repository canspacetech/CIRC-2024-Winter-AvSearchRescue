# CIRC 2024 GPS Beacon

## Description

This is a variety of information to support the CIRC 2024 Avalance Search and Rescue

## Usage during CIRC Search & Rescue task

To use the Astronaut GPS Beacon, connect to the open SSID "Isaac_Asimov"
* Astronaut IP will be accessible at http://10.10.11.1 Port 80
* Astronaut also accessible by Telnet at 10.10.11.1 Port 23
* Astronaut Beacon is a standard 802.11b/g/n 2.4Ghz access point on Channel 1
* See the Simulation folder in this repo for example output (GPS Beacon) Web/Telnet
  
## Setting up your own hardware for testing
* The microcontroller used for all devices is a ESP-32-S3 Dev board you can view [Here](https://www.digikey.ca/en/products/detail/espressif-systems/ESP32-S3-DEVKITC-1U-N8R2/16162648)
	* The code is written in the arduino IDE, which means you can likely use the code on other hardware with wireless functionality. The code uses common libraries and a standard UART GPS module
	*  Using the older common ESP32 WROOM/WROVER is likely code compatible.

## Authors

Torban Peterson - torban@torban.ca

## License
The MIT License (MIT)

Copyright (c) 2023 Torban Peterson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
