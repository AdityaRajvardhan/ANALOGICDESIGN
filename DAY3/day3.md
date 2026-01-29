# Day 3 – Bandgap Reference (BGR) Circuit Analysis

Day 3 was fully focused on the detailed analysis and simulation of the
Bandgap Reference (BGR) circuit using Cadence Virtuoso.

---

## Introduction to Bandgap Reference (BGR)

- Bandgap Reference circuits are used to generate a temperature-independent reference voltage.
- BGR combines:
  - CTAT voltage
  - PTAT voltage
- Proper weighting of CTAT and PTAT terms results in a stable reference voltage.

---

## CTAT (Complementary To Absolute Temperature)

- CTAT voltage decreases with increase in temperature.
- Base-emitter voltage (VBE) of a BJT exhibits CTAT behavior.
- CTAT slope is negative.
- CTAT term contributes to compensating the PTAT increase.

---

## PTAT (Proportional To Absolute Temperature)

- PTAT voltage increases linearly with temperature.
- Generated using ΔVBE between two BJTs operating at different current densities.
- PTAT voltage calculated using:
  
  ΔVBE = (kT / q) · ln(N)

- Calculator tools were used to compute PTAT values accurately.
- PTAT slope is positive.

---

## DC Sweep with Respect to Temperature

- DC sweep analysis was performed by varying temperature.
- Temperature range was swept over defined limits.
- Output voltages of:
  - CTAT
  - PTAT
  were observed.

---

## Graph Analysis of CTAT and PTAT

- CTAT and PTAT voltages were plotted against temperature.
- Observations:
  - CTAT shows decreasing trend with temperature.
  - PTAT shows increasing linear trend with temperature.
- Intersection and compensation behavior verified through plots.

---

## Slope Calculation

- Slopes of CTAT and PTAT curves were calculated from graphs.
- Slope represents voltage change per degree temperature.
- Used slope values to quantify temperature dependency.

---

## Temperature Coefficient Calculation

- Temperature coefficients were determined using calculated slopes.
- Coefficients C1 and C2 were extracted.
- These coefficients define the weighting of:
  - CTAT term
  - PTAT term
- Proper selection of C1 and C2 ensures temperature independence.

---

## Final BGR Voltage Calculation

- Bandgap reference voltage calculated using formula:

  Vref = C1 · VCTAT + C2 · VPTAT

- Coefficient values obtained from slope matching.
- Verified that Vref remains nearly constant across temperature.

---

## Conclusion

- Complete Bandgap Reference circuit analyzed.
- CTAT and PTAT characteristics studied in detail.
- DC temperature sweep performed.
- Slopes extracted from simulation graphs.
- Temperature coefficients C1 and C2 calculated.
- Final BGR voltage validated using analytical formulas and simulation results.
- Gained strong understanding of temperature compensation in IC design.

---
