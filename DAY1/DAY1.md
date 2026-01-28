# Analog and Mixed-Signal IC Design – Class Work Notes

This repository contains class work notes and conceptual understanding gained during the
Five Days Hands-on Training Program on **Analog IC Design and Layout Considerations Using Cadence Tool**.

---

## MOSFET

- MOSFETs are voltage-controlled devices.
- A MOSFET consists of a gate terminal insulated from the semiconductor substrate and two junctions called the source and drain.
- MOSFET operation depends on the gate-source voltage (VGS) and drain-source voltage (VDS).

### Regions of Operation

**Triode (Linear) Region**
- When VDS is small, the MOSFET behaves like a voltage-controlled resistor.
- Drain current depends on both VGS and VDS.

**Saturation Region**
- When VDS exceeds (VGS − VTH), channel pinch-off occurs near the drain.
- The MOSFET behaves as a current source.
- Drain current is proportional to (VGS − VTH)².

**Channel Length Modulation**
- In practical MOSFETs, drain current slightly increases with increase in drain voltage even in saturation region.
- This effect is known as channel length modulation.

---

## Introduction to Mixed-Signal IC Design

- Mixed-signal integrated circuits contain both analog and digital circuits on the same chip.
- These ICs are widely used in:
  - Automotive electronics
  - Wireless communication systems
  - Internet of Things (IoT)
  - System-on-Chip (SoC) designs

---

## IC Design Flows

### Digital IC Design Flow

- Design specification and constraints
- RTL modeling and simulation
- Logic synthesis
- Floorplanning, placement, and routing
- Design Rule Check (DRC) and Layout Versus Schematic (LVS)
- Parasitic extraction
- Post-layout verification and tape-out

### Analog IC Design Flow

- Design specification and topology selection
- Schematic entry and circuit simulation
- Layout using parameterized cells
- Design Rule Check (DRC)
- Layout Versus Schematic (LVS)
- Parasitic extraction
- Post-layout simulation

---

## PVT Variations in IC Design

Integrated circuits must operate reliably under all conditions of:

- Process variation (device parameter changes)
- Voltage variation (supply fluctuation)
- Temperature variation

This combined analysis is referred to as **PVT analysis** and is essential for production-ready ICs.

---

## Three Main Blocks in IC Design

### Bandgap Reference

- Generates a temperature-independent reference voltage.
- Achieved by combining:
  - CTAT voltage (base-emitter voltage of BJT)
  - PTAT voltage (thermal voltage based term)
- The resulting reference voltage remains nearly constant across temperature, supply, and process variations.

### Low Dropout Regulators (LDOs)

- Provide stable and noise-free supply voltages.
- Used to power sensitive analog and digital blocks inside an IC.

### Phase Locked Loops (PLLs)

- Generate accurate and low-jitter clock signals.
- Required for high-speed digital and RF circuits.

---

## Hands-on Session

- A **Common-Source (CS) amplifier** was designed and simulated using **Cadence Virtuoso**.
- The design helped in understanding:
  - Biasing techniques
  - Gain behavior
  - MOSFET operation in saturation region

- Hands-on experience was gained in:
  - Schematic entry using Virtuoso
  - Simulation setup
  - Running analyses
  - Observing voltage and gain characteristics

---

## Conclusion
-In conclusion, learned the fundamentals of analog and mixed-signal IC design including:
- MOSFET structure and operation
- Basics of mixed-signal ICs
- Applications of mixed-signal ICs
- Digital IC design flow
- Analog IC design flow
- Importance of PVT analysis
- Need for bandgap reference
- Role of LDOs in ICs
- Role of PLLs in ICs
- During the hands-on session, a common-source (CS) amplifier was designed and simulated using Virtuoso Cadence to understand biasing, gain, and MOSFET operation in saturation region. 
- The session also provided hands-on experience with Cadence Virtuoso tools including schematic entry, simulation setup, running analyses, and observing voltage and gain characteristics.

---

**DAY 1**
