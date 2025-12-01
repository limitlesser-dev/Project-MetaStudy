This is a crucial chapter, shifting us from Electrostatics (charge at rest) to Electrokinematics/Electrodynamics (charge in motion). To achieve that 90% mark, we must meticulously cover the fundamentals, master the derivations, and flawlessly execute circuit analysis using Kirchhoff's Laws.

Here is your comprehensive roadmap to teach and finish the chapter on Current Electricity:

---

## Roadmap for Current Electricity (Chapter Mastery for 90% Marks)

### Phase 1: The Core Fundamentals (Review & Definition)

We start with the basics; while this may feel like 10th grade, absolute clarity here is mandatory.

1. **Electric Current & Electricity:**
    - **Electricity:** Defined as a form of energy generated when charge particles are in motion.
    - **Electric Current (I):** Defined as the rate of flow of charge. Mathematically, $I = \Delta Q / \Delta t$ (for steady current) or $I = dQ/dt$ (for instantaneous current).
    - **SI Unit:** Ampere (A), named after André-Marie Ampère. $1 \text{ Ampere}$ is defined as $1 \text{ Coulomb}$ of charge passing per second.
2. **Types of Current and Direction:**
    - **Conventional Current:** Flows from the positive terminal to the negative terminal. This convention was established before the discovery of electrons.
    - **Electronic Current:** Flows in the direction of electron movement (from negative to positive terminal). _Remember:_ Current is always opposite to the direction of electron flow.
3. **Electromotive Force (EMF):**
    - **Definition:** EMF ($\epsilon$ or $E$) is essentially Voltage or Potential Difference, but specifically defined as the work done by the source (cell/battery) in taking a unit positive charge from the lower potential to the higher potential terminal (or across the entire circuit).
    - **Difference from Potential Difference (V):** EMF is the maximum potential difference of a circuit. It is the potential difference between terminals in an _open circuit_ (no current flowing). Potential difference (V) is measured across any two points in the external circuit.
    - **Units:** Volt (V) or Joule per Coulomb (J/C).

### Phase 2: Ohm's Law and Microscopic Theory (The Crucial Derivations)

This section contains the derivations that are guaranteed to earn you marks. You _must_ know the microscopic theory perfectly.

1. **Ohm's Law:**
    - **Statement:** At constant temperature and constant dimensions, the current flowing through a conductor (I) is directly proportional to the potential difference (V) applied across its ends.
    - **Mathematical Form:** $V \propto I$ or $V = IR$, where $R$ is the constant of proportionality called Resistance.
2. **Drift Velocity ($v_d$) and Relaxation Time ($\tau$):**
    - **Drift Velocity:** The average velocity with which free electrons drift towards the positive terminal when an electric field is applied.
    - **Relaxation Time ($\tau$):** The average time gap between two successive collisions of a charge particle (electron) inside the conductor.
3. **Derivation of Drift Velocity:**
    - Using kinematic equation ($v = u + at$) and Newton's second law ($F=ma$ where $F=qE$): $$\vec{v}_d = -\frac{e\vec{E}\tau}{m}$$
    - _Note:_ The negative sign indicates that the drift velocity is opposite to the electric field direction.
4. **Relation between Current (I) and Drift Velocity ($v_d$):**
    - This is essential for relating the microscopic movement to the macroscopic current.
    - $$I = n e A v_d$$ (Magnitude, ignoring the sign).
    - _Note:_ Current is directly proportional to drift velocity.
5. **Derivation of Ohm's Law (Microscopic Form):**
    - **A High-Value Derivation!** You must substitute the $v_d$ formula into the $I$ formula, and then use the relation $E = V/L$.
    - The result yields: $V = \left(\frac{m}{n e^2 \tau}\right) \frac{L}{A} I$.
    - Comparing this to $V=IR$, the resistance $R$ is identified as $R = \left(\frac{m}{n e^2 \tau}\right) \frac{L}{A}$.
6. **Current Density ($\vec{J}$), Conductivity ($\sigma$), and Mobility ($\mu$):**
    - **Current Density ($\vec{J}$):** Current flowing per unit area perpendicular to the flow. $\vec{J} = I/A$. SI Unit: A/m$^2$. $\vec{J}$ is a vector quantity.
    - **Microscopic Ohm's Law (Vector Form):** $\vec{E} = \rho \vec{J}$ or $\vec{J} = \sigma \vec{E}$.
    - **Conductivity ($\sigma$):** Reciprocal of resistivity ($\sigma = 1/\rho$). $\sigma = \frac{n e^2 \tau}{m}$.
    - **Mobility ($\mu$):** Magnitude of drift velocity per unit electric field applied. $\mu = |v_d|/E$. The relation $\mu = \frac{e\tau}{m}$ follows from the drift velocity formula.

### Phase 3: Resistance, Resistivity, and Temperature Dependence

This phase focuses on the factors affecting resistance and how materials are classified.

1. **Factors Affecting Resistance (R):**
    - **Length (L):** $R \propto L$ (directly proportional).
    - **Area of Cross-section (A):** $R \propto 1/A$ (inversely proportional).
    - **Nature of Material and Temperature:** These are combined into resistivity ($\rho$).
    - **Combined Formula:** $R = \rho L/A$.
2. **Resistivity ($\rho$):**
    - **Definition:** The proportionality constant in the resistance formula, depending only on the nature of the material and temperature.
    - **SI Unit:** Ohm-meter ($\Omega \cdot m$).
