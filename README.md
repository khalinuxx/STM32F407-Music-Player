# STM32F407 Music Player
This project is a music player that uses an STM32F407 board to read WAV files from a USB drive and output audio through the port jack. The player also includes 5 buttons to control music playback, volume, and track selection.

## Hardware Requirements
To build this project, you will need:
* STM32F407 board
* OTG cable
* USB drive
* 5 buttons
* jack to jack cable
* Speakers

## Software Requirements

 To program the STM32F407 board, you will need a toolchain that supports ARM Cortex-M processors. We recommend using the STM32CubeIDE, which is a free integrated development environment (IDE) provided by STMicroelectronics.

## Usage
* Clone this repository to your local machine.
* Open the project in STM32CubeIDE.
* Build the project and flash it to the STM32F407 board.
* Connect the USB drive to the STM32F407 board.
* Connect the port jack to the audio output of the STM32F407 board.
* Connect the 5 buttons to the GPIO pins of the STM32F407 board.
* Power on the board.
* Use the buttons to control music playback, volume, and track selection.
## Configuration

 To configure the GPIO pins for button inputs, you can modify the main.c file in the project. The default pin configuration for the buttons is:

* Play/Pause: PA0
* Next Track: PA3
* Previous Track: PA5
* Volume Up: PA1
* Volume Down: PA2
