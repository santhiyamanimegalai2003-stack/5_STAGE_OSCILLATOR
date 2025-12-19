# 5_STAGE_OSCILLATOR
## REG NUM :25014334
## NAME :SANTHIYA B
## EXPERIMENT6.b Design a CMOS Five Stage Amplifier and find out the Transient and OP analysis.

## Aim:To Design CMOS Five Stage Amplifier and Perform Transient and OP analysis.

## ToolsUsed:
Virtuoso Schematic Editor is used for the design and analysis.

## Theory:
A five-stage amplifier is a multistage amplifier system where five individual amplifier circuits are connected in cascade (series) to achieve a substantially higher overall gain than a single stage could provide. The primary function is to boost a weak input signal, often by dedicating initial stages to voltage gain and the final stage to high power/current gain. The total gain of the system is the product of the voltage gains of the five individual stages, making the system highly effective for applications like radio receivers or powerful audio systems. Interstage coupling (usually RC, transformer, or direct) ensures the AC signal passes efficiently while isolating the DC bias conditions of each stage.

## Procedure:
•	Click  new -> library->attach to an existing technology library gpdk180(in technology file)
•	new-> cellview ->(nameofthelayout)
## Forschematic:
A.TRANSISTOR DIAGRAM:

![5 STAGE](https://github.com/user-attachments/assets/1b582984-3cd7-45d4-8e63-f20176229a3a)

FIG: 5 SATGE OSCILLATOR DIAGRAM 

B. IN CADENCE 

<img width="1045" height="758" alt="image" src="https://github.com/user-attachments/assets/c6c242d8-83fe-4002-ad3c-093a049a5a0b" />

FIG: 5 SATGE OSCILLATOR SCHEMATIC DIAGRAM 

•	Pick the components NMOS,PMOS,ground,VDC and voltage source.
•	Connect the wire as per the schematic diagram.

Transient Analysis and OP:
a)	In the Analysis section, select transient.
b)	In the stop time type 400n and clic kOK.
c)	In the transient Analysis section,turn on Save transient Operating Point.
d)	Check the enable button and then click Apply. 
e)	ClickOK in the Choosing Analyses Form.


## Execute Outputs:
To be plotted–Select on Schematic in the simulation window.
Follow the prompt at the bottom of the schematic window,Click on
output net Vout,input net Vin of the Inverter.

Execute Simulation:
Netlist and Run in the sIMulation window to start the Simulation.
When simulation finishes,the DC,AC plots automatically will be poppedup along file.

## WAVFORM:
<img width="975" height="565" alt="image" src="https://github.com/user-attachments/assets/bdacaf4c-b326-4cd3-b010-afe5a3b27c52" />

## Results:
Design of CMOS Five Stage Amplifier Transient and OP analysisis performed.
