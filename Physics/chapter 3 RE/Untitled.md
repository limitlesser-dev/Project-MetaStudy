# Chapter 3: Current Electricity

## 1.0 Introduction: From Static Charges to Electric Current

In our study of physics so far, we have focused on **Electrostatics**, the branch that deals with electric charges at rest. We explored the forces they exert and the fields they create. This chapter marks a fundamental shift in our perspective as we move into the realm of **Electrodynamics**—the study of charges in motion. The directed movement of these charges constitutes an **electric current**, a phenomenon that powers our modern world. From the simple act of lighting a torch to the dramatic spectacle of lightning striking the earth, the principles of current electricity are at play. In this chapter, we will dissect these principles, starting from the very definition of current and building towards the tools needed to analyze complex electrical circuits.

### 1.1 Defining Electric Current

Electric current is formally defined as the rate of flow of electric charge through a cross-sectional area of a conductor.

For a steady, constant flow of charge, the current (_I_) is the total charge (_q_) that passes through a surface in a given time (_t_): `I = q / t`

However, current is not always steady. For cases where the rate of flow varies with time, we define the instantaneous current as the differential rate of flow of charge: `I = dq / dt`

The SI unit for electric current is the **Ampere (A)**, named after the French physicist André-Marie Ampère. One ampere is defined as the flow of one coulomb of charge per second (1 A = 1 C/s).

### 1.2 Conventional Current vs. Electronic Current

While current is simply the flow of charge, a crucial distinction must be made regarding its direction. This leads to two related concepts: conventional current and electronic current. The historical conventions established before the discovery of the electron are still used in circuit analysis today.

|   |   |
|---|---|
|Conventional Current|Electronic Current|
|This is the historical standard used in all circuit diagrams and analysis. It defines the direction of current as the direction that **positive charge** would flow. Therefore, conventional current flows from the **positive terminal** to the **negative terminal**.|This describes the actual physical flow of charge carriers in solid conductors like metal wires. The charge carriers are negatively charged **electrons**. Electronic current flows from the **negative terminal** to the **positive terminal**.|
|**Key takeaway:** For all practical circuit analysis in this course, we will use the direction of **conventional current**.|**Key takeaway:** The direction of conventional current is **opposite** to the direction of electron flow. When analyzing the underlying physics, it is vital to remember that electrons are the particles actually moving in a metallic conductor.|

But what compels these charges to move in a continuous, sustained flow? To maintain a current, an 'engine' is needed to continuously provide energy to the charges. This leads us to the crucial concept of Electromotive Force (EMF).

--------------------------------------------------------------------------------

## 2.0 Electromotive Force (EMF), Potential Difference, and Ohm's Law

For a continuous current to flow, charges must be moved in a complete circuit. This requires an energy source. Consider the analogy of a water fountain: a pump does work to lift water from a lower reservoir to a higher one, increasing its gravitational potential energy. The water then flows down naturally, but the pump is necessary to maintain the continuous circulation. Similarly, a source of **Electromotive Force (EMF)**, such as a battery or cell, does work on electric charges, moving them from a point of lower potential to a point of higher potential, thereby maintaining the current.

### 2.1 Electromotive Force (EMF)

The **Electromotive Force (ε)** of a source is defined as the work done by the source in moving a unit positive charge from its lower potential terminal to its higher potential terminal.

Mathematically, it is expressed as: `ε = Work Done / Charge`

This abstract definition has a physical origin within the cell. The EMF arises from the potential difference between the electrodes and the adjacent electrolyte solution (`ε = V+ + V–`).

**Key Characteristics of EMF:**

- **Not a Force:** Despite its name, EMF is not a force. It is a potential difference, representing energy per unit charge.
- **Unit:** The SI unit for EMF is the **Volt (V)**, the same as for potential difference.
- **Maximum Potential Difference:** EMF represents the maximum potential difference across the terminals of a source when no current is being drawn from it (i.e., in an open circuit).

### 2.2 Ohm's Law

