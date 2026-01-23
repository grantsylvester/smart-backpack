# Smart Backpack
## Description
This repository houses the software and PCB design for the Smart Backpack being created by Purdue ECE49595SD Team 10E. The two main directories are:

- PCB
    - This directory houses the KiCad project files for our PCB.
- Software
    - This directory houses the PlatformIO project that has the code to be flashed onto the ESP32.

## Software To Do List
This is a list of modules in the software that we need to implement still:

- **main.c**
    - Integrate all components to run the main program in this file

- **gps.c** and **gps.h**
    - src and header files for GPS-related functions

- **imu.c** and **imu.h**
    - src and header files for IMU-related functions

- **rfid.c** and **rfid.h**
    - src and header files for RFID reader-related functions

- **sensors.c** and **sensors.h**
    - src and header files for all other sensors:
        - Water bottle sensors
        - Laptop detection pressure switches
        - Zipper state hall effect sensors
        - Haptic feedback motors
        - Back Cooling Fan (stretch goal)

- **app.c** and **app.h**
    - src and header files for Bluetooth connection and the web application.