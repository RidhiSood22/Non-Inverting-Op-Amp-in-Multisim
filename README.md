# Non-Inverting-Op-Amp-in-Multisim

Overview

This project demonstrates the design and simulation of a Non-Inverting Amplifier using an operational amplifier in NI Multisim.
The amplifier increases the amplitude of the input signal without changing its phase.

# Aim

To design and simulate a non-inverting amplifier in Multisim and analyze its gain and output waveform.

 # Theory

A non-inverting amplifier is an op-amp configuration where the input signal is applied to the non-inverting terminal (+).

The voltage gain is given by:

Av = 1 + (R1/Rf)​

Key Characteristics:
Output is in phase (0° shift) with input
High input impedance
Stable gain
Widely used in buffering and amplification

# Components Used (Multisim)
Operational Amplifier (e.g., 741 Op-Amp)
Resistors:
R1 (to ground)
Rf (feedback resistor)
AC Voltage Source (input signal)
Ground
Oscilloscope (Virtual Instrument in Multisim)
Power Supply (±12V or ±15V)

# Circuit Diagram 
<img width="550" height="300" alt="image" src="https://github.com/user-attachments/assets/4b061482-429c-4376-b319-2f1fbfd9c307" />



<img width="550" height="300" alt="image" src="https://github.com/user-attachments/assets/4c24f321-c322-4932-b7d3-8988f00a21f7" />


        
# Procedure (Multisim)
Open NI Multisim and create a new design.
Place the Op-Amp (741) from the component library.
Add resistors R1 and Rf.

Connect:
Input signal to non-inverting terminal (+)
Feedback network between output and inverting terminal (-)
R1 from inverting terminal to ground
Add power supply to the op-amp.
Connect an oscilloscope to observe input and output signals.
Run the simulation.

# Expected Results
Output signal is amplified but not inverted

Gain follows:

Av  = 1+ (R1/Rf)
	​
Output waveform has the same phase as input

# Example Values
Parameter	Value
R1 = 1 kΩ
Rf = 9 kΩ
Gain = 10

# Precautions
Ensure correct wiring of feedback network

Verify power supply connections

Avoid very high gain to prevent saturation

Check grounding in Multisim

# Applications
Voltage follower (buffer)
   
Audio amplifiers

Signal conditioning

Instrumentation circuits


# Conclusion

The non-inverting amplifier provides stable amplification with no phase inversion and is ideal for applications requiring high input impedance and signal integrity. Simulation in NI Multisim helps in easy analysis and verification of circuit behavior.
