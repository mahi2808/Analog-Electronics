# Filters Git Notes

Filters
Filter = Passes Some Frequencies and Blocks Some Frequencies

Purpose:
Noise Removal
Signal Conditioning
Frequency Selection

Types:
LPF, HPF, BPF, BSF

LPF:
Passes Low Frequencies
Blocks High Frequencies
Capacitor to Ground

HPF:
Passes High Frequencies
Blocks Low Frequencies and DC
Resistor to Ground

Capacitor Reactance:
Xc = 1/(2πfC)

Frequency ↑ => Xc ↓

RC Filter:
Fc = 1/(2πRC)

Cutoff Frequency:
Also called Corner Frequency or -3dB Frequency

At Fc:
Vout = 0.707 × Vin

Band Pass Filter:
Passes Middle Frequencies
Fo = √(FL × FH)
BW = FH - FL

Band Stop Filter:
Blocks Middle Frequencies
Also called Notch Filter

Applications:
ADC Inputs
Sensor Interfaces
Audio Circuits
Communication Systems
50Hz Noise Removal

Important Formulas:
Xc = 1/(2πfC)
Fc = 1/(2πRC)
Fo = √(FL × FH)
BW = FH - FL

Memory Map:
LPF → Pass Low
HPF → Pass High
BPF → Pass Middle
BSF → Block Middle