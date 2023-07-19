# Arduino Project: School Alarm System

This is an Arduino project that demonstrates school alarm system . The project uses the Arduino programming language and can be customised for similar projects

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Hardware Setup](#hardware-setup)
- [Software Setup](#software-setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Features

-  Set time and date using keypad and LCD screen
-  Backup battery to keep the RTC running in case of power outage
-  Set alarm times with push buttons
-  Interface with alarm speakers
-  User friendly interface 

## Requirements
To run this project, you will need the following components:
- Push button
- ISD2560
- ATmega32
- 2004 LCD
- 10k pot
- LA4445 audio amp module
- DS1307 RTC
- Cr2032 holder
- Cr2032 coin cell
- 10k resistor
- 100uF capacitor
- 100nF capacitor
- 22pF capacitor
- 16mhz xtal

## Hardware Setup
Setup the the hardware as shown below:

![image](https://github.com/cgardesey/smart_security_firmware/assets/10109354/3b127681-51dc-4175-b936-d415535cf182)


## Software Setup
1. Install the Arduino IDE (Integrated Development Environment) from the [official Arduino website](https://www.arduino.cc/en/software).
2. Connect your Arduino board to your computer using a USB cable.
3. Open the Arduino IDE and select the appropriate board and port from the **Tools** menu.
4. Create a new sketch in the Arduino IDE.
5. Copy and paste the code from the `Smart_Security.ino` file into your sketch.
6. Save the sketch with a meaningful name.

## Usage
1. Upload the **school_alarm_system_firmware.ino** sketch to the Arduino board by clicking the **Upload** button in the Arduino IDE.
2. The LED connected to the Arduino board should start blinking at a fixed interval.
3. Experiment with the code to and customize to suit your needs.

## Contributing
Contributions to this project are welcome. If you would like to contribute, please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Submit a pull request with a clear description of your changes.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute this project as needed.
