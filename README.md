# Flightime - Quadcopter
[![View PCB on KiCanvas](https://hack.club/pcb-badge)](https://kicanvas.org/?repo=https%3A%2F%2Fgithub.com%2FRishitJain-dev%2FFlightime%2Ftree%2Fmain%2FPCB)
<img width="866" height="550" alt="Screenshot 2026-10-22 000128" src="https://github.com/user-attachments/assets/08b853c2-1928-4594-a8a6-b680967e18e0" />

Flightime is a custom designed drone with a PLA Aero frame, 4 8520 brushed motors, and a PCB flight controller with a OV2640 camera mounted on the XIAO ESP32 S3 SENSE

> Weighs: 132.6g

I designed this as an example project for [Lift Off](liftoff-ysws.vercel.app), where you design a drone, and get the components to build it and if its a great project, then even a drone controller!

### Features
- OV2640 FPV Camera
- Bluetooth and WiFi capabilities
- < 150g
- Power Switch
- 8520 Brushed motors
- $200 total price (including tools!)

## PCB

The PCB was made in KiCAD! It has:
- GY-521 gyroscope
- XIAO ESP32 S3 sense
- Various resistors
- Various SMD & TH capacitors
- SMD MOFSETs

<img width="1278" height="838" alt="Screenshot 2026-10-21 213401" src="https://github.com/user-attachments/assets/f34e1ffd-8f9b-4f30-b7cb-3c990d3a8bc8" />
<img width="1269" height="795" alt="Screenshot 2026-10-21 213337" src="https://github.com/user-attachments/assets/de72935e-6bf2-40f0-8380-3805ae98684b" />

## CAD

The CAD was designed exclusively in Onshape. The 2 parts fit together with 4 M3 screws and nuts, it doesn't require any heatset inserts, you screw directly into the PLA.

There are cut-outs in each piece so that wires can fit through. This is a pusher drone, the motors are press fit and the propellers face towards the ground.

<img width="1066" height="674" alt="Screenshot 2026-10-22 000128" src="https://github.com/user-attachments/assets/a927618d-fd26-4a45-8d06-20a6b44b2faf" />

## Assembly  

Use the schematic diagram on Kicanvas to solder one side of the wires to the board before assembly. Then place the board, mount it using the screws and nuts and take the wires to the motors and solder the other side there. 

## Firmware

We move by slowing down certain motors and speeding up others, this causes it to lean and tilt towards the direction its meant to be going, and begins to accelerate. 
In the final firmware, it will be controlled through bluetooth on a computer or phone.

<img width="838" height="409" alt="image" src="https://github.com/user-attachments/assets/8c2c6632-1c58-45e9-a36e-225129330a90" />






