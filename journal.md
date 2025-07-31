|                   |                                                       |
|------------------|-------------------------------------------------------------------------|
| **Project Name**  | RuchithaBoard                                                           |
| **Author**        |Ruchitha                                                                |
| **Description**   | A self-designed 60% custom mechanical keyboard featuring SMD diodes, a Pro Micro clone, Gateron Blue switches, and an OLED display. The PCB and layout were designed in EasyEDA Pro, while the case was modeled in Fusion 360. The board is waiting for approval from Hackclub Highway and has not yet been printed or fabricated. |
| **Case**          | Self-designed and modeled in Fusion 360 (not yet 3D printed)            |
| **Total Cost**    | $90.83 / ₹8,117 (approximate)                                           |
| **Total Time Spent** | 24 hours                                                            |



## July 27 — Schematic Day (5 hours)
The idea came out of nowhere, honestly. I just wanted to make something clean, simple and personal. I opened up EasyEDA Pro, created a new project, and started placing the switches manually for a 60 percent layout. I didn’t use templates or copied matrix blocks. I wanted to build every key, every column by hand. It took time but felt so much more satisfying.I spent a good amount of time laying out the switch matrix with five rows and fourteen columns. I matched each column to GPIO pins on the Pro Micro clone, and reserved D2 and D3 for the OLED lines. Every diode was added as an SMD footprint and aligned neatly. I got a bit too obsessed with the symmetry, but I didn’t care  this was my board.By the time I was done with the schematic, the net labels, and double-checking everything, the whole circuit looked confident and clean. I exported the netlist, saved everything with a weirdly proud smile, and closed it for the night.

<img width="644" height="594" alt="Screenshot 2025-07-31 152957" src="https://github.com/user-attachments/assets/36aa4b33-6ce7-4f6c-af90-b92e299168dd" />

## July 28 — Routing and Layout (4 hours)
This session was all about copper and patience. I sat down with my tea and started routing the PCB from scratch. No autorouting, no hacks. Just me, the grid, and a bunch of yellow airwires waiting to be tamed.
I started with columns, drawing them as straight as possible without collisions. Rows were tougher because they had to snake around the columns and components. I didn’t mind. I placed vias like little checkpoints and kept the ground pour clean. Every DRC warning got squashed as I progressed, and by the end of it, the board actually looked beautiful.I made sure to leave some room for the OLED header on the top and added silkscreen labels for the rows and columns  partly for debug, partly for vibes. I exported the Gerbers and stared at them zoomed out, appreciating the little grid I’d just built.

<img width="1018" height="392" alt="Screenshot 2025-07-31 153837" src="https://github.com/user-attachments/assets/aab76210-bc86-4e12-a587-d318624ed696" />


## July 29 — Fusion Modeling Day (4 hours)
After finishing the electrical side, it was time to give the board a home. I opened Fusion 360, imported the PCB outline as DXF, and started building a bottom shell around it. The plan was to make a minimalist case that just holds the board securely with basic screw mounts and enough room for the USB port.I added side walls about 5 mm thick and some internal bosses for screws. The Pro Micro’s height was estimated based on an old model I had, so I gave it a few millimetres of breathing space. The OLED cutout was modeled carefully, matching the header placement and with enough clearance around the glass.
The design didn’t follow any tray mount style. I was just figuring it out as I went. Everything was shaped from scratch  even the USB cutout was eyeballed using a caliper from a cable I had lying around. By the time I finished the first full model, it looked like something I’d want to hold. I didn’t print it yet, though. I’m still refining and waiting for the PCB approval before starting the actual print.

<img width="1031" height="582" alt="image" src="https://github.com/user-attachments/assets/25cd53f0-ef64-4190-8413-25abd2321aca" />
<img width="958" height="605" alt="image" src="https://github.com/user-attachments/assets/b4a4af42-0a7d-438a-a760-cd71f9faf5cc" />


July 30 — Assembly Planning and Part Checks (6 hours)
This day was a mix of inventory check and mentally preparing for how the soldering would go once the PCB arrives. I laid out all my components on the desk  switches, SMD diodes, OLED display, header pins, Pro Micro. I don’t have hot-swap sockets for this board, and I didn’t want to use any either. I wanted this to be a proper soldered board  permanent and intentional.I did a dry run with switch alignment using an old PCB just to see how the footprint spacing felt. Looked good. I also used a multimeter to pre-test the OLED header connections on my Pro Micro clone. It’s a small thing but gives peace of mind.
I didn’t do any actual building or printing today, just prep. I saved the QMK JSON layout and decided I’d build the firmware tomorrow, even if the PCB isn’t ordered yet.

<img width="1165" height="625" alt="Screenshot 2025-07-31 152735" src="https://github.com/user-attachments/assets/a6a8e227-1ba6-44ef-a6ea-596cd0a9c3bb" />
<img width="1132" height="486" alt="Screenshot 2025-07-31 152401" src="https://github.com/user-attachments/assets/98723e37-a897-4c9b-af6f-ce374be424c1" />

## July 31 — Firmware with QMK and Final Github  (5 hours)
I spent the final build session working on QMK. Even without the physical PCB, I didn’t want to waste time. I used QMK Configurator to set up the layout exactly as per my schematic. The base layer had all the standard keys, but I added a layer for function keys and media control  just enough to make it feel modern.I selected the right pin mappings for rows and columns based on my schematic. It was a lot of back and forth between QMK and EasyEDA to make sure everything matched. After that, I compiled the firmware and downloaded the .hex file. All I’m doing now is waiting for Hackclub Highway to approve the PCB so I can order it and finally make this board real.

<img width="1132" height="486" alt="Screenshot 2025-07-31 152401" src="https://github.com/user-attachments/assets/7a67a0a5-020a-4a9d-82ab-a816aee63601" />
<img width="1859" height="689" alt="Screenshot 2025-07-31 154333" src="https://github.com/user-attachments/assets/2c828e17-f931-44a1-a905-b00f5f05ea9f" />


uploaded all the files, schematics , step files and firmware :)
Hope it gets approved

