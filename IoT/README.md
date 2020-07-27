# Recogg - IoT

###  ###

![Preview]()

Recogg uses the Raspberry-Pi in conjunction with other hardware components to perform comprehensive facial detection and facial verification. This automates the modern day attendance system and automatically reports attendance of a class to whoever needs it, eliminating the human error that can occur when manually taking attendance, especially in large classes.

<!-- BUILT WITH -->
### Built With

* [Python](https://img.shields.io/badge/python-3.6-blue)
* [Raspberry-Pi](https://img.shields.io/badge/raspberry--pi-4-green)
* Camera
* Bread Board
* Button
* Wires
* Resistors
* 20 x 4 I2C LCD Screen
* 4 x 4 Number Pad

### Features
* Accurate Facial Detection
* Capture Faces using Raspberry Pi Camera
* Update LCD Screen with Information
* Allow entry of a class uid using a keypad
* Turn On/Off using Button
* Mobile with a Portable Battery

## Getting Started
1. Set up Raspberry-Pi
    * [See hardware guide](#hardware-guide)
2. [Install necessary software](#installation)
3. [Set up necessary hardware](#hardware-guide)
4. [Download files in IoT repository](#installation)

### Prerequisites
* [Buy all necessary hardware](#built-with)
* [Install necessary software](#installation)
  
<!-- INSTALLATION -->
### Installation
1. [Install Python](https://img.shields.io/badge/python-3.6-blue)
2. Install Python libraries (Use linux terminal on Raspberry-Pi) 
   * PIP installer for Python3
   ```sh
   sudo apt-get install python3-pip
   ```
   * numpy
   ```sh
   pip install numpy
   ```
   * opencv
   ```sh
   pip install python-opencv
   ```
3. Clone the repo
```sh
git clone https://github.com/your_username_/Recogg.git
```

<!-- HARDWARE GUIDE -->
### Hardware Guide
* Raspberry-Pi setup
  * [Install Raspbian-OS](https://www.raspberrypi.org/documentation/installation/installing-images/)
  * Plug into keyboard and mouse, monitor (using HDMI), and power source
* [Keypad](https://maker.pro/raspberry-pi/tutorial/how-to-use-a-keypad-with-a-raspberry-pi-4)
* [LCD Screen](https://www.youtube.com/watch?v=F9IVtKa8C7Q)
* [Button](https://raspberrypihq.com/use-a-push-button-with-raspberry-pi-gpio/)
* [Camera](https://projects.raspberrypi.org/en/projects/getting-started-with-picamera)
* GPIO Pin Setup (Using BCM layout)
 * Keypad Pins (starting from the left)
   * Pin 1 - GPIO 5
   * Pin 2 - GPIO 6
   * Pin 3 - GPIO 13
   * Pin 4 - GPIO 19
   * Pin 5 - GPIO 12 
   * Pin 6 - GPIO 16
   * Pin 7 - GPIO 20 
   * Pin 8 - GPIO 21 
 * LCD Screen Pins
   * GND - GND
   * VCC - 5V
   * SDA - SDA1
   * SCL - SCL1
 * Button Pins
   * RXD0
   * 3.3V


<!-- USAGE EXAMPLES -->
## Usage

The IoT part of Recogg can be used for any kind of facial detection from an attendance system, to a door lock, to unlocking a computer. As this project is a prototype, we encourage improving it and using it for other purposes. **Make sure to list us as the original authors, especially if you use any of our code, documentation, or instructions.**

_For more examples, please refer to the [Documentation](https://example.com)_

## More Information ##

For more information licenses, contributing, errors, and other components, visit the [front of the repository](https://github.com/ashayp22/Recogg).



