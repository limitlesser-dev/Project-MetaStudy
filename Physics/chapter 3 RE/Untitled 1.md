**Attention, future high-scorer!** To truly _teach and finish the chapter to get 90% marks_ in Current Electricity, merely reading is insufficient. You need a targeted action plan. This checklist, in your requested Obsidian format, focuses on mastering the core concepts, derivations, and problem types essential for board exams, heavily relying on the concepts emphasized by Ashu Sir and the NCERT excerpts.

Here is your mandatory checklist, beta/beti, ensuring you cover every crucial point:

---

# [[Physics - Current Electricity]] Mastery Checklist (90% Score Goal)

## I. Foundational Concepts & Definitions (The Basic Half Hour)

- [ ] **Define Electric Current ($I$):** Understand it as the rate of flow of charge ($I = dQ/dt$ or $I = \Delta Q / \Delta t$).
- [ ] **Units Mastery:** Know the SI unit is the Ampere (A), defined as 1 Coulomb/second.
- [ ] **Current Direction:** Clearly distinguish [[Conventional Current]] (Positive to Negative) from [[Electronic Current]] (Opposite to electron flow, Negative to Positive).
    - _Crucial Rule:_ Current always flows opposite to the direction of electrons.
- [ ] **Electromotive Force (EMF) ($\epsilon$):** Define EMF as the work done per unit charge by the source in taking charge from lower to higher potential, or the maximum potential difference in an open circuit.
- [ ] **Internal Resistance ($r$):** Define this as the resistance offered by the cell/battery itself.

## II. Ohm's Law and Material Properties (The Core)

- [ ] **Ohm's Law Statement:** State precisely: $V \propto I$, or $V = IR$, ensuring you mention the condition: **constant temperature and dimensions**.
- [ ] **Resistance ($R$):**
    - [ ] Define R (the property that resists current flow, like "circuit friction").
    - [ ] Know the factors $R$ depends on: Length ($L$) (Directly Proportional) and Area ($A$) (Inversely Proportional).
    - [ ] Derive $R = \rho L/A$. **(High Priority Derivation)**
- [ ] **Resistivity ($\rho$):**
    - [ ] Define Resistivity ($\rho$) (The constant in $R = \rho L/A$).
    - [ ] Units: Ohm-meter ($\Omega$ m).
    - [ ] Understand that $\rho$ depends ONLY on Nature of Material and Temperature, NOT dimensions.
    - [ ] **Must Know Ranges:** Memorize the $\rho$ ranges for Conductors ($10^{-8}$ to $10^{-6}$ $\Omega$ m), Insulators ($>10^8$ $\Omega$ m), and Semiconductors ($10^{-4}$ to $10^6$ $\Omega$ m).
- [ ] **Conductance ($G$) and Conductivity ($\sigma$):**
    - [ ] Define $G = 1/R$ and $\sigma = 1/\rho$.
    - [ ] Know units: $G$ is $\Omega^{-1}$ (or Siemens), $\sigma$ is $\Omega^{-1} m^{-1}$.
- [ ] **Temperature Dependence:**
    - [ ] **Conductors:** Apply the formula $R_2 = R_1 [1 + \alpha (T_2 - T_1)]$ (or $\rho_T = \rho_0 [1 + \alpha (T-T_0)]$) for calculating resistance/resistivity at different temperatures. (Practice numericals like Example 3.3/3.4).
    - [ ] Understand _why_ resistance increases with temperature in conductors (collision frequency increases, $\tau$ decreases).

## III. Microscopic Picture & Kinematics (Derivations Galore)

- [ ] **Relaxation Time ($\tau$):** Define it as the average time gap between two successive collisions of a charge particle.
- [ ] **[[Drift Velocity]] ($v_d$):**
    - [ ] **Derivation 1:** Prove $v_d = -e E \tau / m$. **(First major derivation, MUST KNOW)**
    - [ ] **Derivation 2:** Relate Current and Drift Velocity: $I = \pm ne A v_d$ (where $n$ is electron density). **(Second major derivation, MUST KNOW)**
