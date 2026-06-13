# BJT Biasing

1. Introduction to BJT Biasing
- Applying DC voltages and currents to a transistor.
- Sets the operating region.

2. Fixed Bias
- Uses one base resistor RB.
- IB = (VCC - VBE)/RB
- IC = β × IB
- Simple but poor stability.

3. Collector Feedback Bias
- RB connected from Collector to Base.
- Negative feedback improves stability.
- IC↑ → VC↓ → IB↓ → IC↓.

4. Emitter Feedback Bias
- Uses emitter resistor RE.
- VE = IE × RE
- VBE = VB - VE
- IC↑ → VE↑ → VBE↓ → IB↓ → IC↓.

5. Voltage Divider Bias
- Most widely used method.
- VB = VCC × R2/(R1+R2)
- VE = VB - 0.7V
- IE = VE/RE
- IC ≈ IE
- Excellent stability.

6. Thermal Stability
- Leakage current increases with temperature.
- VBE decreases with temperature.
- Thermal runaway:
  Temperature↑ → IC↑ → Power↑ → Temperature↑.
- Negative feedback prevents instability.

7. Q-Point
- Quiescent operating point.
- Defined as (IC, VCE).
- No input signal applied.
- Often VCE ≈ VCC/2.

8. DC Load Line
- VCC = ICRC + VCE
- Cutoff: IC=0, VCE=VCC
- Saturation: VCE≈0, IC=VCC/RC
- Q-point lies on load line.

Important Formulas
- IB = (VCC - VBE)/RB
- IC = β × IB
- VE = IE × RE
- RE = VE/IE
- VB = VCC × R2/(R1+R2)
- VE = VB - 0.7
- IE = VE/RE
- IC ≈ IE
- VCC = ICRC + VCE
