# Inverting-Operational-Amplifier-in-Multisim
This project demonstrates the design and analysis of an inverting amplifier using an operational amplifier (Op-Amp). The circuit produces an output voltage that is 180° out of phase with the input signal and scaled by a specific gain.

# Objective

To design and verify an inverting op-amp circuit and study its voltage gain, phase inversion, and behavior with different resistor values.

# Theory

An inverting amplifier uses an op-amp with:

Input applied to the inverting terminal (-)
Non-inverting terminal (+) connected to ground
A feedback resistor R
f
	​

 from output to input

The voltage gain is:

A
v
	​

=−
R
in
	​

R
f
	​

	​


Where:

A
v
	​

 = Voltage gain
R
f
	​

 = Feedback resistor
R
in
	​

 = Input resistor

 The negative sign indicates phase inversion (180° shift).

# Components Required
Operational Amplifier (e.g., LM741 Op-Amp IC)
Resistors (R
in
	​

, R
f
	​

)
DC power supply (±V)
Function generator (input signal)
Oscilloscope (to observe output)
Breadboard / LabVIEW simulation setup
# Circuit Diagram (Conceptual)

<img width="678" height="392" alt="image" src="https://github.com/user-attachments/assets/1ad62644-ede1-4536-9a32-3d9ecfda79c1" />
--------------------------------------------------------------------
<img width="805" height="460" alt="image" src="https://github.com/user-attachments/assets/e2c9cd8c-4ae7-4d93-94a1-2f8994da4ebe" />



# Working Principle
Input signal is applied through R
in
	​

 to the inverting terminal.
The non-inverting terminal is grounded.
Due to virtual ground, the inverting terminal remains at ~0V.
Current flows through R
in
	​

 and R
f
	​

.
Output voltage is generated across R
f
	​

, inverted and amplified.
# Procedure
Set up the op-amp circuit on a breadboard or LabVIEW.
Connect:
Input signal via R
in
	​

Feedback resistor R
f
	​

Ground to non-inverting terminal
Apply power supply (±V).
Provide an input signal (e.g., sine wave).
Measure output using an oscilloscope.
Calculate gain and compare with theoretical value.
#  Precautions
Ensure proper power supply polarity.
Use appropriate resistor values to avoid saturation.
Check connections before powering the circuit.
Avoid noise and loose connections.
# Result
Output signal is inverted (180° phase shift).
Gain matches approximately with theoretical value:
A
v
	​

=−
R
in
	​

R
f
	​

	​


Example:

R
f
	​

=10kΩ, R
in
	​

=1kΩ
Gain = -10
# Project Structure
Inverting-OpAmp/
│── inverting_opamp.vi / circuit_diagram.png
│── README.md
# Applications
Signal inversion
Audio amplification
Analog signal processing
Active filters
