# Custom DevBoard

## What This Is

This is my **custom development board**. I made it to experiment with electronics, write code, and connect sensors and other parts easily. Everything important is on one board so I don’t need lots of extra modules.

---

## Board Render
<img width="734" height="709" alt="image" src="https://github.com/user-attachments/assets/e55386ba-c43e-436c-9eff-c3768953af2d" />



## PCB Layout
<img width="556" height="597" alt="image" src="https://github.com/user-attachments/assets/0c182536-3363-478f-b1ca-4d2e0facc381" />


## Schematic
<img width="933" height="525" alt="image" src="https://github.com/user-attachments/assets/d20021de-dbf3-4736-a7d8-994510f81520" />


## Bill of Materials (BOM)

| Reference | Part Name      | Description                           |
| --------- | -------------- | ------------------------------------- |
| U1        | RP2040         | Main microcontroller                  |
| U2        | MCP1700        | 3.3V voltage regulator                |
| U3        | W25Q16         | External flash memory                 |
| Y1        | 12 MHz Crystal | Clock source for RP2040               |
| J1        | USB Connector  | Power and programming                 |
| R*        | Resistors      | Pull-ups, pull-downs, and general use |
| C*        | Capacitors     | Power filtering and stability         |
| SW*       | Buttons        | Boot and reset buttons                |

## Power

* Powered through **USB**
* Runs at **3.3V logic level**

Always make sure power is connected correctly before plugging it in.


## How I Use It

1. Plug the board into a computer using USB.
2. Upload code to the RP2040.
3. Connect sensors, motors, or other devices to the pins.
4. Test and improve my project.


## What This Board Is For

* Learning embedded systems
* Testing RP2040 projects
* Robotics and electronics experiments
* Custom hardware development

## Author

Designed by **Mithilessh Bhasker**
