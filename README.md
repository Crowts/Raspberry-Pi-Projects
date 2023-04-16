# Raspberry-Pi-Projects: 
<br>

Raspberry Pi as a Casting Tool <br>

**Hardware:** <br>
Raspberry Pi <br>
SD card <br>
HDMI cable <br>
monitor <br>
smartphone <br>


**Software:** <br>
Raspicast (Andriod) or AirPlay (iOS) <br>
OMXIV <br>
libjpeg8-dev <br>
libpng12-dev <br>

First, you'll to connect the raspberry pi to your monitor using the HDMI cable. Ensure you have the SD card inserted. Once done, you'll need an internet connection, so connect to your WiFi. <br>

You must find your Pi's IP address. Open a terminal and type
```python
$ ifconfig
```

Note: It should look something like this 192.168.xx.xx. 

<br>
<br>

**Install Raspicast** <br>
From the PlayStore, download the Raspicast app and configure the port (should be 22) and add the IP address.
