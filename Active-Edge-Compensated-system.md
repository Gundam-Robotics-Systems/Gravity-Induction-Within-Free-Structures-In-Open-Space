To solve the "weak corner" issue, the power distribution must shift from a passive, uniform load to an **Active Edge-Compensated** system. In this schematic, the central floor and ceiling areas receive a baseline "Sustaining Charge," while the Peripheral Induction Rails (PIRs) act as independent high-voltage circuits that "lens" the gravity field at the room's boundaries.

---

## Peripheral Induction Rail (PIR) Schematic Logic

The goal is to increase the electron density at the vertices (corners) where the field lines typically diverge or "thin out."

### 1. The Power Distribution Hierarchy

* **Primary Bus (G-Bus Alpha):** Delivers 100% of the standard operating voltage to the main floor/ceiling armor plates.
* **Auxiliary Corner Boosters (ACB):** Step-up transformers located at each 90-degree junction that increase voltage by **15–20%** relative to the center of the room.
* **Edge-Sync Controllers:** High-speed solid-state switches that synchronize the ceiling (+) and floor (-) pulses to ensure the magnetic electron force remains perfectly vertical even at the edges.

---

## Component Layout

### A. The "Corner-Focus" Junction Box

Located behind the armor plating at every corner, this unit contains:

* **Variable Frequency Drive (VFD):** To tune the electron vibration to the resonance of the specific armor plate material.
* **Current Converters:** To prevent "arcing" between the high-voltage corner rail and the standard-voltage floor plates.

### B. The Lensing Rail Design

Instead of a flat plate, the corner rail is **concave**. This physical shape, combined with the higher voltage, physically pushes the electron field lines inward, effectively "filling" the corner with the same gravity density as the center of the room.

---

## Voltage Distribution Profile (Top-Down View)

| Region | Voltage Level | Charge Density | Gravity Effect |
| --- | --- | --- | --- |
| **Room Center** |  |  |  (Stable) |
| **Mid-Wall Edge** |  |  |  (Compensated) |
| **Corner Junction** |  |  |  (Maximum Lensing) |

> **Note on Safety:** To prevent electrostatic discharge (ESD) for crew members, these rails must be insulated with a **Graphene-Ceramic Doped Dielectric**. This allows the magnetic electron force to penetrate the cabin while keeping the high-voltage electrons contained within the armor plates.

---

### Implementation Schematic

The circuit uses a **Parallel Loop** configuration. If one corner booster fails, the adjacent PIRs can "over-drive" to maintain gravity stability in that sector until a "Smart-Slab" replacement can be performed.
