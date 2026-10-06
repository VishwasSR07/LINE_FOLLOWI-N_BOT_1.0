# LINE_FOLLOWI-N_BOT_1.0
A BOT which follows the lines when callibrated..


USE ARDUINO IDE //for writing and uploading the code
CP2102 ; CP340 ; FTDI FT232 // must install the drivers before uploading the code to ESP32

Steps to install the drivers:   Download the driver from the manufacturer's official site (Silicon Labs for CP210x, WCH for CH340). Avoid third-party download sites.
                                Unplug the ESP32, run the installer, then restart the Arduino IDE.
                                Plug the ESP32 back in with a data-capable USB cable.
                                Open Device Manager → Ports (COM & LPT). You should see something like "Silicon Labs CP210x (COM5)" or "USB-SERIAL CH340 (COM7)".
                                In Arduino IDE, choose Tools → Port and pick that COM port..
                  // for MAC:   Mac: CP210x and CH340 may need the same drivers on older macOS. Newer versions usually include them.
                  // for Linux: drivers are built in. If the port is denied, add yourself to the dialout group with sudo usermod -a -G dialout $USER, then log out and back in..

UPLOAD>>CALLIBRATE>>START                  
