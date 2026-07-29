# Delta 

![alt](<3D & Plate/Delta v1.png>)

Delta is a 60% low-profile mechanical keyboard built around a custom designed 1.2 mm FR4 plate that serves as both the switch plate and the switch interconnect PCB. Instead of using a traditional keyboard PCB, the FR4 plate integrates the electrical routing for the switches and SMD diodes while also exposing solder pads for each row and column.

At the heart of the keyboard is [PHOTON](https://github.com/samdoes-stuff/Photon), a custom microcontroller board that outputs the keyboard's row and column matrix. The integrated plate connects directly to PHOTON through wire connections.

![alt text](<3D & Plate/photon.png>)

The keyboard features JLCPCB's Colorful Silkscreen process with a Cosmic Orange finish on both sides, inspired by Apple's iPhone color palette. Combined with the custom backplate, battery mount, and USB extension board, Delta is a fully featured wireless and USB HID mechanical keyboard.

![alt](<3D & Plate/Delta_2026-Jul-28_10-23-40PM-000_CustomizedView4533982454_png_alpha.png>)

# Hardware 

  Layout: 60%
  Plate: 1.2 mm FR4 with integrated switch routing
  Controller: [PHOTON](https://github.com/samdoes-stuff/Photon),(Custom MCU)
  Connectivity: Low energy BLT + USB HID
  Switches: Gateron KS-33 Brown
  Stabilizer: Gateron Low profile Stabilizer Set 
  Keycaps: DSA profile MX style Switches

  ## BOM 
     Please refer to BOM.csv


# Schematics & PCB

This board is designed in Easyeda. It is two layer board comes with solderable M3 standoff. This board also features the JLCPCB's multicolor silkscreen. 

[View Documentation](Design File/SCH_Schematic1_2026-07-28.pdf)

# AI Declaration 

AI has been used to do web search and finding relevant information about the components. NO AI has been used in my PCB design. All the routings and design are manual and video logged