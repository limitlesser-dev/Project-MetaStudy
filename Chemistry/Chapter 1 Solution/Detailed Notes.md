This document provides detailed notes covering the concepts, definitions, formulas, and examples discussed in the provided sources regarding the 12th-grade chemistry chapter on Solutions.

---

## Detailed Notes on Solutions (Class 12 Chemistry)

### I. Introduction and Basic Concepts

**Lecture Context** This lecture serves as the first "one shot" chemistry lecture for 12th grade on the Ashu Ghai 11th & 12th channel. The initial focus is heavily on reviewing NCERT material, although competency-based questions will be introduced later. The first three chapters of 12th-grade physical chemistry (Solutions, Electrochemistry, Chemical Kinetics) are highly numerical, with an approximately 80% chance of a numerical problem arising from these topics.

**Mixtures** A mixture is formed when two or more chemically non-reactive substances are physically mixed together. They are characterized by having **no fixed ratio** (non-fixed composition). Examples of mixtures include air (nitrogen, oxygen, $\text{CO}_2$), blood (RBCs, WBCs, plasma), mineral water, and alloys (e.g., 22- or 23-carat gold, which contains other metals for hardness).

**Types of Mixtures:**

1. **Homogeneous Mixture:**
    - Consists of a single phase (uniform composition).
    - Its properties are the same throughout the mixture.
    - Components cannot be individually seen, even with a microscope.
    - Examples: Salt + Water, Sugar + Water, and Alloys.
2. **Heterogeneous Mixture:**
    - Consists of distinct phases (not uniform composition).
    - Components are individually visible, sometimes requiring a microscope (e.g., blood).
    - Examples: Oil + Water, Sand + Water, Salt + Ethanol (since salt does not dissolve in ethanol).

**Solutions (True Solutions)** A solution is defined as a **homogeneous mixture** of two or more components whose composition can be varied within certain limits.

- **Particle Size:** Solutions have a particle size **less than 1 nanometer** ($< 1 \text{ nm}$ or $10^{-7}$ to $10^{-8} \text{ cm}$). This size is so small that particles cannot be viewed even with an electron microscope.
- **Properties:** Solutions are characterized by **Homogeneity** and the **Absence of Settling** (the particles will never settle out, unlike suspensions like mud in water).
- **Components:** Every solution has two main components:
    - **Solvent (A):** The component generally present in a larger amount, which dissolves the solute.
    - **Solute (B):** The component generally present in a smaller amount, which dissolves in the solvent.

---

### II. Methods of Expressing Concentration

Concentration measures the amount of solute present in a solution. The concentration terms studied in 11th grade are reviewed, using specific symbols where A represents the **Solvent** and B represents the **Solute** ($A+B$ represents the Solution).

|Concentration Term|Definition / Formula|Symbolic Representation|
|:--|:--|:--|
|**Mass Percentage (W/W)**|$(\frac{\text{Mass of Solute}}{\text{Mass of Solution}}) \times 100$|$\frac{W_B}{W_A + W_B} \times 100$|
|**Volume Percentage (V/V)**|$(\frac{\text{Volume of Solute}}{\text{Volume of Solution}}) \times 100$|$\frac{V_B}{V_A + V_B} \times 100$|
|**Mass by Volume % (W/V)**|$(\frac{\text{Mass of Solute}}{\text{Volume of Solution}}) \times 100$|(Used infrequently)|
|**Parts per Million (PPM)**|Used for very low concentrations (trace quantities). $\frac{\text{Mass of Solute}}{\text{Mass of Solution}} \times 10^6$|$\frac{W_B}{W_A + W_B} \times 10^6$|
|**Mole Fraction ($X$)**|Ratio of the number of moles of one component to the total moles. **Unitless**.|$X_B = \frac{n_B}{n_A + n_B}$; $X_A + X_B = 1$|
|**Molarity (M)**|Moles of solute per liter of **solution**. Unit: $\text{mol} \cdot \text{L}^{-1}$ (Molar).|$M = \frac{n_B}{V_{A+B} (\text{L})} = \frac{W_B}{M_B \times V_{A+B}}$|
|**Molality (m)**|Moles of solute per kilogram of **solvent**. Unit: $\text{mol} \cdot \text{kg}^{-1}$ (Molal).|$m = \frac{n_B}{W_A (\text{kg})} = \frac{W_B (\text{g})}{M_B \times W_A (\text{kg})}$|

