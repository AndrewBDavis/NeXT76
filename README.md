NeXT76 Left-Handed Alps Keyboard
=====================
The primary goal of this project was create as PCB and accompanying layered acrylic case for exclusive support for NeXT non-adb keycaps and Alps Electric SKCM/SKCL switches.

![next_pcb](https://github.com/AndrewBDavis/NeXT/blob/master/next_pcb.jpg)
![next_model](https://github.com/AndrewBDavis/NeXT/blob/master/next_case/next_model.JPG)


Supported Layouts
---------------
This keyboard supports the [NeXT standard non-adb layout](https://tinyurl.com/mrxz3pk3) with a few differences, there no arrow Keys, brightness or volume keys and the numpad is moved to the immediate left of the ESC, TAB, etc... keys.  
Numpad Layouts supported:  
| 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |
|----|----|----|----|--|----|----|----|----|--|----|----|----|----|
| 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |
| 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |
| 1u | 1u | 1u | 2u |  | 2u | 1u | 1u | 1u |  | 1u | 1u | 1u | 1u |
| 2u | 2u | 1u | 2u |  | 2u | 1u | 2u | 2u |  | 1u | 2u | 2u | 1u |  

(Some layouts not shown explicitly)


BOM for Alps76 keyboard                                                  
------------------
| REF:  | VALUE:     | FOOTPRINT:           | COMPONENT            |
|------ | ---------- | -------------------- | -------------------- |  
| C1    | 22p        | C_0805               |                      |
| C2    | 22p        | C_0805               |                      |     
| C3    | 1u         | C_0805               |                      |
| C4    | 4.7u       | C_0805               |                      |
| C5    | 0.1u       | C_0805               |                      |
| C6    | 0.1u       | C_0805               |                      |
| C7    | 0.1u       | C_0805               |                      |
| C8    | 0.1u       | C_0805               |                      |
| J1    | USB_mini_B | USB_miniB_hirose_5S8 | UX60SC-MB-5S8 Hirose |
| R1    | 22         | R_0805               |                      |
| R2    | 22         | R_0805               |                      |
| R3    | 10K        | R_0805               |                      |
| R4    | 10K        | R_0805               |                      |
| R5    | 1K         | R_0805               |                      |
| R6    | 1K         | R_0805               |                      |
| R7    | 1K         | R_0805               |                      |
| SW1   | SW_PUSH    | Custom               | TE 1825966-1         |
| U1    | ATMEGA32U4 | QFP44                | ATMega32u4-AU        | 
| X1    | CRYSTAL    | FA-238               | 16MHz, 12PF          |
| D(78) | DIODE      | SOD-123              | 1N4148               |
| LED(3)| LED        | LED_D3.0mm           | 3mm Round Top LED    |

Revisions
-------------
V0.0: 	Prototype  
V1.0: 	Initial Release  
&emsp;&emsp;&nbsp;&nbsp;Cleaned up trace routing  
&emsp;&emsp;&nbsp;&nbsp;Added full numpad support  

		
