# Clampers

Clamper:
Shifts the entire waveform up or down without changing shape or amplitude.

Purpose:
Level Shifting
DC Restoration
Signal Conditioning

Components:
Diode
Capacitor
Resistor

Positive Clamper:
Shifts Waveform Upward
Example:
Input = -5V to +5V
Output = 0V to +10V

Memory:
Anode → GND

Negative Clamper:
Shifts Waveform Downward

Example:
Input = -5V to +5V
Output = -10V to 0V

Memory:
Cathode → GND

Biased Clamper:
Uses Diode + Capacitor + Resistor + Bias Source
Shifts waveform to desired voltage level.

Clipper vs Clamper:
Clipper:
Cuts Waveform
Amplitude Changes

Clamper:
Shifts Waveform
Amplitude Same

Applications:
ADC Signal Shifting
Communication Systems
Video Circuits
Oscilloscopes
Signal Conditioning

Memory Map:
Clamper → Shifts Waveform
Positive Clamper → Moves Up
Negative Clamper → Moves Down
Biased Clamper → Moves to Desired Level