# Qt Creator Arduino configuration

This repository creates a template that you allows you to configure Qt Creator as your Arduino's IDE.

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
* Serial monitor (for example GTKTerm version > 0.99 or picocom, or screen or minicom)

## Boards supported and tested
Theoretically this template can support all boards that Arduino-MakeFile support.

## How to install
In this repository you will find these templates in folders:

* arduino_sketch_style
  + This folder contains a Sketch style Arduino template
  + (the same style used in the official Arduino IDE)


INSTALLATION INSTRUCTIONS
-------------------------

1) Clone this repo as advised in http://doc.qt.io/qtcreator/creator-project-wizards.html.

2) Click on:
File > New File or Project
Select AVR > Arduino project using sketch.

## Based on work of: 
* Cleiton Souza (cleiton@tutamail.com)
* Jason Jorgenson (jjorgenson@gmail.com)
