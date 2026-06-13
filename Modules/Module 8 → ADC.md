# ADC

ADC (Analog to Digital Converter)
ADC converts Analog Voltage into Digital Value.
Sensor → ADC → MCU

Why ADC?
• Sensors produce Analog Signals.
• MCU processes Digital Data.
• ADC acts as a bridge.

Analog:
• Continuous Signal
• Infinite Values

Digital:
• Discrete Signal
• Finite Values

Sampling:
• Taking measurements at regular intervals.
• Sampling Rate = Samples/sec (Hz)

Sampling = Take Snapshot

Quantization:
• Assigning sampled voltage to nearest digital level.

Quantization = Nearest Digital Level

Resolution:
• Smallest voltage change ADC can detect.
• Also called Step Size or LSB Size.

Levels = 2^n
8-bit = 256
10-bit = 1024
12-bit = 4096
16-bit = 65536

Resolution = Vref / (2^n)

ADC Formula:
Digital Output = (Vin × (2^n - 1)) / Vref
Vin = (ADC Count × Vref) / (2^n - 1)

SAR ADC:
Successive Approximation Register

Uses:
• Sample & Hold
• Comparator
• Binary Search

ADC Errors:
• Quantization Error = Rounding Error
• Offset Error = Constant Shift
• Gain Error = Slope Error

ADC Steps:
Select Channel → Start Conversion → Sampling → SAR Conversion → EOC → Read ADC Register
EOC = End Of Conversion

Sensor Interface:
• High Voltage → Voltage Divider
• Low Voltage → Op-Amp Amplifier
• Noisy Signal → Filter
• Weak Sensor → Buffer
• Current Measurement → Shunt Resistor

Memory Flow:
Sensor → Analog Signal → Sampling → Quantization → SAR ADC → Digital Count → MCU
