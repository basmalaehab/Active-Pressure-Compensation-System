# Active-Pressure-Compensation-System
a system designed to regulate the internal pressure in a sealed environment to match the external (ambient) pressure. This helps prevent structural damage, maintain functionality of sensitive components.

# System Goal
Maintain a positive pressure differential between internal and external environments by controlling two solenoid valves:
- Inlet Valve: Adds pressure (from compressor)
- Exhaust Valve: Releases excess pressure

# Fuzzy Logic Control (SISO)
We implemented a SISO fuzzy logic system using LabVIEW. The system uses only pressure error as its input, and based on this, it decides:
- Whether to open the inlet valve
- Or open the exhaust valve
- Or keep both valves closed

# Implementation Tools
- LabVIEW for fuzzy logic
- Fuzzy Logic Controller (custom rule-based)
- STM32 to interface pressure sensors and control solenoid valves