In 1828, Georg Simon Ohm discovered a fundamental relationship between the voltage applied across a conductor and the current that flows through it.

**Ohm's Law states:**

Provided the physical conditions such as temperature and dimensions remain constant, the current flowing through a conductor is directly proportional to the potential difference applied across its ends.

This proportional relationship is written as: `V ∝ I`

To turn this into an equation, we introduce a constant of proportionality, **Resistance (R)**: `V = IR`

**Resistance (R)** is the property of a substance that opposes the flow of electric current. Its SI unit is the **Ohm (Ω)**. A conductor has a resistance of one ohm if a potential difference of one volt across it results in a current of one ampere.

### 2.3 The V-I Graph for an Ohmic Conductor

A conductor that obeys Ohm's Law is called an **Ohmic conductor**. The relationship between voltage and current for such a conductor can be visualized with a graph.

- A plot of **Voltage (V) versus Current (I)** yields a straight line that passes through the origin. This linear relationship confirms the direct proportionality stated in Ohm's Law.
- The **slope** of this V-I graph is given by `ΔV / ΔI`. According to the equation `V = IR`, this slope is equal to the resistance of the conductor.
    - `Slope = V / I = R`
- **Important Note:** If the axes are reversed and the graph plots **Current (I) versus Voltage (V)**, the graph is still a straight line through the origin. However, the slope is now `ΔI / ΔV`, which is the reciprocal of the resistance.
    - `Slope = I / V = 1/R`

This distinction is a common source of error and requires careful attention when interpreting graphs.

While Ohm's Law provides the fundamental relationship `V = IR`, the value of the resistance `R` itself is not arbitrary; it depends on the specific physical and material properties of the conductor.

--------------------------------------------------------------------------------

## 3.0 Resistance and Resistivity: Material Properties

The resistance of an object is not just a random value; it is an intrinsic property determined by its geometry, the material it is made from, and its temperature. Let's explore the factors that define a conductor's resistance.

### 3.1 Factors Affecting Resistance

The resistance of a conductor is influenced by four primary factors:

- **Length (l):** Resistance is **directly proportional** to the length of the conductor (`R ∝ l`). A longer conductor provides a longer path for the electrons, leading to more collisions with the lattice ions and thus greater opposition to the current.
- **Area of Cross-Section (A):** Resistance is **inversely proportional** to the cross-sectional area (`R ∝ 1/A`). A thicker wire offers more available paths for the electrons to flow, reducing the overall opposition and therefore lowering the resistance.
- **Nature of the Material:** Different materials inherently offer different levels of opposition to current flow. This property is quantified by resistivity.
- **Temperature:** The temperature of the conductor affects its resistance. For metals, resistance generally increases with temperature, while for semiconductors, it decreases. This will be discussed in more detail later.

### 3.2 Resistivity (ρ)

By combining the proportionalities for length and area, we can formulate an equation for resistance. The constant of proportionality introduced is called **resistivity** (or specific resistance), denoted by the Greek letter rho (ρ).

`R = ρ (l / A)`

**Resistivity (ρ)** is an intrinsic property of a material. It is defined as the resistance of a conductor of that material having a unit length and a unit cross-sectional area. Its value depends only on the nature of the material and its temperature. The SI unit for resistivity is the **Ohm-meter (Ω·m)**.

### 3.3 Classification of Materials by Resistivity

Materials can be broadly classified into three categories based on their resistivity values.

|   |   |   |
|---|---|---|
|Material Class|Characteristic Resistivity (at room temp.)|Description|
|**Conductors**|10⁻⁸ Ω·m to 10⁻⁶ Ω·m|Materials like copper and silver that allow electric current to pass through them easily.|
|**Semiconductors**|Intermediate|Materials like silicon and germanium whose resistivity lies between conductors and insulators.|
|**Insulators**|Very high (> ~10¹² Ω·m)|Materials like glass, rubber, and plastic that strongly resist the flow of electric current.|

### 3.4 Conductance (G) and Conductivity (σ)

