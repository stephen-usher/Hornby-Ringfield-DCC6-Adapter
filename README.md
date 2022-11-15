# Hornby-Ringfield-DCC6-Adapter
 
 This board is designed to interface a 6 pin DCC decoder with the Hornby ringfield motor found in most models from the mid-1970s until the late 1980s. With the appropriate wires and connectors it can be used as a substitute to the original wiring without the need to solder to any of the original parts of the model.
 
 In addition to the PCB you will need:
 >2x SOD-323 format diodes with at least 100mA throughput (for directional lights)
 >2x 2010 SMD 10 ohm resistors
 >2x 6 way 1.27mm pitch through-hole socket
 >Optional 0603 1uF SMD ceramic capacitor
 >Wires with connectors. The ones to connect to the motor block and unpowered bogie on diesels can be obtained from Peter's Spares. The 2.78mm spade connectors are more difficult to source.
 
 Although this was designed to be used with Hornby locos it will work with others, such as Lima. I've recently used this board to upgrade a Lima 08 shunter, just soldering wires, bridging the resistor pads (as the Lima motor has a higher resistance) and swapping the motor wires as the Lima motor runs in the opposite direction.
 
 The reason that the board has two 10 ohm resistors in parallel is that the Hornby ringfield motor has a resistance of 13 ohms. With the DCC decoder outputting 16V (pulsed) there is a possibility of the motor, if stalled, drawing more than the 1 amp which most 6 pin DCC decoders can handle. The parallel capacitors add an extra 5 ohms (spread between two resistors so as to reduce the current in any one resistor), taking the total to 18 ohms, with a maximum current at 16V less than one amp.
 
 The optional 1uF capacitor helps dampen any voltage spikes from the motor.

 The DCC Decoder I use is the Bachmann E-Z Command 90 degree 6 Pin DCC Decoder (Ananlogue Compatible), 36-556RA. I've found that for Hornby motors CV10 should be given the value 35 and CV212 (back-EMF cut-off) set to 35.
  
 Note: I've not yet tested the lighting but the circuit conforms to the specification given in the DCC Wiki.
