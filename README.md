# Switch-N-Sense
This is a Kicad redesign of switch-n-sense pcb from LibreSolar project

## Design changes:

* Wire to board connector is replaced with cheaper alternative - Keystone 8197 (30A rating)
* MOSFET's footprint now is TDSON-8-1 for 5x6 mm SMD transistors 
* Pinout of connector to the BMS (IDC connector) is compatible with previous version of pcb
* C1,C2,C6 and C7 are changed to 0805(2012) size

## Current target

Current rating can be adjusted depending on chosen MOSFETs and sense resistors, but major limiting factor is connector (30A)

| MOSFET (2x)   | Voltage | Maximum Current | Remark                                       |
|---------------|---------|-----------------|----------------------------------------------|
|NVMFS6H800NT1G | 48V     | 30 A            | connector limited                            |


