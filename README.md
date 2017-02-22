This board is now compleet. Testing will start shortely.

This repository will have all the files for the PCB that fits on a Raspberry Pi witch will have a 7 stage low pass filter for the VHF 2m band. (About 60db down for first harmonic).<br>
![Alt text](7_stage_2m_filter_1.png?raw=true "Block diagram")<br>
It also now include a Mini Circuits low pass filter so you could use this board for two bands.
Operating manual will be available shortly.
This board is to be used with the rpitx utility to alow you to transmit on the 2m VHF band.
This board will have 7 stage lowpass filter.<br>
Here is the filter design details.<br>

![Alt text](7_stage_2m_filter_1.png?raw=true "Filter diagram")<br>
Filter similator Diagram<br>
![Alt text](7_stage_2m_filter_2.png?raw=true "Filter diagram")
The PCB files is Kicad file format.<br>
The circuit diagram.<br>

![Alt text](Raspberry_Pi_dual_filter_Diagram.png?raw=true "Raspberry Pi hat Circuit diagram")
PCB layout diagram during design
![Alt text](Bacar_PCB_2.png?raw=true "PCB diagram")
<br>
Chnaged Connectors transistor and regulator
![Alt text](Bacar_PCB_3.png?raw=true "PCB diagram")
<br>
PCB 3D view
![Alt text](Raspberry_Pi_Tx_2m_dual_filter.png?raw=true "PCB 3D Layout")
Top SMA Connector is linkd to one filter.
Botom SMA connector is connected to 7 stage filter.
<br>
3DB RF Attenuator T (Kicad)
![Alt text](3db_Rf_attenuator.png?raw=true "3db rf Attenuator")
<br>
6dB Rf attenuator T (Kicad)
![Alt text](6db_RF_Attenuator.png?raw=true "6db rf Attenuator")
<br>
9dB Rf attenuator T (Kicad)
![Alt text](9db_RF_Attenuator.png?raw=true "6db rf Attenuator")
<br>
PCB wave guide with Ground plane impedance calculator 50ohm (Kicad)
![Alt text](PCB_wave_guide_with_Ground_plane.png?raw=true "9db rf Attenuator")
<br>
