# Rotorflight-Frsky-Setup
Instructions for Frsky Ethos Initial Radio and Configurator Setup, this is a generic setup using a Nexus FBL, Frsky transmitter with an frsky access receiver

# Radio

Following the manufacturers instructions register and bind your receiver to your newly created model or a clone

Once the bind is successful you will see Telmetry items updating in the Model\Telemetry screen, similar to this

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup1.png)

And the radio will display signal in the top right similar to this:

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup1-1.png)
 

Enter the Model screen and scroll to RF System, select the receiver, in this example we are using a Frsky Archer GR6Plus, click on the receiver type and select options. Under Telemetry port choose FBUS, and exit the screen. FBUS is the prefered method of connection.

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/receiver-f.bus2.jpg)


# Nexus and RF Configurator

In the following example the Frsky receiver is connected to Port (A) of a Nexus controller. With the supplied cables you can connect to either Port A, B or C

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/nexus1.jpg)

Connect the USB-C cable to the Nexus and connect to the PC\Laptop with the Configurator installed. The latest Rotorflight configurator can be found [HERE](https://github.com/rotorflight/rotorflight-firmware/releases)

One connected this screen will be displayed if a new Nexus is attached.

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page1.png)

This is a warning the accelerometer is not calibrated, click close and enter the main configurator page. 

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page2.png)


Select SETUP on the left, hold or keep the nexus flat on the bench and click 'Calibrate Accelerometer', the top status bar will show ' Accelerometer calibration finished'

Select STATUS on the left and the following page will be displayed

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page3.png)

Item 1 is showing board firmware and identification.
Item 2 is showing battery connection info - At this stage the main battery is not connected.
Item 3 is showing the Nexus firmware version and the RF Configurator version.

# Configurator Initial Setup

Select Configuration on the left

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page4.png)

The screen is described as:

Enter your craft name
Enable Accelerometer, Barometer and CMS
Set Port (A) or your assigned receiver port to Serial Rx
## By default the Nexus is setup to be installed horizontal pins facing towards the front, if the pins are facing to the rear enter 180 in the Yaw Degree's box.
Click Save and reboot

Enter the Receiver tab and select the options as per this view.

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page5.png)

Under telemetry enable these options

![image](https://github.com/jimmy6616/Rotorflight-Frsky-Setup/blob/img/setup-page6.png)















