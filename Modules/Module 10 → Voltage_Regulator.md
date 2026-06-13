# Voltage Regulator Git Notes

Voltage Regulator = Maintains Constant Output Voltage
Why Needed?
Input Voltage Varies
Electronics Need Stable Voltage

Types:
1. Linear Regulator
2. Switching Regulator

Linear Regulator:
7805, 7812, LDO, AMS1117, LM1117

Advantages:
Simple, Low Noise, Low Cost

Disadvantages:
Heat Generation, Low Efficiency
Power Loss = (Vin - Vout) × Iload

7805:
78 = Positive Regulator
05 = 5V Output

Pinout:
Input, Ground, Output (IGO)

7812:
78 = Positive Regulator
12 = 12V Output

78xx = Positive
79xx = Negative

LDO:
Low Dropout Regulator
Dropout Voltage = Vin(min) - Vout

7805 ≈ 2V
LDO ≈ 0.1V to 0.5V

Switching Regulator:
MOSFET Fully ON/OFF
Uses PWM

Buck Converter:
Step-Down Switching Regulator
12V → Buck → 5V
Vout = Duty Cycle × Vin

Linear vs Switching
Linear:
Simple, Low Noise, More Heat

Switching:
Efficient, Less Heat, More Noise

Practical Design:
Battery → Buck → 5V → LDO → 3.3V → MCU
Buck = Efficiency
LDO = Clean Power

Decoupling Capacitor:
Typically 0.1uF near MCU VCC pins
Important Formulas:
Power Loss = (Vin - Vout) × Iload
Dropout Voltage = Vin(min) - Vout

Buck Converter:
Vout = Duty Cycle × Vin
