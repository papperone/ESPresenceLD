# ESPresence
ESPHome firmware for ESPresenceLD sensor (ESP32+LD2410x)

# Installation
Read PDF file in repository --> **ESPresence-LD2410-Install.pdf**

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
Link to TINDIE store for purchase:  https://www.tindie.com/products/33322/

Link to HACS for custom card (Maurizio Arci):  https://github.com/madmicio/lovelace-ld-2410-control-card

Link to THINGIVERSE for STL files (Henrik Sozzi):  TBD
