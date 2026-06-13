# Clippers

Clipper:
Cuts a selected portion of a waveform.

Purpose:
Voltage Limiting
Overvoltage Protection
Wave Shaping

Components:
Diode + Resistor

Positive Clipper:
Positive Half → Clipped
Negative Half → Passed

Memory:
Cathode → GND

Negative Clipper:
Negative Half → Clipped
Positive Half → Passed

Memory:
Anode → GND

Biased Clipper:
Clip at Desired Voltage

Positive Clip Level:
Vclip = Vbias + 0.7V

Negative Clip Level:
Vclip = -(Vbias + 0.7V)

Clipper vs Clamper:
Clipper:
Cuts Waveform
Amplitude Changes

Clamper:
Shifts Waveform
Amplitude Same

Applications:
MCU Input Protection
ADC Protection
Overvoltage Protection
Signal Limiting
Communication Circuits
Wave Shaping

Memory Map:
Clipper → Cuts Waveform
Positive Clipper → Cuts Positive Half
Negative Clipper → Cuts Negative Half
Biased Clipper → Cuts at Selected Voltage