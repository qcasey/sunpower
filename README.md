# Sunpower - Home Assistant
Python script for decoding Sunpower inverter packets and recording solar production, power consumption, and temperature in Home Assistant.

Built on the great research of [@ehampshire's](https://github.com/ehampshire) [original repo](https://github.com/ehampshire/sunpower). Detailed walkthrough of the setup [on their website](http://www.2b1f625d-a29c-41a3-81d7-ca1904095e20-19686.remixer.website/).

To use properly, edit the configuration variables in [capture/pycap.py](https://github.com/qcasey/sunpower/blob/master/capture/pycap.py#L11). Written for my single inverter, microinverters will need to have the Home Assistant entity change based on the serial number. 