Just as resistance measures opposition to current, we can also define quantities that measure the ease of current flow.

- **Conductance (G):** This is the reciprocal of resistance. It represents how easily current can flow through a component. `G = 1 / R` The SI unit of conductance is the **Siemens (S)**, which is equivalent to ohm⁻¹ (`Ω⁻¹`).
- **Conductivity (σ):** This is the reciprocal of resistivity. It is an intrinsic property of a material measuring how well it conducts electricity. `σ = 1 / ρ` The SI unit of conductivity is **Siemens per meter (S/m)** or `(Ω·m)⁻¹`.

These macroscopic properties—resistance and resistivity—arise from the collective behavior of countless charge carriers at the microscopic level. To truly understand why a copper wire conducts so well, we must examine the motion of electrons within it.

--------------------------------------------------------------------------------

## 4.0 The Microscopic Origin of Current and Resistivity

The macroscopic laws of current and resistance are governed by the microscopic behavior of electrons within a conductor. In a metallic conductor, the outer electrons of the atoms are not bound to individual atoms but are free to move throughout the material, forming an "electron gas."

In the absence of an external electric field, these free electrons move randomly due to their thermal energy, constantly colliding with the fixed positive ions of the metallic lattice. Their motion is haphazard, with no preferred direction. As a result, the average velocity of the electrons is zero, and there is no net flow of charge, meaning no electric current.

When an electric field is applied across the conductor, a force is exerted on each electron, causing them to accelerate in the direction opposite to the field. This directed motion is superimposed on their random thermal motion. While they still collide with ions, the electrons acquire a net directional velocity.

### 4.1 Drift Velocity and Relaxation Time

Two key concepts are essential for understanding this microscopic behavior:

- **Drift Velocity (v_d):** This is the average velocity with which free electrons are "drifted" towards the positive end of a conductor under the influence of an external electric field. This velocity is very small, typically on the order of millimeters per second.
- **Relaxation Time (τ):** This is the average time interval between two successive collisions of a free electron with the ions of the lattice.

### 4.2 Deriving the Expression for Drift Velocity

We can derive a formula for drift velocity using Newton's second law.

1. The electric force **F** on an electron (charge `-e`) in an electric field **E** is: `F = -eE`
2. This force produces an acceleration **a**: `a = F / m = -eE / m` where _m_ is the mass of the electron.
3. Using the first equation of motion, `v = u + at`, we can find the velocity gained by an electron between collisions. The average initial velocity (`u`) after a collision is zero due to the random nature of the motion. The time (`t`) for which it accelerates is the relaxation time (`τ`). The final average velocity is the drift velocity (`v_d`). `v_d = 0 + aτ`
4. Substituting the expression for acceleration, we get: `v_d = -eEτ / m` The negative sign confirms that the drift velocity of electrons is in the direction opposite to the applied electric field.

### 4.3 The Relationship Between Current and Drift Velocity

We can establish a direct link between the macroscopic current and the microscopic drift velocity.

1. Consider a conductor with length _l_, cross-sectional area _A_, and a number density of free electrons _n_ (number of free electrons per unit volume).
2. The total number of free electrons in this volume is `(n) × (Al)`.
3. The total charge _q_ in this volume is the number of electrons multiplied by the charge of one electron, _e_: `q = (nAl)e`
4. The time _t_ it takes for these electrons to travel the length _l_ at a drift velocity _v_d_ is: `t = l / v_d`
5. Substituting these into the definition of current, `I = q / t`: `I = (nAl)e / (l / v_d) = nAev_d`
6. This gives us the fundamental relationship: `I = neAv_d`

### 4.4 Deduction of Ohm's Law

By combining the two microscopic equations we have derived, we can deduce Ohm's Law from first principles. This is a powerful demonstration of how macroscopic phenomena arise from microscopic physics.

1. Start with our two key equations (using magnitudes for simplicity):
    - `I = neAv_d`
    - `v_d = eEτ / m`
