# Operational Amplifier (Op-Amp)

Op-Amp Basics
- Op-Amp = Operational Amplifier
- Inputs: Non-Inverting (+), Inverting (-)
- Formula: Vout = A(V+ - V-)

Ideal Op-Amp
- Gain = Infinity
- Input Impedance = Infinity
- Output Impedance = 0 Ohm
- Bandwidth = Infinity

Memory:
Input Takes Nothing
Output Gives Everything

Golden Rules
- I+ = I- = 0
- V+ = V- (with negative feedback)

Virtual Short
- V+ = V-
- No physical connection

Virtual Ground
- V+ = 0V
- V- = 0V
- No actual ground connection

Inverting Amplifier
- Input -> (-)
- (+) -> Ground
- Gain = -Rf/Rin
- Vout = -(Rf/Rin)Vin

Non-Inverting Amplifier
- Input -> (+)
- Gain = 1 + (Rf/Rin)
- Vout = (1 + Rf/Rin)Vin

Voltage Follower (Buffer)
- Gain = 1
- Vout = Vin
- High Input Impedance
- Low Output Impedance
- Sensor -> Buffer -> ADC

Comparator
Non-Inverting:
Vin > Vref -> HIGH
Vin < Vref -> LOW

Inverting:
Vin > Vref -> LOW
Vin < Vref -> HIGH

Shunt Current Sensing
- V = I x R
- Current -> Shunt -> Op-Amp -> ADC -> MCU

Bandwidth
- Maximum frequency amplified correctly
- Higher Gain -> Lower Bandwidth

Op-Amp Selection
- LM358 -> Most Common
- LM324 -> 4 Op-Amps
- LM741 -> Old Op-Amp
- Rail-to-Rail -> Precision ADC

Important Revision
- I+ = I- = 0
- V+ = V-
- Inverting Gain = -Rf/Rin
- Non-Inverting Gain = 1 + Rf/Rin
- Buffer = Vout = Vin
- Comparator = Voltage Comparison
- Current Sensing = V = I x R
