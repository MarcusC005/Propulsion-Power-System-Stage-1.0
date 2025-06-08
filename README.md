# Four-Phase Interleaved Boost Converter for Ion Propulsion

# Project OverView
This project presents the design and optimization of a four-phase interleaved boost converter developed for aerospace power systems. The converter steps up a regulated 28 V input to 100 V output and serves as the first stage in a three-stage architecture designed to supply 1200 V at 300 W for ion propulsion systems.

The primary design goals were to:

Achieve >95% efficiency (realized: 96.9%)

Maintain output ripple below 500 mV (realized: <50 mV)

This design incorporates aerospace-relevant engineering principles, including:

Multi-phase interleaving for ripple and thermal optimization

A voltage-threshold-based delay mechanism for PWM control

Realistic parasitic modeling for MOSFETs, inductors, and capacitors

A Type III compensation network for robust feedback stability

The project closely follows industry norms and hardware constraints, resulting in a converter topology that is both flight-relevant and scalable to higher voltage levels.

##  Key Specs
- Input: 28 V (regulated spacecraft bus)
- Output: 100 V
- Power: 300 W
- Topology: Four-phase interleaved boost
- Simulated Efficiency: 96.9%
- Output Ripple: <50 mV

##  Documentation
- See attached files –
- Full technical write-up
- Waveform Gallery
- Documentation
- Ltspice Files

##  Highlights
- Voltage-threshold-based phase delay logic
- Type III compensation with parasitic modeling
- Custom soft-start and current balancing architecture
- Aerospace-grade ripple and thermal performance

##  Author
Marcus Cropley  
Studying Master of Electrical Engineering (First Year)
RMIT University  
[Email](mailto:Marcus3691@outlook.com)
