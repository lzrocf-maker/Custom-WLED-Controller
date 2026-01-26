# Custom WLED Controller (ESP32-C3)

This is a custom board with an esp32 c3 as a brain for WLED projects or installations. Here is a photo of how the WLED Controller is suposed to look like when assembled:

<img width="1178" height="790" alt="image" src="https://github.com/user-attachments/assets/a70fe9b6-8e75-4bf9-a242-85b20000dda6" />

## Project Overview
I have built this board to have more flexibility when making custom lighting projects, although it can also be used to control servos or whatever components require a data pin and voltaje.

## Hardware Specifications
- **Microcontroller:** ESP32-C3-Mini
- **Connectors:** 6x JST-Connectors, 1x Barrel-Jack 2.5mm, 1x Terminal-Block.
- **DC-DC Converter:** 1x 560Mini (If you can't find it, in the BOM there's a link to the amazon product).
- **Mounting:** 3x M3 screws, and two 3d printed halves.

## Board Screenshots

<img width="944" height="804" alt="image" src="https://github.com/user-attachments/assets/75b2113f-68c0-4dad-a9f7-409efebbd70f" />
<img width="489" height="584" alt="image" src="https://github.com/user-attachments/assets/8c754fdd-5620-44a0-a5e6-729ff7bc6355" />
<img width="724" height="855" alt="image" src="https://github.com/user-attachments/assets/95f46eda-984f-45d0-ab96-841e695e0476" />

## 3D Enclosure & Assembly
I designed the case so that you only have to print 2 parts, the two halves come together with 3 M3 screws that thread to the plastic with the PCB in the middle:

- **Top Plate:** I designed the top part so that you have the cut-outs for the barrel jack, terminal block and usb-c from the esp32-c3, as well as having the cut-outs for the 6 JST connectors.
  <img width="1082" height="795" alt="image" src="https://github.com/user-attachments/assets/94c1f7d9-5fdd-4bb9-b437-1591df1f6ff6" />
- **Bottom Base:** The bottom part features a recesed part so that the pins of the components do not crash onto the case. It also has 3 countersunc holes for the 3 M3 screws.
  <img width="1079" height="769" alt="image" src="https://github.com/user-attachments/assets/63c504bc-d339-492a-a671-ebdcf46dcc37" />
<img width="1102" height="631" alt="image" src="https://github.com/user-attachments/assets/bfad4c78-84fc-42f7-b26f-cbaaa9782aa2" />

## Firmware
This board uses WLED as the primary software, however, you can put any firmware you want that works with the configuration.

## Repository Contents
- The files ended on .kicad_sch/pro/pcb are the PCB files.
- The Gerbers.zip contains the files for PCB manufacturing.
- WLED LED Controller.step contains the 3d model of the macropad.
- The BOM file contains all the list of materials needed for manufacturing this project.
