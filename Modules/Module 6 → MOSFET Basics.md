# MOSFET

1. Introduction to MOSFET
- MOSFET = Metal Oxide Semiconductor Field Effect Transistor
- Voltage controlled device
- Terminals: Gate, Drain, Source
- Main control voltage: VGS

2. MOSFET Construction
- Gate insulated by SiO2
- Gate current ≈ 0
- Intrinsic body diode present

3. Working Principle
- VGS creates channel
- No channel = OFF
- Channel formed = ON
- VGS(th) starts conduction

4. Enhancement MOSFET
- Normally OFF
- N-MOS: Positive VGS → ON
- P-MOS: Negative VGS → ON

5. Depletion MOSFET
- Normally ON
- N-MOS: Negative VGS → OFF
- P-MOS: Positive VGS → OFF

6. Operating Regions
- Cutoff = OFF
- Triode (Linear) = ON
- Saturation = Amplifier region

7. MOSFET as Switch
- N-MOS Low Side:
  Gate HIGH → ON
  Gate LOW → OFF
- P-MOS High Side:
  Gate LOW → ON
  Gate HIGH → OFF

8. Gate Resistor
- Limits gate charging current
- Typical: 47Ω to 220Ω
- Common: 100Ω

9. Pull-Up / Pull-Down
- Prevent floating gate
- N-MOS uses Pull-Down
- P-MOS uses Pull-Up
- Common value: 10kΩ

10. Logic Level MOSFET
- Suitable for 3.3V/5V MCU
- VGS(th) is not fully ON voltage
- Check RDS(on) at actual gate voltage

11. Applications
- LED Driver
- Relay Driver
- Motor Driver
- Solenoid Driver
- Fan Driver
- Flyback diode required for inductive loads

12. Selection Parameters
- VDS = Voltage rating
- ID = Current rating
- VGS(th) = Start conduction voltage
- RDS(on) = ON resistance
- Lower RDS(on) = Lower heat

13. BJT vs MOSFET
- BJT = Current controlled
- MOSFET = Voltage controlled
- MOSFET is faster and more efficient

Important Formula
- VGS = VG - VS
- Power Loss = I² × RDS(on)

Quick Revision
- Enhancement = Normally OFF
- Depletion = Normally ON
- N-MOS Gate HIGH → ON
- P-MOS Gate LOW → ON
- Cutoff = OFF
- Triode = ON
- Saturation = Amplifier