---

### III. Colligative Properties (CPs)

Colligative Properties are defined as properties that depend **only on the number of solute particles** (or amount/concentration of solute) present in the solution, and are **independent of the nature** of the solute.

The four main CPs are:

#### 1. Relative Lowering of Vapor Pressure (RLVP)

- **Concept:** When a **non-volatile solute** is added to a volatile solvent, the vapor pressure of the resulting solution ($P$) decreases compared to the pure solvent ($P^\circ$). The non-volatile solute particles occupy the surface, inhibiting the solvent from vaporizing.
- **RLVP Definition:** The ratio of the reduction in vapor pressure ($P^\circ - P$) to the vapor pressure of the pure solvent ($P^\circ$).
- **Formula (Raoult's Law):** RLVP is directly proportional to the mole fraction of the solute ($X_B$). $$\frac{P^\circ - P}{P^\circ} = X_B = \frac{n_B}{n_A + n_B}$$

#### 2. Elevation in Boiling Point (EBP)

- **Boiling Point:** The temperature at which the vapor pressure of a liquid equals the atmospheric pressure. (Water boils at $100^\circ \text{C}$ only at 1 atmosphere pressure).
- **Concept:** Because adding a non-volatile solute lowers the vapor pressure of the solution, a higher temperature is required for the solution's vapor pressure to reach the atmospheric pressure. Thus, the boiling point is _elevated_ ($T_2 > T_1$).
- **Elevation in B.P. ($\Delta T_B$):** The change is calculated as the final boiling point minus the initial boiling point: $$\Delta T_B = T_2 - T_1$$.
- **Formula:** $\Delta T_B$ is directly proportional to the **molality ($m$)** of the solute. $$\Delta T_B = K_B \cdot m = K_B \frac{W_B}{M_B \times W_A (\text{kg})}$$
    - $K_B$ is the **Ebullioscopic Constant** (unit: $\text{K} \cdot \text{kg} \cdot \text{mol}^{-1}$).
- **Applications:** Adding salt to water increases its boiling point, cooking food faster; checking the purity of a solvent; molar mass determination.

#### 3. Depression in Freezing Point (DFP)

- **Concept:** Adding a solute interferes with the ability of solvent molecules to arrange into a solid lattice structure (freezing). This requires lowering the temperature further to induce freezing, thus the freezing point is _depressed_ ($T_1 > T_2$).
- **Depression in F.P. ($\Delta T_F$):** The change is calculated as the initial freezing point minus the final freezing point: $$\Delta T_F = T_1 - T_2$$.
- **Formula:** $\Delta T_F$ is directly proportional to the **molality ($m$)** of the solute. $$\Delta T_F = K_F \cdot m = K_F \frac{W_B}{M_B \times W_A (\text{kg})}$$
    - $K_F$ is the **Cryoscopic Constant** (or Depression Constant) (unit: $\text{K} \cdot \text{kg} \cdot \text{mol}^{-1}$).
- **Applications:** Used to melt ice faster (e.g., using salt on roads); creating anti-freezing solutions and coolants for cars to prevent liquids from solidifying at low temperatures.

#### 4. Osmotic Pressure (OP)

- **Osmosis:** The movement of **solvent molecules** through a **selectively permeable membrane (SPM)**:
    - From higher concentration of solvent (or lower concentration of solute).
    - To lower concentration of solvent (or higher concentration of solute).
- **Osmotic Pressure ($\Pi$):** The pressure that must be applied to the solution side (opposite direction) to **stop** the process of osmosis.
- **Formula (Van't Hoff Equation):** Osmotic pressure is proportional to Molarity ($C$) and absolute temperature ($T$). $$\Pi = C R T \text{ or } \Pi V = n R T$$
    - $C$ is **Molarity** (moles/Liters).
    - $R$ is the Gas Constant ($R \approx 0.083 \text{ L} \cdot \text{bar} \cdot \text{mol}^{-1} \cdot \text{K}^{-1}$).
    - $\Pi$ will be in bar if $R = 0.083$ is used and volume is in liters.
- **Reverse Osmosis (RO) and Water Purification:** The direction of osmosis can be reversed if a pressure ($P$) greater than the osmotic pressure ($\Pi$) is applied to the solution side ($P > \Pi$). This forces pure solvent (water) out of the solution, making it a method of water purification.

---

### IV. Solubility and Henry's Law

**Solubility** Solubility is the **maximum amount of solute** that can be dissolved in a given amount of solvent at a given temperature. Solubility is essentially equivalent to the maximum concentration achievable.

**Factors Affecting Solubility (General):**

1. **Nature of Solute and Solvent:** Solubility is dependent on the specific chemical identities of the solute and solvent (e.g., salt dissolves in water but not ethanol).
2. **Temperature:**
    - **Solids in Liquid:** Solubility generally **increases** with increasing temperature.
    - **Gases in Liquid:** Solubility **decreases** with increasing temperature (inversely proportional). (E.g., cold drinks are drunk cold to maintain gas, and aquatic life thrives in colder water because of higher dissolved oxygen).
3. **Pressure:**
    - **Solids in Liquid:** Pressure has no significant effect.
    - **Gases in Liquid:** Solubility **increases** with increasing pressure (directly proportional).

**Henry's Law** Henry's Law relates the solubility of a gas in a liquid to pressure.

- **Statement (Modern Version):** The partial pressure ($P$) of a gas in the vapor phase is proportional to the mole fraction ($X_B$) of the gas in the solution. $$P = K_H X_B$$
    - $K_H$ is the **Henry's Constant**. The unit of $K_H$ is the same as the unit of pressure (e.g., Pa, bar, mm Hg).
- **$K_H$ and Solubility:** $K_H$ is inversely proportional to solubility. A gas with a higher $K_H$ value is **less soluble**.
    - For example, at 293 K, Nitrogen ($\text{N}_2$) has a higher $K_H$ (76.48 kbar) than Oxygen ($\text{O}_2$) (34.86 kbar), meaning Oxygen is more soluble.
- **$K_H$ and Temperature:** Since solubility decreases with temperature, $K_H$ increases with increasing temperature.
- **Applications:**
    1. **Carbonated Soft Drinks:** High pressure is used during bottling to increase the solubility of $\text{CO}_2$.
    2. **Deep Sea Diving (Bends):** Divers use compressed air diluted with **Helium** to reduce the concentration of nitrogen. At high pressure underwater, nitrogen solubility in the blood increases drastically, which leads to "bends disease" upon ascent if nitrogen is not reduced.

---

### V. Raoult's Law, Ideal, and Non-Ideal Solutions

#### Dalton's Law of Partial Pressure

The total pressure ($P_{\text{total}}$) exerted over a solution phase in a container is the sum of the partial pressures of its components ($P_A$ and $P_B$): $$P_{\text{total}} = P_A + P_B$$

- **Condition:** This law strictly applies only if the components (A and B) are **non-reactive and non-interactive** (i.e., there is no attraction or repulsion between them).

#### Raoult's Law (for Volatile Liquids)

For a solution of volatile liquids, the partial vapor pressure of each component ($P_A$) in the solution is directly proportional to its mole fraction ($X_A$) in the solution. $$P_A = P_A^\circ X_A$$ $$P_B = P_B^\circ X_B$$

- $P_A^\circ$ and $P_B^\circ$ are the vapor pressures of the pure components.
- Combining with Dalton's Law, the total pressure is: $$P_{\text{total}} = P_A^\circ X_A + P_B^\circ X_B$$

#### Ideal and Non-Ideal Solutions

**Ideal Solutions** Solutions that **strictly follow Raoult's Law** across all concentrations and temperatures are termed Ideal Solutions.

|Property|Ideal Solution|
|:--|:--|
|**Raoult's Law**|$P_{\text{total}} = P_A + P_B$|
|**Molecular Interaction**|No attraction or repulsion between A-B components (hypothetically)|
|**Enthalpy Change ($\Delta H$)**|Zero ($\Delta H = 0$)|
|**Volume Change ($\Delta V$)**|Zero ($\Delta V = 0$)|
|**Examples**|Hexane + heptane, Benzene + toluene|

**Non-Ideal Solutions** Solutions that **do not follow Raoult's Law** ($P_{\text{total}} \ne P_A + P_B$) are Non-Ideal Solutions.

|Property|Non-Ideal (Positive Deviation)|Non-Ideal (Negative Deviation)|
|:--|:--|:--|
|**Raoult's Law**|$P_{\text{total}} > P_A + P_B$|$P_{\text{total}} < P_A + P_B$|
|**Molecular Interaction**|Repulsion (components push away, increasing pressure)|Attraction (components pull close, decreasing pressure)|
|**Enthalpy Change ($\Delta H$)**|Positive (Endothermic mixing)|Negative (Exothermic mixing)|
|**Volume Change ($\Delta V$)**|Positive (Volume expands upon mixing)|Negative (Volume contracts upon mixing)|
|**Examples**|Acetone + Benzene, Acetone + Ethanol|Phenol + aniline, Chloroform + acetone|

#### Azeotropic Mixtures

Azeotropes are mixtures of two liquids that **boil at a constant temperature** and distill over without any change in composition. They cannot be separated by simple distillation.

1. **Minimum Boiling Azeotrope:**
    - Boils at a temperature **lower** than either pure component.
    - Formed by Non-Ideal Solutions showing **Positive Deviation** (repulsion makes boiling easier).
    - Example: Ethanol-water.
2. **Maximum Boiling Azeotrope:**
    - Boils at a temperature **higher** than either pure component.
    - Formed by Non-Ideal Solutions showing **Negative Deviation** (attraction makes boiling difficult).
    - Example: $68%$ nitric acid and $32%$ water.

---

### VI. Vant Hoff Factor ($i$)

The Vant Hoff factor ($i$) is introduced to modify Colligative Property formulas when the solute is an **electrolyte** (dissociates or associates). Colligative properties depend solely on the _number_ of particles.

- **Formula:** $$i = \frac{\text{Number of particles after dissociation/association}}{\text{Number of particles before dissociation/association}}$$
    
- **Non-Electrolytes:** For non-electrolytes (like glucose or urea) that do not break apart, $i = 1$.
    
- **Strong Electrolytes (Complete Dissociation):** $i$ equals the total number of ions produced.
    
    - Example: $\text{NaCl} \rightarrow \text{Na}^+ + \text{Cl}^-$. $i = \frac{2}{1} = 2$.
    - Example: $\text{K}_2\text{SO}_4 \rightarrow 2\text{K}^+ + \text{SO}_4^{2-}$. $i = \frac{3}{1} = 3$.
- **Weak Electrolytes (Partial Dissociation):** If a weak electrolyte breaks into two ions (like $\text{CH}_3\text{COOH}$), $i$ is related to the degree of dissociation ($\alpha$) by: $$i = 1 + \alpha$$ The dissociation constant ($K_a$) is also related to $\alpha$ and the molar concentration ($C$) by the equilibrium expression: $$K_a = \frac{C \alpha^2}{1 - \alpha}$$
    

**Modified Colligative Property Formulas (for Electrolytes):** The calculated colligative property must be multiplied by $i$:

1. $\Delta T_F = i K_F m$
2. $\Delta T_B = i K_B m$
3. $\Pi = i C R T$ (or $\Pi V = i n R T$)