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
-  Backup battery to keep the RTC perppertually running in case of poewr outage
-  Set alarm times with push buttons
-  Interface with alarm speakers
-  User friendly interface 

## Requirements
To run this project, you will need the following components:
- Two Arduino board (e.g., Arduino Uno or Arduino Nano)
  The two boards will communicate serially. One board will serve as the master and the other will serve as the slave
- RTC
- 20x4 LED
- 4x4 Keypad
- Sim800 or sim900
- PIR's
- 120db buzzers
- Switch (Toggle, push button or slide switch)
- Terminal blocks (optional)
- 12V 5A power adapter (with stable output)
- Flexible wire calbe
- Packaging (Junction box, 3D moulded plastic box, wooden box etc)
- Resistors
- Transistors
- Capacitors
- Jumper wires
- Breadboard (optional, for prototyping)

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