3. **Classification of Materials by Resistivity:**
    - **Conductors:** Very low resistivity ($10^{-8} \Omega\cdot m$ to $10^{-6} \Omega\cdot m$).
    - **Insulators:** Very high resistivity ($10^8 \Omega\cdot m$ or more).
    - **Semiconductors/Alloys:** Resistivity in the middle range ($10^{-4} \Omega\cdot m$ to $10^6 \Omega\cdot m$).
4. **Temperature Dependence of Resistivity/Resistance:**
    - **The Second Crucial Formula:** For metallic conductors, increasing temperature increases resistivity/resistance.
    - The relation is: $R_T = R_0 [1 + \alpha (T - T_0)]$ or $\rho_T = \rho_0 [1 + \alpha (T - T_0)]$.
    - ($\alpha$ is the temperature coefficient of resistivity).
    - _Qualitative Understanding:_ For conductors, increased temperature decreases relaxation time ($\tau$), thereby increasing $\rho$. For semiconductors, $n$ (number density of charge carriers) increases significantly, causing $\rho$ to decrease with temperature.

### Phase 4: Electrical Energy, Power, and Cells

Focus on how energy is dissipated and the practical handling of batteries.

1. **Electrical Energy and Power:**
    - **Power (P):** Rate of doing electrical work, or electrical energy dissipated per unit time. $P = W/\Delta t$.
    - **Power Formula Derivations:** Starting from $P = W/t$ and $V = W/Q$:
        - $$P = V I$$.
        - $$P = I^2 R$$.
        - $$P = V^2 / R$$.
    - **Joule's Law of Heating:** The heat produced ($H$ or $W$) in time $t$ is $H = I^2 R t$. This energy dissipation is caused by collisions (friction) between electrons and ions.
    - **Commercial Unit of Energy:** Kilowatt-hour (kWh), often called a 'Unit'. $1 \text{ kWh} = 3.6 \times 10^6$ Joules.
2. **Internal Resistance ($r$) and Terminal Voltage ($V$):**
    - **Internal Resistance:** The resistance offered by the electrolyte inside the cell itself.
    - **Terminal Voltage (V):**
        - **Discharging Case (Standard Use):** $V = E - I r$. (This shows $E > V$).
        - **Charging Case:** $V = E + I r$.
    - **V vs. I Graph:** Plotting Terminal Voltage (V) on the y-axis against Current (I) on the x-axis results in a downward sloping straight line.
        - The Y-intercept gives the total EMF ($E$).
        - The slope ($m$) gives the negative of the internal resistance ($-r$).

### Phase 5: Complex Circuit Analysis (High-Value Questions)

This is the ultimate test of your understanding. Questions involving these topics carry the highest weightage.

1. **Kirchhoff's Rules:** These are necessary when simple series/parallel rules are insufficient.
    - **First Law (Junction Rule / KCL):** The sum of currents entering a junction equals the sum of currents leaving the junction.
        - **Basis:** Law of Conservation of Charge.
        - **Application:** Used to relate currents at a branching point.
    - **Second Law (Loop Rule / KVL):** The algebraic sum of changes in potential (EMF and voltage drop across resistors) around any closed loop is zero.
        - **Basis:** Law of Conservation of Energy.
        - **Sign Conventions:** Critical to master for applying KVL.
2. **Wheatstone Bridge:**
    - **Arrangement:** Five resistances arranged in a specific configuration, typically used to determine an unknown resistance.
    - **Balance Condition:** If the current through the central galvanometer arm ($I_G$) is zero, the bridge is balanced.
    - **Balance Condition Formula (Must be derived using KVL):** $$\frac{P}{Q} = \frac{R}{S}$$.
    - _Note:_ When the bridge is balanced, the points connected to the galvanometer are at the same potential, and the galvanometer resistance can be ignored for calculating net resistance.
3. **Cells in Series and Parallel:**
    - **Series Combination:** Total EMF adds up ($E_{eq} = E_1 + E_2 + E_3 + ...$), and internal resistance adds up ($R_{eq} = R_1 + R_2 + R_3 + ...$). (Used when maximum voltage is needed, e.g., in a TV remote).
    - **Parallel Combination:** Total internal resistance uses the reciprocal rule (like parallel resistors). Total EMF uses the formula: $$\frac{E_{eq}}{R_{eq}} = \frac{E_1}{R_1} + \frac{E_2}{R_2} + \frac{E_3}{R_3} + ...$$. (Used when cells require the same charging potential).

---

### Your Action Plan for 90%

1. **Skip/Revise Strategy:** If you've seen this chapter before, use the timestamps provided in the source to jump straight to the high-value questions (Part 1 questions start at 1 hour 30 minutes; Part 2 questions start at 2 hours 39 minutes).
2. **Master Derivations:** Focus intensely on the derivations for Ohm's Law (microscopic), Drift Velocity, and the Wheatstone Bridge balance condition.
3. **Practice KVL/KCL:** Solve complex circuit problems (like Example 3.6 and the related questions in the source) multiple times.
4. **Analyze Graphs:** Understand the V-I graph for internal resistance (slope is $-r$, intercept is $E$).

By focusing on these phases and high-yield topics, you will cover the chapter comprehensively and secure the knowledge necessary for high marks. Now, go finish this chapter!