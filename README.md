## RuchithaBoard


RuchithaBoard is a fully custom 60% mechanical keyboard designed from scratch using EasyEDA Pro for the PCB and Fusion 360 for the case. Built for both functionality and flair, it combines a clean layout, hot-swap support, OLED display integration, and full compatibility with QMK firmware all packed into a compact, 3D-printable design.

<img width="1132" height="486" alt="Screenshot 2025-07-31 152401" src="https://github.com/user-attachments/assets/4e664880-eb9d-4c8d-8cac-15a992dd702c" />


The PCB layout was crafted with a hand-routed matrix and carefully labeled traces. It uses a Pro Micro clone as the microcontroller, with diode protection and breakout headers for I2C devices like the OLED screen. The silkscreen includes a custom shoutout and a subtle Arctic Monkeys guitar motif, etched right into the copper pour for a fun personal touch.

<img width="1038" height="344" alt="Screenshot 2025-07-31 152948" src="https://github.com/user-attachments/assets/a774b3a2-9b00-43c5-925c-7eb2edb7833e" />
<img width="644" height="594" alt="Screenshot 2025-07-31 152957" src="https://github.com/user-attachments/assets/e6cf2656-2435-44c7-86a6-51cb0bbd4742" />
<img width="1018" height="392" alt="image" src="https://github.com/user-attachments/assets/f9f05d3c-f14f-465b-a605-47dd47c1126f" />
<img width="937" height="284" alt="image" src="https://github.com/user-attachments/assets/43151bea-f455-4522-97f1-788783c689d8" />
<img width="919" height="501" alt="image" src="https://github.com/user-attachments/assets/78a7c7fe-d75d-43cb-898a-f396cf022fc0" />


The case was modeled entirely in Fusion 360 as a snug two-piece shell. It includes cutouts for the USB port and OLED, and fits together without screws. The design was iterated with both black and white themes in mind, allowing flexibility in print material and keycap choices.
<img width="960" height="494" alt="Screenshot 2025-07-31 153813" src="https://github.com/user-attachments/assets/487b8344-8ea7-4873-a7a1-6e7cd3205653" />

<img width="1146" height="677" alt="Screenshot 2025-07-31 152721" src="https://github.com/user-attachments/assets/c50e37a2-f266-4352-bb20-1123aa1f55bc" />
<img width="1145" height="604" alt="Screenshot 2025-07-30 223226" src="https://github.com/user-attachments/assets/9a0ff9d6-d143-4cdb-a824-fb9607d73e58" />


The keymap was built using the QMK Configurator and exported for future flashing. It features a main typing layer and a second layer with arrows, volume control, and a RESET shortcut. The firmware hasn't been flashed yet since the board isn't assembled, but everything is ready once the build is complete.

This is my first fully designed mechanical keyboard from schematic to switch placement, every bit was customized. RuchithaBoard isn’t just a board; it’s a personal tech/art project that reflects the way I learn, tinker, and design stuff I want to use.

## BOM

| Component                 | Description                          | Qty | Unit Price (USD) | Unit Price (INR) | Store               |
| ------------------------- | ------------------------------------ | --- |---------------- | ---------------- | ------------------- | 
| **PCB Prototype (Black)** | 1.6mm, HASL with lead finish         | 5   | $13.70          | ₹1140            | JLCPCB              | 
| **Shipping (JLCPCB)**     | International to India               | 1   | $21.13          | ₹1757            | JLCPCB              | 
| **Pro Micro (Clone)**     | Micro USB controller board           | 1   | $7.00           | ₹580             | Amazon.in           | 
| **Gateron Blue Switches** | Clicky tactile mechanical switches   | 70  | $18.00          | ₹1500            | CosmicByte.in       | 
| **SMD Diodes (1N4148WS)** | 0805 package                         | 70  | $1.50           | ₹130             | ShaarviElectronics  | 
| **OLED Display (0.91")**  | SSD1306, I2C                         | 1   | $3.50           | ₹300             | Amazon.in           | 
| **Keycaps (PBT Blank)**   | For 65% layout                       | 1   | $20.00          | ₹1700            | NeoMacro.in         | 
| **Soldering + Misc**      | Wires, flux, solder                  | —   | $6.00           | ₹510             | —                   | 
| **Case**                  | 3D Printed (Self-designed in Fusion) | 1   | —                | —                | —                   | 


## Total Estimated Cost: $90.83 / ₹8,117



<img width="1859" height="689" alt="Screenshot 2025-07-31 154333" src="https://github.com/user-attachments/assets/9ca23f8a-0478-4552-97b7-c96a35e65b0c" />




