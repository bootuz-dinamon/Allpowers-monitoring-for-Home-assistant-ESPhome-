# Monitoring for Home assistant ESPhome  Charging stations Allpowers 

Allpowers charging stations have a built-in Bluetooth module that transmits BLE notifications with two data sets. By controlling them, you can get information about the battery status, input and output power.
This example works on charging stations:
 - Allpowers R600 - https://bit.ly/4omckK7 

And it should also work on the:
- Allpowers S300


Source - https://github.com/madninjaskillz/AllPowersS300ESP32HomeAssistant

And this is the data array that is processed by the program:

>  Notification from 0000fff1-0000-1000-8000-00805f9b34fb, value: (0x) A5-65-B1-00-01-08-01-02-59-00-00-00-23-01-37-37
> 
>  Notification from 0000fff1-0000-1000-8000-00805f9b34fb, value: (0x) A5-65-B1-00-01-06-03-03-01-FF-FF-03-02-76
