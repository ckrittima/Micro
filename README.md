# Microprocessor Project

This project is about Counting people using Raspberry pi 4, picamera and OpenCV. If people are detected by a picamera it will count people around there and send result to https://thingspeak.com/channels/1396043 and if number of detected people greater than 0 it will light the led.

update the Raspberry Pi

> sudo apt-get update

Install the required dependencies

> sudo apt-get install libhdf5-dev

> sudo apt-get install libhdf5-serial-dev

> sudo apt-get install libatlas-base-dev

> sudo apt-get install libjasper-dev

> sudo apt-get install libqtgui4

> sudo apt-get install libqt4-test

Install the OpenCV in Raspberry Pi

> pip3 install opencv-contrib-python==4.1.0.25

Install other Required Packages

> pip3 install imutils

> pip3 install matplotlib

> sudo apt-get install python3-tk