2. Substitute the expression for `v_d` into the equation for `I`: `I = neA (eEτ / m) = (ne²Aτ / m) E`
3. Recall that for a uniform field over a length _l_, the electric field _E_ is related to the potential difference _V_ by `E = V / l`. Substitute this into the equation: `I = (ne²Aτ / m) (V / l)`
4. Rearrange the equation to solve for _V_, grouping the terms: `V = (ml / ne²τA) I`
5. This equation is now in the form of Ohm's Law, `V = RI`. By comparing the two, we can identify the microscopic expression for resistance **R**: `R = ml / ne²τA`
6. Furthermore, we can compare this with the formula `R = ρ (l/A)` to find the microscopic expression for **resistivity ρ**: `ρ = m / ne²τ`

This derivation beautifully connects the macroscopic, measurable quantity of resistance to the fundamental microscopic properties of the material: the mass (_m_) and charge (_e_) of the electron, the number density of charge carriers (_n_), and the relaxation time (_τ_).

--------------------------------------------------------------------------------

## 5.0 Temperature Dependence and Limitations of Ohm's Law

Ohm's Law provides an excellent model for many materials under specific conditions, but it is not a universal law of nature. Its validity is limited, primarily by physical conditions like temperature. Furthermore, many modern electronic components are specifically designed to have non-linear, or "non-ohmic," behavior.

### 5.1 Temperature Dependence of Resistivity

From the microscopic model, we found that resistivity `ρ` is inversely proportional to both the number density of charge carriers (`n`) and the relaxation time (`τ`). Temperature affects these two parameters differently in various materials.

- **For Conductors (Metals):** As temperature increases, the positive ions in the metallic lattice vibrate with greater amplitude. This increased thermal agitation leads to more frequent collisions for the drifting electrons, which **decreases the relaxation time (τ)**. The number density of free electrons (`n`) in a metal is very large and does not change significantly with temperature. Since `ρ ∝ 1/τ`, the decrease in `τ` causes the **resistivity and resistance of metals to increase** with temperature. For most metals, this relationship is approximately linear over a moderate temperature range: `ρ_T = ρ_0 [1 + α(T - T_0)]` where `ρ_T` is the resistivity at temperature `T`, `ρ_0` is the resistivity at a reference temperature `T_0`, and `α` is the **temperature coefficient of resistivity**.

[Instruction to writer: Insert a graph here showing Resistivity vs. Temperature for a typical conductor like copper. The graph should show a nearly straight line with a positive slope, originating from a non-zero resistivity at low temperatures.]

For some alloys like nichrome, the dependence of resistivity on temperature is much weaker and largely linear.

[Instruction to writer: Insert a graph here showing Resistivity vs. Temperature for an alloy like nichrome. The graph should be a straight line with a much smaller positive slope compared to that of a pure conductor.]

- **For Semiconductors and Insulators:** In these materials, the number density of free charge carriers (`n`) is much lower than in metals and is highly dependent on temperature. As temperature increases, thermal energy excites more electrons, breaking them free from their atoms and making them available as charge carriers. This leads to a significant **increase in** `**n**`. While the relaxation time `τ` also decreases due to more collisions, the sharp increase in `n` is the dominant effect. Since `ρ ∝ 1/n`, the overall result is that the **resistivity of semiconductors and insulators decreases** as temperature rises.

[Instruction to writer: Insert a graph here showing Resistivity vs. Temperature for a semiconductor. The graph should be a curve showing a rapid, non-linear decrease in resistivity as temperature increases.]

### 5.2 Omic and Non-Omic Conductors

Based on their adherence to Ohm's Law, materials and devices can be classified into two groups.

- **Omic Conductors:**
    - These are materials that **obey Ohm's Law**.
    - Their voltage-current (V-I) relationship is **linear**, resulting in a straight-line graph that passes through the origin.
    - Their resistance remains constant, independent of the applied voltage or current (assuming constant temperature).
    - **Example:** Most metals, like copper and silver, behave as ohmic conductors over a wide range of conditions.
