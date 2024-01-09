![](/images/ESPresenceLD-Logo.jpg)

# ESPresence
ESPHome firmware for ESPresenceLD sensor (ESP32+LD2410x)

# Installation
Read PDF file in repository --> **ESPresence-LD2410-Install.pdf**

# Factory Reset
If you want to bring your device to the initial conditions please follow below steps:
1) download the loader firmware from this repository -- espresenceld.bin
2) connect your device to PC with USB cable and flash the firmware just downloaded using **ESPHome Flasher** tool
3) Now the device is in the initial condition and you can install it following the instructions
   
# Hardware
This firmware is suitable for my ESPresence device based on ESP32-WROOM-32D microcontroller and LD2410C presence sensor.
You can purchase this device using the link in the next section. 
| GPIO  | Assigned Function |
| ------------- | ------------- |
| IO18  | LD2410C TX Pin  |
| IO33  | LD2410C RX Pin  |
| IO13  | Status LED (Green) used by ESPHome  |
| IO23  | Disable Occupancy LED (Red)  |
| IO34  | LDR for analog luminosity reading  |
| IO25  | ICS Bus - SCL Pin  |
| IO36  | ICS Bus - SDA Pin  |

# Useful Link
Link to TINDIE store for purchase
![https://www.tindie.com/products/33322/](https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-smalls.png)

Link to HACS for custom card (Maurizio Arci)
https://github.com/madmicio/lovelace-ld-2410-control-card

Link to THINGIVERSE for STL files (Henrik Sozzi): 
**- TBD -**
