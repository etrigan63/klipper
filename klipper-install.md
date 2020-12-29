# Introduction

The purpose of this document is to provide a set of step-by-step instructions to install [Klipper](https://klipper.org) on a Formbot/Vivedino Troodon CoreXY 3D Printer (both models).

## Conventions

* Inline links will be used to reference software that can be downloaded.
* Commands issued in a terminal will be presented in `block format`

## Materials needed

* Vivedino Troodon 3D printer (300 or 400 model)
* Raspberry Pi (Zero, 3B+, 4B+)
* Micro SD Card (32GB)
* A set of Metric Hex Keys
* A computer (Windows, Mac or Linux)
* SD/MicroSD Card Reader (if not built-in to computer)
* [Raspberry Pi Imager](https://www.raspberrypi.org/software/)
* SSH Terminal - [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html) (Mac & Linux users can use `ssh` command inside the terminal)
* Plain Text Editor - [Notepad++](https://notepad-plus-plus.org/downloads/) (Windows users only. Mac/Linux have text editors provided)

## Step 1 - Prepare Raspberry Pi Base OS Image

### Materials Needed

* Micro SD Card
* Computer
* SD/MicroSD Card Reader
* Raspberry Pi Imager
* Plain Text Editor

1. Download and install Raspberry Pi Imager (link provided at top of document).
2. Insert MicroSD Card into reader and connect to computer.
3. Launch Raspberry Pi Imager

![RPI-Imager-01](./images/rpi-imager-01.png)

4. Click on "Choose OS"
5. Select "Raspberry Pi OS (other)"

![RPI-Imager-02](./images/rpi-imager-02.png)

6. Select "Raspberry Pi OS Lite (32-bit)"

![RPI-Imager-03](./images/rpi-imager-03.png)

7. Select your SD card from the dropdown.
8. Click the "Write" button.
