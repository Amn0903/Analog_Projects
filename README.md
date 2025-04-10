# Analog Circuit Design: Beta Multiplier, Cascode Current Mirror, and Cascode Amplifier
This project involves the design and simulation of key analog building blocks-**Beta Multiplier**, **Cascode Current Mirror**, and **Cascode Amplifier**-in both **180nm** and **22nm CMOS technology nodes** using **LTspice** for simulation and **Magic VLSI** for layout (180nm only).
## Objective
**Design and simulate:**
- Cascode Current Mirror
- Cascode Amplifier
- Perform simulations in both **180nm** and **22nm** CMOS technology.                              
- Verify key specifications: gain, power dissipation, and unity gain bandwidth (UGB).
- Create corresponding layouts (for 180nm) in Magic VLSI.  
## Tools Used
- LTspice – Circuit simulation
- Magic VLSI  – Layout design (for 180nm)
- Technology: 180nm and 22nm CMOS

## Key Results

| Metric                    | 180nm             | 22nm              |
|--------------------------|-------------------|-------------------|
| Voltage Gain             | 26.01 dB          | 26.02 dB          |
| Power Dissipation        | 0.058 mW          | 0.025 mW          |
| Unity Gain Bandwidth     | 30.22 MHz         | 210 MHz           |
| Frequency Response       | Low-pass Filter   | Low-pass Filter   |
## Layout Design (180nm only)

Layouts for the following were created using Magic:
- Cascode Current Mirror
- Cascode Amplifier

## Observations

- **22nm** technology consumes **less power** and achieves **higher bandwidth**, owing to its smaller transistor size.
- Layout complexity increases in 22nm due to tighter design rules and scale.
- Both technologies meet all design specifications for gain, power, and bandwidth.

## Conclusion

This project successfully demonstrates the complete flow of analog circuit design:
- Schematic → Simulation → Layout (for 180nm)
- All simulation results closely match theoretical expectations.
- Technology comparison highlights the advantages and trade-offs between 180nm and 22nm processes.
