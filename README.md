# Qt Creator Arduino configuration

This repository creates a template that you allows you to configure Qt Creator as your Arduino's IDE.

## About Qt Creator
Qt Creator provides a cross-platform where you can developer from Windows, Linux or Mac. Is a very advanced IDE when provide a lot of smart things to help you develop more quickly and easily. Some main features of Qt Creator:
- Rapid code navigation tools
- Syntax highlighting and code completion
- Static code checking and style hints as you type
- Support for source code refactoring
- Context sensitive help
- Code folding
- Parenthesis matching and parenthesis selection modes

With all these features and more, Qt Creator can be lightweight, and for me, is one of the best IDE's available.


## About template
This repository creates a template that you allows you to configure Qt Creator as your Arduino's IDE.

What you need to use (*pre-requisites*):
* PC running Linux
- Windows and Mac can use it too, but some small changes are necessary
- In the future I will provide files ready to use in all environments
* Arduino IDE > 1.6.3
  + http://www.arduino.cc/en/Main/Software
* Arduino-Makefile 1.3.4
  + https://github.com/sudar/Arduino-Makefile
* Qt Creator > 3.3.1
  + http://www.qt.io/download-open-source
* GTKTerm version > 0.99
  + Can be any other serial monitor, but I chose it because is very lightweight

## Boards supported and tested
Theoretically this template can support all boards that Arduino-MakeFile support, it's mean:
* Supports all official AVR-based Arduino boards
* Supports chipKIT
* Supports Teensy 3.x (via Teensyduino)

I Already tested successfully with:
- Arduino Mega 2560
- Arduino Pro
- Arduino Uno

If you have tested any other boards, please tell me about your experience!


## How install
In this repository you will find these templates in folders:

* arduino_sketch_style
  + This folder contains a Sketch style Arduino template
  + (the same style used in the official Arduino IDE)


INSTALLATION INSTRUCTIONS
-------------------------

1) Clone this repo in template in [QT_CREATOR_PATH]/templates/wizards/ 

2) Click on:
File > New File or Project
Select AVR > Arduino project using sketch.

## Based on work of: 
* Cleiton Souza (cleiton@tutamail.com)
* Jason Jorgenson (jjorgenson@gmail.com)
