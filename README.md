# Nintendo 64 U12 LDO Repair PCB
KiCad Project for Nintendo 64 U12 LDO Repair PCB

# Background

I came across a Nintendo 64 NUS-CPU-05 motherboard with a seemingly dead Sharp PQ7VZ5 linear regulator at U12. This component is obsolete and has an awkward pinout which prevents simple replacement.

This PCB is an attempt to substitute the Sharp PQ7VZ5 linear regulator using a compatible footprint connected to a Texas Instruments TLV78525PDBVR. This linear regulator has a fixed output of 2.5V and it's extremely cheap and common, making it a suitable replacement.

Theoretically, this PCB would work for any Sharp PQ7VZ5 linear regulator replacement, but please note that other changes may be required when using other voltages.

# BOM

| Component | Manufacturer | Description | Quantity | DigiKey Part # |
| -- | -- | -- | -- | -- |
| U1 | Texas Instruments | Linear Voltage Regulator IC Positive Fixed 1 Output 500mA SOT-23-5 | 1 | 296-TLV78525PDBVRCT-ND |
| C1, C2 | Murata Electronics | 1 µF ±20% 16V Ceramic Capacitor X5R 0402 (1005 Metric) | 2 | 490-14599-1-ND
| R1 | Stackpole Electronics Inc | 100 kOhms ±5% 0.063W, 1/16W Chip Resistor 0402 (1005 Metric) Automotive AEC-Q200 Thick Film | 1 | RMCF0402JT100KCT-ND

# Render

![PCB Render](https://github.com/jutrasb/n64-u12-ldo-repair-pcb/blob/main/Images/pcb_render.png?raw=true)