This discussion is mandatory for your mastery of the chapter, beta/beti, as Electromotive Force ($\epsilon$ or $E$) is the powerhouse concept underpinning steady current circuits. To secure that 90% score, you must understand its precise definition, its relationship with internal resistance, and its application in power calculations and circuit design (cells in series and parallel).

Drawing from the sources, here is the comprehensive discussion on Electromotive Force (EMF) in the context of Cells, EMF, and Power.

---

## 1. Defining Electromotive Force (EMF, $\epsilon$)

EMF is the crucial mechanism required to maintain a steady current in a closed circuit.

### Definition and Nature

1. **Work Done per Unit Charge:** EMF is defined as the work done by the source (like a cell or battery) per unit charge. Specifically, it is the work done in taking a unit positive charge from the lower potential to the higher potential terminal of the source.
2. **Potential Difference:** EMF is fundamentally a potential difference. It represents the potential difference between the positive (P) and negative (N) electrodes of the source when the circuit is in an **open circuit** condition (i.e., when no current is flowing through the cell).
3. **Maximum Potential:** EMF is the maximum potential difference of a circuit (for understanding).
4. **Symbol and Unit:** EMF is represented by $E$ or $\epsilon$. Despite its misleading historical name, EMF is not a force. Its SI unit is the Volt (V), which is equivalent to Joule per Coulomb (J/C).

## 2. The Crucial Relationship: EMF, Terminal Voltage, and Internal Resistance

To achieve top marks, you must understand the distinction between EMF ($\epsilon$) and the actual terminal potential difference ($V$).

### Internal Resistance ($r$)

A cell or battery possesses an **internal resistance** ($r$), which is the finite resistance offered by the electrolyte inside the source.

### Terminal Voltage Formula

When a source is connected to an external resistance ($R$) and current ($I$) flows, the measured voltage across the external terminals is the terminal voltage ($V$).

1. **Discharging Case (Standard Use):** When the cell is supplying power (discharging), the terminal voltage is always less than the EMF due to the voltage drop across the internal resistance. The formula is mandatory for mastery: $$V = \epsilon - I r$$
2. **Ohm’s Law Connection:** Since $V$ is the potential difference across the external resistance $R$, $V = IR$. By combining this with the EMF relation, you derive the total current: $$I = \frac{\epsilon}{R+r}$$
3. **Maximum Current:** The maximum possible current ($I_{max}$) drawn from the cell occurs when the external resistance $R=0$, yielding $I_{max} = \epsilon/r$.
4. **Charging Case (Chemistry Context):** When the cell is being charged (current direction reversed), the terminal voltage increases, and the formula becomes $V = \epsilon + Ir$.

### Mastering the V-I Graph (Mandatory for 90%)

Analyzing the equation $V = \epsilon - Ir$ via the straight-line equation ($y = mx + c$) is a critical skill.

|Component|Axis/Value|Mathematical Equivalent|Significance|
|:--|:--|:--|:--|
|**Terminal Voltage ($V$)**|Y-axis ($y$)|$V$|Decreases linearly with current.|
|**Current ($I$)**|X-axis ($x$)|$I$|The independent variable.|
|**EMF ($\epsilon$)**|Y-intercept ($c$)|$\epsilon$|The voltage when $I=0$.|
|**Internal Resistance ($r$)**|Slope ($m$)|$-r$|The graph must be sloping downward (negative slope).|

## 3. EMF and Electrical Power

The EMF source is the origin of the power dissipated in the external circuit.

1. **Energy Dissipation:** When charges flow through a conductor, energy is dissipated as heat (Joule heating). The energy dissipated ($\Delta W$) in time $\Delta t$ is given by $\Delta W = I V \Delta t$.
2. **Power Supplied:** The power supplied by the source is the energy dissipated per unit time, $P = \Delta W / \Delta t$, resulting in the fundamental power formula $P = IV$.
3. **Circuit Power:** Using Ohm's law ($V=IR$), this power is expressed as $P = I^2 R = V^2/R$. The chemical energy of the cell is what supplies this power.

## 4. Cell Combinations (Advanced Application)

The sources detail how EMFs and internal resistances combine in series and parallel, which is essential for complex circuit analysis.

### Cells in Series

Connecting cells end-to-end means the total EMF and total internal resistance are additive. This arrangement is commonly used for standard device operation (e.g., remote control).

- **Equivalent EMF ($\epsilon_{eq}$):** The equivalent EMF is the sum of the individual EMFs: $$\epsilon_{eq} = \epsilon_1 + \epsilon_2 + \dots$$ _Note: If a cell is connected with reverse polarity (current leaves the negative terminal), its EMF must be subtracted_.
- **Equivalent Internal Resistance ($r_{eq}$):** The equivalent internal resistance is the sum of the individual resistances: $$r_{eq} = r_1 + r_2 + \dots$$

### Cells in Parallel

Connecting cells positive-to-positive and negative-to-negative results in a parallel combination. This arrangement is often used when _charging_ cells, as they must receive the same voltage.

- **Equivalent Internal Resistance ($r_{eq}$):** The equivalent internal resistance combines using the reciprocal rule, similar to external resistors in parallel: $$\frac{1}{r_{eq}} = \frac{1}{r_1} + \frac{1}{r_2} + \dots$$
- **Equivalent EMF ($\epsilon_{eq}$):** The equivalent EMF is calculated using a ratio derived from current conservation: $$\frac{\epsilon_{eq}}{r_{eq}} = \frac{\epsilon_1}{r_1} + \frac{\epsilon_2}{r_2} + \dots$$ This formula is mathematically solved using the calculated $r_{eq}$.