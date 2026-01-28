# Day 2 – Analog IC Design (Hands-on & Circuits)

The Day 2: learning and hands-on circuits designed during the
Analog and Mixed-Signal IC Design training program using Cadence Virtuoso.

---

## Circuit 2 – Common Source Amplifier with Active Load

- Implemented a common-source (CS) amplifier using NMOS as input device.
- PMOS transistor used as active load.
- Bias voltages were applied to set proper operating point by warying W2.
- Output taken at the drain node.
- Small-signal gain expression:
  
  Av = − gm × ro

- Observed inversion of output signal with respect to input.
- Circuit helped understand:
  - Biasing
  - Gain
  - Saturation region operation

---

## Circuit 3 – Common Source Amplifier with Current Mirror Load

- NMOS transistor used as amplifying device.
- PMOS current mirror used as active load.
- Improved gain compared to resistive load.
- Bias voltage applied to mirror transistor.
- Small-signal gain expression:

  Av = − gm × (ro3 || ro4)

- Helped in understanding:
  - Current mirror operation
  - Output resistance enhancement
  - Gain improvement techniques

---

## Circuit 4 – Differential Amplifier

- Designed a MOSFET differential amplifier.
- Two NMOS transistors used as differential pair.
- PMOS transistors used as active loads.
- Tail current source implemented using NMOS.
- Differential input applied to both gates.
- Output taken from one side of the differential pair.
- Key observations:
  - Differential operation
  - Common-mode rejection
  - Bias current control
- Forms the core block of operational amplifiers.

---

## Symbol Creation of Operational Amplifier

- Created Op-Amp symbol using the previously designed differential amplifier circuit.
- Pins defined:
  - Differential inputs (+, −)
  - Output
  - Power supply (VDD)
  - Ground (VSS)
- Differential amplifier as a functional Op-Amp block.

---

## Bandgap Reference (BGR) Circuit

- Bandgap Reference circuit was discussed and implemented at circuit level.
- Focus was on understanding:
  - Circuit structure
  - Use of BJTs/MOS devices
- Aim of BGR:
  - Generate temperature-independent reference voltage
- Only circuit implementation was performed (no detailed analysis).

---

## Conclusion

- Designed and analyzed CS amplifiers with different loads.
- Understood current mirror based gain enhancement.
- Learned working of differential amplifier.
- Created Op-Amp symbol using differential amplifier circuit.
- Implemented Bandgap Reference circuit at schematic level.
- Gained further hands-on experience with Cadence Virtuoso tools.

---
