# Hardware connection and use

---

#### Regardless of receiver and transmitter:

The CUAV XTEND Radio module does not divide the receiving end from the transmitting end (no matter aircraft and ground), and the module has an automatic switching chip built in.

When USB is plugged into the computer, data is automatically switched to the USB port

When USB is not present, data is switched to the 6P GH1.25 port

#### Factory paired:

The factory default is airspeed 115K, interface rate is 57600, peer-to-peer broadcast mode

If you need to modify the configuration, please refer to the software configuration guide. Generally, you only need to modify the VID to achieve the effect of isolation from communication with other modules. For example, if you modify other configurations, familiarize yourself with the documentation and then modify it carefully.

#### Connection with Flight Control:

PixHack: Radio Interface Plugged into Flight Control

Pixhawk: plug into the flight controller's telem1 or telem2 interface

#### Ground Station Use:

In theory, the ground stations of the PIX are compatible. Please select 57600 baud rate when connecting. Note whether the driver is installed correctly and whether the port number is selected.

If you use a mobile OTG connection, the distance may be short because OTG power is not enough

[xtcu debugging and related configuration tutorial]
(http://doc.cuav.net/tutorial/copter/optional-hardware/radio/usb-xbee.html)