- [ ] **Derive Ohm's Law from Microscopic View:** Combine $v_d$ formulas to show $V = IR$ and simultaneously prove $R \propto L/A$ and find $\rho = m / (n e^2 \tau)$. **(Most Important Derivation for 90%)**
- [ ] **Current Density ($\mathbf{J}$):**
    - [ ] Define $\mathbf{J} = I/A$ (current flow normal to area).
    - [ ] Understand the vector relation $I = \mathbf{J} \cdot \mathbf{A} = J A \cos\theta$.
    - [ ] Vector form of Ohm's Law: $\mathbf{J} = \sigma \mathbf{E}$.
- [ ] **Mobility ($\mu$):**
    - [ ] Define $\mu = |v_d|/E$ (Drift velocity per unit electric field).
    - [ ] Know the expression $\mu = e \tau / m$.

## IV. Electrical Energy, Power & Applications

- [ ] **Power Formulas:** Derive and memorize all forms of electric power: $P = V I$, $P = I^2 R$, and $P = V^2 / R$.
- [ ] **Joule's Law Proof:** Prove that Heat produced ($H$) is $I^2 R t$ using $P=W/t$ and $W=P \cdot t$.
- [ ] **Commercial Energy Unit:** Know the definition and conversion: 1 kilowatt-hour (kWh) = $3.6 \times 10^6$ J. (Used by the electricity board!).
- [ ] **Applications:** Understand the principle behind heating appliances (High resistance Nichrome wire) and electric fuses (Melts due to high $I^2 R t$).

## V. Cells and Combinations

- [ ] **Terminal Voltage Equation:** Master $V = \epsilon - I r$ (Discharging case).
- [ ] **V vs I Graph:** Be ready to plot Terminal Voltage (V) vs. Current (I).
    - [ ] Know the slope is **$-r$** (negative internal resistance).
    - [ ] Know the Y-intercept is $\epsilon$ (EMF). (Practice graph-based PYQs like).
- [ ] **Cell Series Combination:** Know how $E_{eq}$ and $r_{eq}$ add up.
- [ ] **Cell Parallel Combination:** Know the complex formulas for $E_{eq}$ and $r_{eq}$. (Practice the complex parallel numerical).

## VI. Network Analysis (The Numerical Challenge)

- [ ] **[[Kirchhoff's Laws]] (KCL & KVL):**
    - [ ] **Junction Rule (KCL/First Law):** Statement: $\sum I_{in} = \sum I_{out}$. **Principle:** Law of Conservation of Charge.
    - [ ] **Loop Rule (KVL/Second Law):** Statement: Algebraic sum of potential changes around a closed loop is zero ($\sum \Delta V = 0$). **Principle:** Law of Conservation of Energy.
    - [ ] **Sign Conventions:** Practice applying the sign conventions rigorously (especially when moving against current or traversing a cell from + to -).
    - [ ] **Complex Circuit Solving:** Be able to set up the necessary $N$ equations for $N$ unknown currents using both KCL and KVL. (This is a 5-mark question area!)
- [ ] **[[Wheatstone Bridge]] (Essential PYQ Topic):**
    - [ ] **Structure:** Recognize the 5-resistance arrangement.
    - [ ] **Balance Condition Derivation:** Derive the condition: if $I_g = 0$, then $P/Q = R/S$ using KVL. **(MUST DO Derivation)**
    - [ ] **Application:** Recognize a balanced bridge (if $P/Q = R/S$) and know that the central galvanometer branch is irrelevant (zero current flows through it). (Practice complex rearrangement questions like).

## VII. Critical Review and Limitations

- [ ] **Limitations of Ohm's Law:** List and describe the three ways materials can be non-Ohmic (V not proportional to I, dependence on sign of V, non-unique V-I relation; e.g., semiconductors/diodes).
- [ ] **V-I Graph Interpretation:** Quickly differentiate the linear V-I graph of Ohmic conductors (metals) from non-Ohmic ones (semiconductors, GaAs).
- [ ] **Non-Uniform Conductor:** Know that in a conductor with non-uniform area, only the current ($I$) remains constant; $E$ and $v_d$ vary inversely with the area.

---

**Remember, cohort:** Completing this checklist ensures you haven't just 'read' the chapter, but you have actively engaged with the derivations and crucial conceptual questions demanded for a 90%+ score. Now go crush those formulas!