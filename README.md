# PRIME Lab 2017b Control

LabVIEW code for controlling both slow-switching regime.  cRIO code has been worked on (inlcuding shared variables) but work had just begun on control room HMI when 2017a project scope increased.  Much of the 2017a code for the HMI should be imported and then work restarted.

## cRIO code

All cRIO code has been updated but lessons from 2017a project need to be incorporated.

### SCA-cRIO
Status: currently running 2017a

Lacks legacy monitor (needed for iPad) -- probably best to import 2017a code

### InjA-cRIO
Status: currently running 2010; needs "Miller-ization" and new modules (9205, 9426, 9485, and 9870)

### InjA-Image-cRIO
Status: currently running 2010; no new modules required but updated wiring for HV enables and GV control

### LowEnd-cRIO
Status: currently running 2010; one new module (9485) and updated wiring for HV enables and GV control

### HighEnd-cRIO
Status: currently running 2010; needs "Miller-ization" along with new modules (9205 and 9485) and updated wiring for HV enables and GV control

### Transmission-cRIO
Status: currently running 2017a; will require two new 9485s, one new 9426 module and updated wiring for HV enables and GV control

### R30_1-cRIO
Status: currently running 2017a; will require one new 9485 and updated wiring for HV enables and GV control

### R45_1-cRIO
Status: currently running 2017a; no new modules but extra wiring needed for HV enables and GV control

### R45_2-cRIO
Status: currently running 2017a; will require 1 new cRIO module (9485) and updated wiring for HV enables and GV control, R45-2 will also need upgraded power supply to handle gate valves.

## Top Level (Main) VIs
VIs opened during startup -- probably best to import 2017a code

## Beamline Section VIs
HMI to change beam element control values (hosted on cRIOs)-- probably best to import 2017a code and update shared variable libraries hosted on control computer.

## Tools
Tools available from Main Control VIs and have been updated for new shared variable naming convention.  Molecular beam scaling included along with Flat-Topping.

