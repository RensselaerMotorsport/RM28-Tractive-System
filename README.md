# RM28-TRACTIVE-SYSTEM

This respository currently contains several projects for Rensselaer Motorsport's RM28 car, along with some documentation, and spreadsheets for BOMs and calcs
* WIP RM28 Project - This project is the most up-to-date version of the 2024-2025 competition car's High Voltage System.


To open and work with these files, specific software packages must be used.
* LTSpice - Circuit simulation software used for preliminary mockups of circuit designs. The .asc files can be opened in other spice programs like ngspice or pspice, but these circuits were originally drafted in LTSpice
* KiCad - PCB design software used for creating schematics for manufacturing.


Typical Circuits:
* Brake System Plausability Device (BSPD) - The custom circuit for RM28's safety circuit, designed to connect to our shutdown circuit. This is a fully analog safety circuit that activate the shutdown circuit when unsafe conditions (competition rules) are met.
    * The sensor values used for this circuit include the current sensor through the motor, and the voltage sensor from the accelerator pedal
    * See BSPD Current Sensor Trip Calculator.xlsx for calculations to determine the threshold voltage to activate this section of the circuit
* Ready to Move Light (RTML)
   * Blinking red LED if voltage outside accumulator is >60V, and if GLV on 
   * Static green LED if voltage outside accumulator is <60V, and if GLV on
* Voltage Indicator - Turns on  LED indicator if voltage outside the accumulator container is greater than 60V. Must work in absence of GLV.
* ESF - Shows overall design of racecar electrical system. Includes datasheets, circuit diagrams, electrical architecture, and part numbers.
