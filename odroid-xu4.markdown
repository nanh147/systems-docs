# Odroid XU4

## Setup

### Dependencies

#### Point Grey FlyCapture

sudo apt-get install libraw1394-11 libgtkmm-2.4-1v5 libglademm-2.4-1v5 libusb-1.0-0

USB buffer:

http://stackoverflow.com/questions/31995954/pointgrey-sdk-hangs-on-startcapture

In `/media/boot/boot.ini`, scroll down to `bootargs` line and add `usbcore.usbfs_memory_mb=1000`

#### Vision System (Air)

sudo apt-get install python-dev python-pip
pip install numpy