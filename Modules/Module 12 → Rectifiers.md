# Rectifiers

Rectifier = AC to DC using Diodes
Power Chain:
AC → Transformer → Rectifier → Filter → Regulator → Load

Half Wave Rectifier:
• 1 Diode
• Positive Half Pass
• Negative Half Block
• Efficiency = 40.6%
• Ripple Factor = 1.21
• PIV = Vm

Full Wave Rectifier:
• 2 Diodes + Center Tap
• Uses Both Half Cycles
• Efficiency = 81.2%
• Ripple Factor = 0.482
• PIV = 2Vm
• Output Frequency = 2f

Bridge Rectifier:
• 4 Diodes
• No Center Tap
• Efficiency = 81.2%
• Ripple Factor = 0.482
• PIV = Vm
• Output Frequency = 2f

Ripple Factor:
r = Vr(ac)/Vdc

Efficiency:
η = Pdc/Pac

PIV:
Maximum Reverse Voltage Diode Can Withstand

Filter Capacitor:
Connected Across Load
Purpose: Reduce Ripple
C = I/(f×Vr)

Voltage Rating > Actual Circuit Voltage

Transformer:
Vpeak = Vrms × 1.414

Example:
12V AC RMS → 17V Peak

Memory Map:
Rectifier → AC to DC
HWR → 1 Diode
FWR → 2 Diodes + Center Tap
Bridge → 4 Diodes
Filter Capacitor → Reduces Ripple
Regulator → Stable DC