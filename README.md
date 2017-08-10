# Anycubic kossel linear
Marlin firmware variant for Anycubic Kossel Linear

Use arduino 1.6.8.
Cure 15.04 - slicer
Printrun - control printer

Install CP2102 drivers

Firmware settings:
MANUAL_Z_HOME_POS 3xx - setup Z coordinate
TEMP_SENSOR_BED 1 - activated hotbed
PROBE_OFFSET_FROM_EXTRUDER - offset for probe (default 0 0 -24.1)

Cura settings:
MAX width, depth, heigth - 180, 180, 300
Heated bed - yes
Build area shape - circular
Baudrate 250000
Printing temperature: PLA-195
Fialament diameter (default): 1.75
Nozzle size (default)- 0.4
Travel speed: 130
Infiill speed: 40
Minimal layer time: 10

Printrun:
G28 - return to home
G1ZnXnYn - go to position nxnxn