- **Non-Omic Conductors:**
    - These are materials or devices that **do not obey Ohm's Law**.
    - Their V-I relationship is **non-linear**.
    - Key deviations from Ohm's Law include:
        1. The V-I graph is a curve, not a straight line.
        2. The relationship between V and I may depend on the polarity (sign) of the applied voltage.
        3. The relationship may not be unique, meaning the same current can correspond to more than one voltage value.
    - **Examples:** Semiconductor diodes, transistors, and materials like Gallium Arsenide (GaAs).

Having established the fundamental principles of resistance and its limitations, we can now proceed to analyze how energy is transferred and dissipated within an electrical circuit.

--------------------------------------------------------------------------------

## 6.0 Electrical Energy, Power, and Heating Effect

When an electric current flows through a resistor, the charge carriers repeatedly collide with the atoms of the resistor material. In these collisions, the electrical potential energy of the charges is converted into thermal energy, causing the resistor to heat up. This transformation of energy is a fundamental aspect of all real circuits and is quantified by the concepts of electrical energy and power.

### 6.1 Electric Power (P)

**Electric Power** is the rate at which electrical energy is dissipated or consumed in an electric circuit. `P = Work Done (W) / time (t)`

We can derive the common formulas for electrical power:

1. The work done (`W`) in moving a charge (`q`) through a potential difference (`V`) is `W = qV`.
2. Since current `I = q/t`, we can write `q = It`.
3. Substituting for `q`, we get `W = (It)V = VIt`.
4. Power is `P = W/t`, so `P = VIt / t`. This gives us the fundamental expression for power: `P = VI`

By combining this with Ohm's Law (`V=IR`), we can derive two other useful forms:

- Substituting `V = IR`: `P = (IR)I = I²R`
- Substituting `I = V/R`: `P = V(V/R) = V²/R`

The SI unit of power is the **Watt (W)**, where one watt is equivalent to one joule per second (1 W = 1 J/s).

#### 6.1.1 Application: High-Voltage Power Transmission

The power formulas have a critical real-world application in the transmission of electrical energy from power stations to consumers. To minimize energy loss in transmission cables, power is transmitted at extremely high voltages.

Consider a power `P` that needs to be delivered. The power delivered is `P = VI`. The power lost as heat in the transmission cables, which have a resistance `R_c`, is given by `P_c = I²R_c`.

From the delivery equation, the current required to transmit power `P` at a voltage `V` is `I = P/V`. If we substitute this into the power loss equation, we get:

`P_c = (P/V)² R_c = (P²R_c) / V²`

This result is crucial: for a given amount of power to be delivered (`P`) through cables of a fixed resistance (`R_c`), the power lost (`P_c`) is inversely proportional to the square of the transmission voltage (`P_c ∝ 1/V²`). By transmitting power at very high voltages (hundreds of kilovolts), the current is significantly reduced, which drastically minimizes the energy wasted as heat in the cables.

### 6.2 Joule's Law of Heating

The energy dissipated as heat in a resistor is directly related to the power. Since power is the rate of energy dissipation, the total heat energy (`H`) produced over a time (`t`) is `H = P × t`. Using the power formula `P = I²R`, we arrive at Joule's Law of Heating.

**Joule's Law states** that the heat (`H`) produced in a conductor is directly proportional to:

1. The square of the current (`I²`) flowing through it.
2. The resistance (`R`) of the conductor.
3. The time (`t`) for which the current flows.

This is expressed by the formula: `H = I²RT`

### 6.3 The Commercial Unit of Electrical Energy

While the joule is the SI unit of energy, it is too small for practical use in commercial electricity billing. Utility companies use a larger unit to measure energy consumption.

The commercial unit of electrical energy is the **kilowatt-hour (kWh)**, often referred to simply as one "unit" on an electricity bill.

