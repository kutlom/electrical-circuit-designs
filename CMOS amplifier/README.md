# CMOS Push-Pull Amplifiers (Class A, B, AB) — LTSpice
## Overview
This repository contains LTspice schematics and simulations of CMOS push-pull amplifiers operating in Class A, Class B, and Class AB configurations. The designs illustrate fundamental trade-offs between linearity, efficiency, quiescent current, and distortion in analog amplifier design.
Each amplifier was implemented and analyzed using LTspice.

## Amplifier Classes
### Class A
- Both NMOS and PMOS conduct for the full signal cycle (360°)
- Highest linearity, minimal distortion
- High quiescent current and poor efficiency
- Significant static power dissipation
### Class B
- NMOS and PMOS conduct for ~180° each
- Improved efficiency and minimal static power
- Exhibits crossover distortion near zero input
### Class AB
- Small bias current keeps both devices slightly on
- Greatly reduced crossover distortion
- Balanced trade-off between efficiency and linearity

## Comparison Summary
  Class	Linearity	Efficiency	Quiescent Current	Distortion
A	Excellent	Poor	High	Very Low
B	Moderate	High	Very Low	High (Crossover)
AB	Good–Excellent	Moderate–High	Moderate	Low

## Tools & Concepts
- LTspice for schematic capture and transient simulation
- CMOS NMOS/PMOS push-pull output stages
- Biasing strategies and operating-region analysis

## Key Takeaways
- Biasing determines amplifier class and performance
- Class AB offers the best practical compromise for CMOS amplifiers
- Crossover distortion in Class B can be mitigated through biasing
- LTspice enables rapid evaluation of analog design trade-offs
