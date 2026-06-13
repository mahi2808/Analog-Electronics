# BJT (Switching Focus)

1. BJT Construction
- BJT = Bipolar Junction Transistor
- Terminals: Emitter, Base, Collector
- Types: NPN and PNP
- Emitter: Heavily doped
- Base: Thin and lightly doped
- Collector: Moderately doped

2. NPN Transistor
- Structure: N-P-N
- Majority carriers: Electrons
- Arrow points outward
- VC > VB > VE

3. PNP Transistor
- Structure: P-N-P
- Majority carriers: Holes
- Arrow points inward
- VE > VB > VC

4. Transistor Action
- Small base current controls large collector current
- Emitter injects carriers
- Collector collects carriers

5. Current Components
- IE = IC + IB
- IE > IC > IB

6. Current Gain
- α = IC / IE
- β = IC / IB
- Use Forced Beta ≈ 10 for switching

7. Operating Regions
- Cutoff = OFF
- Active = Amplifier
- Saturation = ON

8. Transistor as Switch
- OFF → Cutoff
- ON → Saturation
- VCE(sat) ≈ 0.2V

9. NPN Low-Side Switching
- Load at Collector
- Emitter to Ground
- GPIO HIGH → ON
- GPIO LOW → OFF

10. PNP High-Side Switching
- Emitter to Supply
- Base LOW → ON
- Base HIGH → OFF

11. Base Resistor
- RB = (VIN - 0.7) / IB
- Protects MCU and transistor

12. Driving LEDs using BJT
- LED resistor required
- Base resistor required

13. Driving Relays using BJT
- Relay current becomes collector current
- NPN commonly used

14. Flyback Diode
- Required for relay coils
- Protects against back EMF
- Common diode: 1N4007

15. Practical Applications
- LED Driver
- Relay Driver
- Motor Switching
- Solenoid Control
- Buzzer Driver
- Automotive Loads

Pending Amplifier Topics
16. Common Base (CB)
17. Common Emitter (CE)
18. Common Collector (CC)
19. Input Characteristics
20. Output Characteristics
21. DC Load Line
22. Q-Point
23. Transistor as Amplifier
