# SC_Platform_Files
json configuration files for the SC Platform

The files in this repository comprise one or more JSON configuration files that match the physical cnfiguration of the 
Smart Citizen Station Version 3 subject of other repos here.

This file provides linkage for the following sensors:

- Urban Board Temperature
- Urban Board Relative Humidity
- Urban Board Light
- Urban Board Noise
- Urban Board VOC gases (2 measures eCO2 && tVOC)

- Aux Bus:
- PM Dust Sensors x 2 ( x 3 measures 1.0, 2.5 && 10.0)
- PM Board Dallas Ext Temp Probe
- SCD41 CO2
- ADC Board Spec Sensors: (All Spec Sensors devices)
- - CO,
- - NO2
- - SO2,
- - H2S
- - O3

- GPS (Lat, Long, Altitude)

- ENS160 VOC conc.
- ENS160 equivalent CO2 conc.
- ENS160 AQI (VOC)


SPECIFICALLY the following sensors are enabled and transmit readings to the platform:

Temperature: 
Humidity: 
PM board Dallas Temperature: 
ENS160 VOC Equiv CO2: 
ENS160 Total VOC: 
ENS160 VOC Air Quality Index:
Battery:  %
Light: 
Barometric pressure: 
VOC Gas CCS811:

eCO2 Gas CCS811: 
GPS Latitude: 
GPS Longitude:
GPS Altitude: 
ADS1x15 ADC 0x48 Ch0
ADS1x15 ADC 0x48 Ch1:
ADS1x15 ADC 0x48 Ch2: 
ADS1x15 ADC 0x48 Ch3: 
ADS1x15 ADC 0x49 Ch0:
ADS1x15 ADC 0x49 Ch1: 

ADS1x15 ADC 0x4A Ch0: 
ADS1x15 ADC 0x4A Ch1: 
ADS1x15 ADC 0x4A Ch2: 
ADS1x15 ADC 0x4A Ch3: 
SCD4x CO2: 
Wind Direction: 
Wind Speed: 
Rain Accumulation: 
Ext PM_A 1.0: 
Ext PM_A 2.5: 

Ext PM_A 10.0: 
Ext PM_B 1.0: 
Ext PM_B 2.5: 
Ext PM_B 10.0:
Noise:

=================
Total 35 Metrics.

In Addition: A pdf document file contains information needed to prepare computation data for the translation of Spc Sensors data into Gas Concentrations
This information links ADC Board Ports to Physical Gas Sensor connections.


