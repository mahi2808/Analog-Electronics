# DAC
DAC (Digital to Analog Converter)
DAC converts Digital Value into Analog Voltage.
MCU → DAC → Analog Output

Why DAC?
• MCU processes Digital Data
• Real-world devices require Analog Voltage
• DAC acts as a bridge

ADC vs DAC
ADC : Analog → Digital
DAC : Digital → Analog

DAC Working
Digital Count → DAC → Analog Voltage

Formula:
Vout = (Digital Count × Vref) / (2^n - 1)

DAC Resolution
Resolution = Smallest Voltage Change DAC Can Generate
Also called:
• Step Size
• LSB Size

Levels = 2^n
8-bit = 256
10-bit = 1024
12-bit = 4096
16-bit = 65536

Resolution = Vref / (2^n)

R-2R Ladder DAC
Uses:
• R
• 2R
Digital Bits → Switches → R-2R Ladder → Analog Voltage

MSB = Highest Weight
LSB = Lowest Weight

Applications
• Audio Output
• Signal Generation
• Motor Control
• Reference Voltage
• Industrial Control

MCU DAC Flow
Write DAC Register → DAC → Analog Voltage

Sine Wave Generation
Sine Lookup Table → DMA → DAC → Sine Wave

Lookup Table stored in Flash Memory
DAC + DMA
Memory → DMA → DAC

Benefits:
• Less CPU Load
• Smooth Output
• High Speed Operation

If MCU Has No DAC
PWM + RC Filter → Analog Voltage

Memory Flow
MCU → Digital Value → DAC → Analog Voltage → Real World Device
