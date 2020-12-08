# Project: Video Monitor

### Hardware Preparation:

1. Raspberry Pi 4B

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/raspberry.png" width="600" alt="add_resourse"/><br/>

2. Raspberry Pi Camera V2

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/camera.jpg" width="600" alt="add_resourse"/><br/>

3. Other devices that can watch the monitoring

### Software Preparation:

1. Raspberry Pi OS

2. Python 3

## Install the Camera on Raspberry Pi

1. Pull up the black strip in the red box of the picture.

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/set1.png" width="600" alt="add_resourse"/><br/>

2. Turn the blue side of the camera cable toward the USB interface.

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/set2.jpg" width="600" alt="add_resourse"/><br/>

3.Press the black strip and the installation is complete.

## Enable camera in system settings

1. Connect to the Raspberry Pi, and enter

    $ sudo raspi-config

2. select "Interfacing Option"

3. select "P1 Camera"

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/enablecam.jpg" width="600" alt="add_resourse"/><br/>

## Switch Python3

1. Enter

    $ which python

2. It will return a url like /usr/bin/python

    $ cd /usr/bin
    $ python --version

3. If it return python 2.7,
    
    $ sudo ln -sf python3 python

4. If it return python 3.7.x, it's ok.

## Put rasp-camera.py on the desktop of Raspberry Pi

If you don't know how to transfer files remotely to Raspberry Pi, see here [Use FileZilla to transfer files to Raspberry Pi]

## Run rasp-camera.py on Raspberry Pi

    $ cd Desktop/
    $ python rasp-camera.py

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/run_py.jpg" width="600" alt="add_resourse"/><br/>

then it will run untill you press ctrl + C
    
## Open a Browser on your PC or mobile phone

enter your Raspberry Pi IP address on search bar, like 
    
    192.168.0.1:8000

<img src="https://github.com/YUEQIN18/IoT/blob/master/Project/picture/take.png" width="600" alt="add_resourse"/><br/>

Then we succeeded.

## Reference

(https://www.cnblogs.com/uestc-mm/p/7587783.html)
  


