# Inverting-Operational-Amplifier-in-Multisim
This project demonstrates the design and analysis of an inverting amplifier using an operational amplifier (Op-Amp). The circuit produces an output voltage that is 180° out of phase with the input signal and scaled by a specific gain.

# Objective

To design and verify an inverting op-amp circuit and study its voltage gain, phase inversion, and behavior with different resistor values.

# Theory

An inverting amplifier uses an op-amp with:

Input applied to the inverting terminal (-)
Non-inverting terminal (+) connected to ground
A feedback resistor Rf from output to input

The voltage gain is: Av = -Rf/Rin
​

 Where:
Av = Voltage gain
Rf= Feedback resistor
Rin = Input resistor

The negative sign indicates phase inversion (180° shift).

# Components Required
Operational Amplifier (e.g., LM741 Op-Amp IC)
Resistors (Rin,Rf)
DC power supply (±V)
Function generator (input signal)
Oscilloscope (to observe output)
Breadboard / LabVIEW simulation setup

# Circuit Diagram 
<img width="590" height="300" alt="image" src="https://github.com/user-attachments/assets/1ad62644-ede1-4536-9a32-3d9ecfda79c1" />



<img width="590" height="300" alt="image" src="https://github.com/user-attachments/assets/e2c9cd8c-4ae7-4d93-94a1-2f8994da4ebe" />



# Working Principle
Input signal is applied through Rin to the inverting terminal.
The non-inverting terminal is grounded.
Due to virtual ground, the inverting terminal remains at ~0V.
Current flows through Rin and Rf.
Output voltage is generated across Rf, inverted and amplified.

# Procedure
Set up the op-amp circuit on a breadboard or LabVIEW.
Connect:
Input signal via Rin
Feedback resistor Rf Ground to non-inverting terminal
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
Av = -Rf/Rin
	​
Example:

Rf = 10kΩ, Rin = 1kΩ
Gain = -10

# Applications
1. Signal inversion
2. Audio amplification
3. Analog signal processing
4. Active filters
   

