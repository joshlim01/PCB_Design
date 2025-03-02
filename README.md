# PCB-Design

![alt text](https://github.com/joshlim01/PCB_Design/blob/main/pictures/pcb.png)

### Files:
- PCB Course Certificate : A certificate showing completion of 30 hour PCB design course
- overview.png : A visual overview of the project and results
- pcbDesign.kicad_pcb : PCB layout file in KiCAD
- signalGeneratorGerber.zip : Gerber files

### Description:

A signal generator PCB design project performed as part of a 30 hour course through the UBC PHAS Elab, Fall 2022.  A 15V DC signal is passed through a voltage regulator to produce 5V DC.  The 5V is passed through a 5V -> -5V converter to power the rails of an op-amp that can control output signal amplitude.  5V powers a 100kHz Timer/Oscillator that produces a squarewave signal that can be tuned in combination with the potentiometers and the op-amp.  Tuned signal can be read from a through-hole test port.

![alt text](https://github.com/joshlim01/PCB_Design/blob/main/pictures/soldered_board.png)

Project phases included:

#### Design
- Creating a schematic in EDA software (KiCad), including additions to the parts library.
- Creating custom component footprints to match manufacturer specifications.
- Review of good design priciples for PCB circuit layout.
- Manual layout of circuit onto a two-layer PCB, design rules specifications, variable width traces.
- Custom silk screen layering, sizing, and drill holes for ease of assembly.
- Gerber file production and PCB ordering.


#### Assembly
- Manual soldering of surface mount components with a Soldering Iron Kit.
- Testing and validation with digital oscilloscope and multimeter.

![alt text](https://github.com/joshlim01/PCB_Design/blob/main/pictures/kicad1.png)
![alt text](https://github.com/joshlim01/PCB_Design/blob/main/pictures/kicad2.png)