One kilowatt-hour is the energy consumed when a device with a power of 1 kilowatt (1000 watts) operates for 1 hour. We can convert this to joules: `1 kWh = 1 kW × 1 hr` `1 kWh = 1000 W × 3600 s` `1 kWh = 3,600,000 J = 3.6 × 10⁶ J`

To apply these concepts of power and energy, we must first be able to calculate the currents and voltages in various parts of a circuit. This requires methods for analyzing circuits with multiple components.

--------------------------------------------------------------------------------

## 7.0 Analysis of DC Circuits

Real-world circuits are rarely as simple as a single source and a single resistor. They typically consist of multiple resistors, cells, and other components arranged in complex networks. To analyze these circuits, we need systematic methods to find their equivalent properties and solve for unknown currents and voltages.

### 7.1 Combinations of Resistors

Resistors in a circuit can be connected in two basic ways: in series or in parallel.

#### Series Combination

Resistors are in series when they are connected end-to-end, providing only one path for the current to flow.

- **Current:** The current is the **same** through all resistors in series.
- **Voltage:** The total voltage across the combination is the **sum** of the individual voltages across each resistor (voltage divides).
- **Equivalent Resistance (R_eq):** The total resistance is the sum of the individual resistances. `R_eq = R₁ + R₂ + R₃ + ...`

#### Parallel Combination

Resistors are in parallel when they are connected across the same two points, providing multiple paths for the current.

- **Voltage:** The voltage is the **same** across all resistors in parallel.
- **Current:** The total current entering the combination is the **sum** of the currents in each branch (current divides).
- **Equivalent Resistance (R_eq):** The reciprocal of the equivalent resistance is the sum of the reciprocals of the individual resistances. `1/R_eq = 1/R₁ + 1/R₂ + 1/R₃ + ...`

### 7.2 Cells and Internal Resistance (r)

An ideal cell is a source of constant EMF. However, a real cell is made of materials (like an electrolyte) that have their own resistance. This is called the **internal resistance (r)** of the cell.

Consider a simple circuit where a cell with EMF `ε` and internal resistance `r` is connected to an external resistor `R`.

- The total resistance of the circuit is the sum of the external and internal resistances: `R + r`.
- The total current `I` flowing in the circuit is given by Ohm's Law: `I = ε / (R + r)`

The **terminal voltage (V)** is the potential difference across the terminals of the cell. Its value depends on whether the cell is supplying, receiving, or has no current flow.

1. **Discharging (supplying current):** When the cell delivers current to the circuit, there is a potential drop across its internal resistance. The terminal voltage is given by: `V = ε - Ir` In this state, the terminal voltage `V` is **less than** the EMF `ε`.
2. **Open Circuit (no current):** When no current is drawn from the cell (`I=0`), there is no internal voltage drop. `V = ε` The terminal voltage is **equal to** the EMF. This is the definition of EMF.
3. **Charging (receiving current):** When an external source is used to charge the cell, it pushes current through the cell against its EMF. The external source must overcome both the cell's EMF and its internal resistance. `V = ε + Ir` In this state, the terminal voltage `V` is **greater than** the EMF `ε`.

### 7.3 Combinations of Cells

Like resistors, cells can also be connected in series or parallel.

#### Series Combination

For `n` identical cells connected in series, each with EMF `ε` and internal resistance `r`:

- **Equivalent EMF:** `ε_eq = nε`
- **Equivalent internal resistance:** `r_eq = nr`

#### Parallel Combination

For a parallel combination of cells, the analysis begins with the most general case. For `n` cells (which can be non-identical) with EMFs `ε₁, ε₂, ...` and internal resistances `r₁, r₂, ...`:

- **Equivalent EMF (**`**ε_eq**`**) and Resistance (**`**r_eq**`**)** are given by the general formulas: `1/r_eq = 1/r₁ + 1/r₂ + ... = Σ(1/r_i)` `ε_eq / r_eq = ε₁/r₁ + ε₂/r₂ + ... = Σ(ε_i / r_i)`
- **For** `**n**` **identical cells** in parallel (each with EMF `ε` and resistance `r`), these general formulas simplify significantly:
    - `1/r_eq = n/r` => `r_eq = r/n`
    - `ε_eq / (r/n) = nε/r` => `ε_eq = ε` So, for identical cells in parallel, the equivalent EMF remains the same as a single cell, but the equivalent internal resistance decreases.

