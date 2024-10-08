# RM28-TRACTIVE-SYSTEM

This respository currently contains one major project:
* WIP RM28 Project - This project is the most up-to-date version of the 2024-2025 competition car's High Voltage System.

To open and work with these files, specific software packages must be used.
* LTSpice - Circuit simulation software used for preliminary mockups of circuit designs. The .asc files can be opened in other spice programs like ngspice or pspice, but these circuits were originally drafted in LTSpice
* KiCad - PCB design software used for creating schematics for manufacturing.


Acronyms Used:
* ESF - Elecrtrical Systems Form
* GLV - Grounded Low Voltage
* HV - High Voltage
* TSAL - Tractive System Active Light


Typical Circuits:
* Tractive System Active Light (TSAL) - When GLV is on and HV (typically between 12-400V) is less than 60V outside the container, turns an LED green. If HV is greater than 60V, a red LED blinks at low frequency. PS16-051 is the transformer used in this circuit, but has been since discontinued. A similar transformer may need to be selected.
* Accumulator Indicator - Turns on blue LED if voltage outside the container is greater than 60V. Must work in absence of GLV.
* ESF - Shows overall design of racecar electrical system. Includes datasheets, circuit diagrams, electrical architecture, and part numbers.
