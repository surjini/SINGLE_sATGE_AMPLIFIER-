# SINGLE_STAGE_AMPLIFIER-
## REG NUM :
## NAME :
## EXPERIMENT 4: Design a CMOS Single Stage Amplifier and findout the DC and OP analysis.

## Aim:
To Design CMOS Stage Amplifier and findout the DC and OP analysis.

## ToolsUsed:
Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
A single-stage amplifier is the most fundamental electronic circuit used to increase the magnitude (gain) of a weak electrical signal. It consists of a single active component (like a transistor) and its associated passive components (resistors and capacitors). The main function of the circuit is to properly bias the transistor to operate in its active region for linear amplification, while capacitors isolate the DC biasing from the AC signal. The overall design results in the output signal being a larger replica of the input, typically achieved using configurations like the Common Emitter (CE).

## Procedure:
•	Click  new -> library->attach to an existing technology library gpdk180(in technology file)
•	new->cellview ->(nameofthelayout)
## Forschematic:
A.)TRANSISTOR DIAGRAM 

<img width="228" height="243" alt="SINGLE SATGE AMPLIFIER DIAG" src="https://github.com/user-attachments/assets/6193943d-9c13-4036-9c60-7ff57202f2a6" />


Fig:CMOS Single Stage Amplifier Transistor  Schematic

B.)IN CADENCE:
•	PickthecomponentsNMOS,PMOS,ground,VDDandvoltagesource.
•	Connectthewireaspertheschematic diagram.


<img width="1067" height="602" alt="image" src="https://github.com/user-attachments/assets/59c8132b-0aa7-47bb-9a61-480007dbc02b" />

Fig:CMOS Single Stage Amplifier Schematic

## DCAnalysisandOP:
1.	In the Analysis section,select dc.
2.	In the DC Analysis section,turn on Save DC Operating Point.
3.	Turn on the Component Parameter.
4.	Double click the Select Component,Which takes you to the schematic window.
5.	Select input signal Vpulse source in the test schematic window.
6.	Select “DCVoltage” in the Select Component Parameter for and click OK.
7.	Intheanalysis formtypestartandstopvoltagesas0to1.8 respectively.
8.	ChecktheenablebuttonandthenclickApply.
9.	Click OK in the Choosing Analyses Form.

## DCOperating Point:
This analysis simply determines the DC operating point of the circuit based on the parameters present on the schematic assuming all capacitor suspened and all inductors shorted. It is the default mode and is automatically performed therefore any other analysis in order to determine the initial state of the circuit.

## Execute Outputs:
To be plotted–Selection Schematic in the simulation window. Follow the prompt at the bottom of the schematic window, Click on output net Vout, input net Vin of the Inverter.

ExecuteSimulation:
Net list and Run in the simulation window to start the Simulation.
When simulation finishes,the DC plots automatically will be poppedup along file.

## Waveform:


## RESULTS:
Design of CMOS Single Stage Amplifier  DC and OP analyses is performed.