For circuits that are too complex to be simplified using these series and parallel rules, a more powerful and universal set of tools is required. These are known as Kirchhoff's Rules.

--------------------------------------------------------------------------------

## 8.0 Kirchhoff's Rules and the Wheatstone Bridge

When analyzing complex electrical networks that cannot be reduced by simple series-parallel combinations, we rely on two fundamental principles formulated by Gustav Kirchhoff. These rules are direct consequences of the laws of conservation of charge and conservation of energy.

### 8.1 Kirchhoff's Rules

#### 1. First Rule (Junction Rule or Current Law)

This rule is based on the **Law of Conservation of Charge**, which implies that charge cannot accumulate at a junction.

**Statement:** The algebraic sum of the currents entering any junction is zero.

A simpler, more intuitive way to state this is: _The total current flowing into a junction must equal the total current flowing out of that junction._ `Σ I_in = Σ I_out`

#### 2. Second Rule (Loop Rule or Voltage Law)

This rule is based on the **Law of Conservation of Energy**. It states that the net change in electric potential energy for a charge moving around any closed loop must be zero.

**Statement:** The algebraic sum of the changes in potential around any closed circuit loop is zero. `Σ ΔV = 0`

**Sign Conventions for Applying the Loop Rule:** To apply the loop rule correctly, a consistent sign convention is essential. As you trace a path around a closed loop:

- **Across Resistors:**
    - When moving **in the direction** of the current, the potential **drops**. The change is **-IR**.
    - When moving **against the direction** of the current, the potential **gains**. The change is **+IR**.
- **Across Cells (EMF Sources):**
    - When moving from the **negative to the positive terminal**, the potential **gains**. The change is **+ε**.
    - When moving from the **positive to the negative terminal**, the potential **drops**. The change is **-ε**.

### 8.2 The Wheatstone Bridge

The Wheatstone bridge is a classic circuit used to measure an unknown electrical resistance. It serves as an excellent application of Kirchhoff's rules.

[Instruction to writer: Insert a clear and labelled diagram of a Wheatstone Bridge circuit here, showing resistors P, Q, R, and S, a cell connected across one diagonal, and a galvanometer (G) connected across the other diagonal.]

The circuit consists of four resistors arranged in a diamond shape (labeled here as P, Q, R, and S). A source of EMF is connected across one diagonal, and a galvanometer (a sensitive current detector) is connected across the other.

#### The Balanced Condition

The bridge is said to be **balanced** when the potential at points B and D is equal, causing no current to flow through the galvanometer (`I_g = 0`).

To derive the condition for this balance, we apply Kirchhoff's loop rule, assuming `I_g = 0`. This implies the current `I₁` flows through both P and Q, and the current `I₂` flows through both R and S.

1. **Apply the loop rule to loop ABDA:** Starting from A and moving clockwise: `-I₁P + I₂R = 0` Rearranging gives: `I₁P = I₂R` (Equation 1)
2. **Apply the loop rule to loop BCDB:** Starting from B and moving clockwise: `-I₁Q + I₂S = 0` Rearranging gives: `I₁Q = I₂S` (Equation 2)
3. **Divide Equation 1 by Equation 2:** `(I₁P) / (I₁Q) = (I₂R) / (I₂S)`

This simplifies to the famous **Wheatstone bridge balancing condition**: `P/Q = R/S`

This principle is highly practical. If three of the resistances are known, the fourth can be varied until the galvanometer reads zero. At that point, the unknown resistance can be calculated with high precision.

--------------------------------------------------------------------------------

These foundational laws and principles—from Ohm's Law to Kirchhoff's Rules—provide the complete toolkit required for the analysis and design of all direct current (DC) electrical circuits.