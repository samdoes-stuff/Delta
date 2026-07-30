# Delta 

![alt](<3D & Plate/Delta v1.png>)

Delta is a 60% wireless low profile mechanical keyboard. Instead of a dedicated pcb for the keyboard, Delta uses a 1.2mm FR4 keyboard plate which works as both Keyboard Plate and PCB. Also, it uses SMD Diode rather than through hole diode. This plate also has coloumn and row outputs so that it can be connected with a seperate micro controller.

As a micro controller, I used my own devboard [PHOTON](https://github.com/samdoes-stuff/Photon), a custom keyboard controller which has dedicated coloumn and row output,

![alt text](<3D & Plate/photon.png>)

I aspire the keyboard to be a cosmic orange color plate inspired by the iphone's color. By just using JLCPCB's multicolor silkscreen, I applied a cosmic orange silkscreen in the both side. Apart from that, the micro controller already features USB HID & Bluetooth (On board antenna).

![alt](<3D & Plate/Delta_2026-Jul-28_10-23-40PM-000_CustomizedView4533982454_png_alpha.png>)

# Hardware 

1.  **Layout**: 60%
2.  **Plate**: 1.2 mm FR4 with integrated switch routing
3.  **Controller**: [PHOTON](https://github.com/samdoes-stuff/Photon), (Custom MCU)
4.  **Connectivity**: Low energy BLT + USB HID
5.  **Switches**: Gateron KS-33 Brown
6.  **Stabilizer**: Gateron Low profile Stabilizer Set 
7.  **Keycaps**: DSA profile MX style Switches

  ## BOM 
     Please refer to BOM.csv


# Schematics & PCB

This board is designed in Easyeda. It is two layer board comes with solderable M3 standoff. This board also features the JLCPCB's multicolor silkscreen. 

[📄 Schematic PDF](./Design%20File/SCH_Schematic1_2026-07-28.pdf)

![front](<Design File/Front Layer.png>)

![back](<Design File/Back Layer.png>)

![pcb1](<Design File/Screenshot 2026-07-28 120603.png>)

![pcb2](<Design File/Screenshot 2026-07-28 120614.png>)


# CAD & Assembly 

Fusion360 is being used for making the backplate and also for the assembly. For the **assembly file** & **backplate**, please refer to **3D & Plate** section of this repo.

![cad1](<3D & Plate/Screenshot 2026-07-28 151730.png>)

![cad1](<3D & Plate/Screenshot 2026-07-28 151740.png>)

![cad1](<3D & Plate/Screenshot 2026-07-28 151751.png>)


# Firmware & Flashing 

**ZMK** is being used in the keyboard. My custom **Photon** MCU comes with pre installed firmware for the keyboard. For the convience, I shared the firmware file in this repo. Please refer to **Firmware** 

If u have different MCU, you may have to build ZMK again for the specific MCU. Here is my [**ZMK_Config**](https://github.com/samdoes-stuff/zmk-config) repo. You can config from there.


# AI Declaration 

AI has been used to do web search and finding relevant information about the components. NO AI has been used in my PCB design. All the routings and design are manual and video logged
