This document provides detailed notes on the key concepts, definitions, formulas, and examples covered in the electrochemistry materials provided.

---

## Detailed Notes on Electrochemistry

### I. Introduction and Core Definitions

**Electrochemistry** is the branch of chemistry that deals with the relationship between chemical energy and electric energy and their mutual interconversion.

1. **Energy Conversions:**
    
    - **Electric Energy $\to$ Chemical Energy (Charging):** Occurs when electric energy is converted into chemical energy (e.g., charging a battery or phone). This process is known as **Electrolysis**.
    - **Chemical Energy $\to$ Electric Energy (Discharging):** Occurs when chemical energy is used to produce electric energy (e.g., a phone using its battery or a microphone battery operating). This relies on **Electrochemical reactions**.
2. **Electrolytic Cell:**
    
    - **Definition:** An apparatus used to carry out **electrolysis**. It converts electrical energy into chemical energy. The chemical reaction is non-spontaneous and requires an external source of voltage.
    - **Electrodes in Electrolytic Cell:** The electrode connected to the positive terminal is the **Anode** (where oxidation occurs) and the electrode connected to the negative terminal is the **Cathode** (where reduction occurs). Both electrodes are typically dipped in the same solution.
3. **Electrochemical Cell (Galvanic or Voltaic Cell):**
    
    - **Definition:** A device that converts the chemical energy released during a **spontaneous redox reaction** into electrical energy.
    - **Electrodes in Electrochemical Cell:**
        - **Anode:** Site of **oxidation** (always). In a galvanic cell, the anode is the **negative** terminal.
        - **Cathode:** Site of **reduction** (always). In a galvanic cell, the cathode is the **positive** terminal.
    - **Construction:** Typically consists of two separate compartments, called **half-cells** (an oxidation half-cell and a reduction half-cell), connected externally by a wire and internally by a **Salt Bridge**.
4. **Salt Bridge:**
    
    - **Purpose:** Completes the electrical circuit and maintains electrical neutrality in both half-cells.
    - **Structure:** Often an inverted U-shaped glass tube containing an inert electrolyte (e.g., $\text{KCl}$, $\text{KNO}_3$) in a semi-solid paste like agar-agar.
5. **Daniell Cell (Example of a Galvanic Cell):**
    
    - **Setup:** A zinc rod dipped in $\text{ZnSO}_4$ solution (Anode) and a copper strip dipped in $\text{CuSO}_4$ solution (Cathode).
    - **Reactions:**
        - Anode (Oxidation): $\text{Zn}(s) \to \text{Zn}^{2+}(aq) + 2e^-$.
        - Cathode (Reduction): $\text{Cu}^{2+}(aq) + 2e^- \to \text{Cu}(s)$.
        - Overall Redox Reaction: $\text{Zn}(s) + \text{Cu}^{2+}(aq) \to \text{Zn}^{2+}(aq) + \text{Cu}(s)$.
    - **Flow:** Electrons flow from the Zinc electrode (Anode, negative) to the Copper electrode (Cathode, positive).

### II. Cell Potential and Nernst Equation

1. **Electrode Potential ($E$):** The potential difference established between a metal electrode and its electrolyte solution.
2. **Standard Electrode Potential ($E^\circ$):** The electrode potential measured under **standard conditions**.
    - Standard Conditions: Temperature $298 \text{ K}$ (or $25^\circ \text{C}$), Pressure $1 \text{ atm}/1 \text{ bar}$ (for gases), and Concentration $1 \text{ M}$ ($1 \text{ mol L}^{-1}$).
    - IUPAC Convention: Standard electrode potentials are reported as **standard reduction potentials**.
3. **Standard Hydrogen Electrode (SHE):**
    - **Reference:** Used to measure the potential of individual half-cells, as individual half-cell potentials cannot be measured directly.
    - **Assigned Value:** The standard potential of SHE is arbitrarily assumed to be **zero** ($E^\circ = 0$) at all temperatures.
4. **Cell Potential ($E_{\text{cell}}$):** The potential difference between the two electrodes of a galvanic cell, measured in volts. It is also called the **electromotive force (emf)** when no current is drawn.
    - **Formula:** $E_{\text{cell}} = E_{\text{cathode}} - E_{\text{anode}}$ (where both potentials are reduction potentials).
    - **Standard Cell Potential ($E^\circ_{\text{cell}}$):** $E^\circ_{\text{cell}} = E^\circ_{\text{cathode}} - E^\circ_{\text{anode}}$.
5. **Cell Representation:** Anode is conventionally placed on the left, and cathode on the right. A vertical line ($|$) separates the metal electrode from the electrolyte, and a double vertical line ($||$) represents the salt bridge.
    - Example: $\text{Zn}(s)|\text{Zn}^{2+}(aq)||\text{Cu}^{2+}(aq)|\text{Cu}(s)$.
6. **Nernst Equation:**
    - **Function:** Relates the cell potential ($E_{\text{cell}}$) to $E^\circ_{\text{cell}}$ and the concentration of species involved, especially when concentrations are not unity.
    - **General Form (at 298 K):** $$E_{\text{cell}} = E^\circ_{\text{cell}} - \frac{0.059}{n} \log Q$$ where $Q$ is the reaction quotient, defined as $Q = \frac{[\text{Products}]}{[\text{Reactants}]}$ (concentrations of ions only, excluding solids/liquids).
    - **Terms:** $n$ is the number of moles of electrons transferred; $0.059$ results from simplifying $\frac{2.303 RT}{F}$ at $T = 298 \text{ K}$.
7. **Thermodynamic Relations:**
    - **Gibbs Free Energy ($\Delta_r G$):** The reversible work done by a galvanic cell is equal to the decrease in its Gibbs energy.
        - $\Delta_r G = -nFE_{\text{cell}}$.
        - Standard Gibbs Energy: $\Delta_r G^\circ = -nFE^\circ_{\text{cell}}$.
    - **Equilibrium Constant ($K_c$):** At equilibrium, $E_{\text{cell}}$ is zero.
        - Relation: $E^\circ_{\text{cell}} = \frac{2.303 RT}{nF} \log K_c$.
        - Simplified (at 298 K): $E^\circ_{\text{cell}} = \frac{0.059}{n} \log K_c$.
        - $\Delta_r G^\circ = -RT \ln K_c$.

### III. Conductance and Molar Conductivity

1. **Resistance ($R$):** The obstruction to the flow of electric current.
    - Formula: $R = \rho (l/A)$. Unit: Ohm ($\Omega$).
2. **Resistivity ($\rho$):** Specific resistance. Resistance of a substance when it is $1 \text{ m}$ long and has an area of cross section of $1 \text{ m}^2$. Unit: $\Omega \text{ m}$ or $\Omega \text{ cm}$.
3. **Conductance ($G$):** The inverse of resistance ($G = 1/R$). Represents the ease of charge flow. Unit: Siemens ($\text{S}$) (equal to $\Omega^{-1}$ or $\text{mho}$).
4. **Conductivity ($\kappa$ or specific conductance):** The inverse of resistivity ($\kappa = 1/\rho$).
    - Unit: $\text{S m}^{-1}$ or commonly $\text{S cm}^{-1}$ in chemistry.
    - **Variation with Concentration:** Conductivity always **decreases** with decrease in concentration (dilution) for both weak and strong electrolytes because the number of ions per unit volume decreases.
    - **Factors Affecting Electrolytic Conductivity:** Nature of electrolyte, size and solvation of ions, nature and viscosity of solvent, concentration of electrolyte, and temperature (increases with temperature).
5. **Cell Constant ($G^\ast$):**
    - Definition: The ratio of the distance between electrodes ($l$) and the area of cross-section ($A$), $G^\ast = l/A$.
    - Relation to Conductivity: Conductivity ($\kappa$) equals Conductance ($G$) multiplied by Cell Constant ($G^\ast$): $\kappa = G \cdot G^\ast$.
    - Unit: $\text{m}^{-1}$ or $\text{cm}^{-1}$.
6. **Molar Conductivity ($\Lambda_m$):** The conductance of the volume of solution containing one mole of electrolyte.
    - Formula (Using $\kappa$ in $\text{S cm}^{-1}$ and concentration $c$ in $\text{mol L}^{-1}$): $$\Lambda_m = \frac{\kappa \times 1000}{c}$$ (The 1000 factor converts liters to $\text{cm}^3$ to match the units).
    - Unit: $\text{S cm}^2 \text{mol}^{-1}$ or $\text{S m}^2 \text{mol}^{-1}$.
    - **Variation with Concentration:** Molar conductivity **increases** with decrease in concentration (dilution) because the total volume containing one mole of electrolyte increases, compensating for the decrease in conductivity ($\kappa$).
7. **Limiting Molar Conductivity ($\Lambda_m^\circ$):**
    - Definition: The molar conductivity at zero concentration or **infinite dilution**. This is the maximum value $\Lambda_m$ can achieve.
    - **Strong Electrolytes:** $\Lambda_m$ increases slowly and linearly with dilution and $\Lambda_m^\circ$ can be obtained by extrapolating the plot of $\Lambda_m$ versus $c^{1/2}$ (following the Debye-Hückel-Onsager equation: $\Lambda_m = \Lambda_m^\circ - A c^{1/2}$).
    - **Weak Electrolytes:** $\Lambda_m$ increases steeply near infinite dilution because the degree of dissociation ($\alpha$) increases significantly. $\Lambda_m^\circ$ cannot be obtained by extrapolation.
8. **Degree of Dissociation ($\alpha$):**
    - Formula: $\alpha = \frac{\Lambda_m}{\Lambda_m^\circ}$.
    - Dissociation Constant ($K$): For a weak electrolyte (like $\text{HAc}$), $K = \frac{c \alpha^2}{1 - \alpha}$.
9. **Kohlrausch's Law (Law of Independent Migration of Ions):**
    - **Principle:** Limiting molar conductivity ($\Lambda_m^\circ$) of an electrolyte is the sum of the individual contributions of the limiting molar ionic conductivities of the cation ($\lambda^\circ_+$) and the anion ($\lambda^\circ_-$).
    - **Formula:** $\Lambda_m^\circ = n_+ \lambda^\circ_+ + n_- \lambda^\circ_-$.
    - **Application:** Used to calculate $\Lambda_m^\circ$ for weak electrolytes, often by using conductivity values of strong electrolytes (e.g., finding $\Lambda_m^\circ(\text{HAc})$ using $\Lambda_m^\circ(\text{HCl})$, $\Lambda_m^\circ(\text{NaAc})$, and $\Lambda_m^\circ(\text{NaCl})$).

### IV. Batteries, Fuel Cells, and Corrosion

#### A. Primary Batteries (Non-Rechargeable)

The reaction occurs only once (irreversible chemical change), and the battery cannot be reused after it dies.

1. **Dry Cell (Leclanche Cell):** Used in transistors and clocks.
    - **Anode:** Zinc container ($\text{Zn}(s) \to \text{Zn}^{2+} + 2e^-$).
    - **Cathode:** Carbon ($\text{graphite}$) rod surrounded by powdered $\text{MnO}_2$ and carbon. $\text{Mn}$ is reduced from $+4$ to $+3$ oxidation state.
2. **Mercury Cell (Button Cell):** Suitable for low-current devices like watches and hearing aids.
    - **Anode:** Zinc-mercury amalgam ($\text{Zn}(\text{Hg})$).
    - **Cathode:** Paste of $\text{HgO}$ and carbon.
    - **Key Feature:** Provides **constant potential** throughout its life because the overall reaction ($\text{Zn}(\text{Hg}) + \text{HgO}(s) \to \text{ZnO}(s) + \text{Hg}(l)$) does not involve any ions in the solution whose concentration changes.

#### B. Secondary Batteries (Rechargeable)

These can be recharged by passing current in the opposite direction (reversible chemical reaction).

1. **Lead Storage Battery:** Commonly used in automobiles and invertors.
    
    - **Electrolyte:** 38% aqueous solution of sulfuric acid ($\text{H}_2\text{SO}_4$).
    - **Discharging Reactions (Use):**
        - Anode (Oxidation): $\text{Pb}(s) + \text{SO}_4^{2-}(aq) \to \text{PbSO}_4(s) + 2e^-$.
        - Cathode (Reduction): $\text{PbO}_2(s) + \text{SO}_4^{2-}(aq) + 4\text{H}^+(aq) + 2e^- \to \text{PbSO}_4(s) + 2\text{H}_2\text{O}(l)$.
        - $\text{PbSO}_4$ is deposited on both electrodes, and $\text{H}_2\text{SO}_4$ is consumed.
    - **Charging:** The reaction is reversed when electricity is passed, converting $\text{PbSO}_4$ back into $\text{Pb}$ and $\text{PbO}_2$.
2. **Nickel-Cadmium Cell:** Has a longer life than the lead storage cell but is more expensive.
    

#### C. Fuel Cells

Galvanic cells that convert the energy from the combustion of fuels (like $\text{H}_2$, $\text{CH}_4$) directly into electrical energy. They are highly efficient (around 70%) and pollution-free.

1. **H$_2$-O$_2$ Fuel Cell:** Used in the Apollo space program.
    - **Overall Reaction:** $2\text{H}_2(g) + \text{O}_2(g) \to 2\text{H}_2\text{O}(l)$.
    - **Electrolyte:** Concentrated aqueous sodium hydroxide ($\text{NaOH}$) or potassium hydroxide ($\text{KOH}$) solution.
    - **Anode (Oxidation):** $2\text{H}_2(g) + 4\text{OH}^-(aq) \to 4\text{H}_2\text{O}(l) + 4e^-$.
    - **Cathode (Reduction):** $\text{O}_2(g) + 2\text{H}_2\text{O}(l) + 4e^- \to 4\text{OH}^-(aq)$.

#### D. Corrosion

The slow destruction of metal upon exposure to air or chemicals. It is fundamentally an **electrochemical phenomenon**.

1. **Rusting of Iron (Electrochemical Mechanism):** Iron rust ($\text{Fe}_2\text{O}_3 \cdot x\text{H}_2\text{O}$) is hydrated ferric oxide.
    - Anodic Spot (Oxidation): $\text{Fe}(s) \to \text{Fe}^{2+}(aq) + 2e^-$.
    - Cathodic Spot (Reduction): $\text{O}_2(g) + 4\text{H}^+(aq) + 4e^- \to 2\text{H}_2\text{O}(l)$ (Oxygen is reduced in the presence of $\text{H}^+$ ions).
    - The $\text{Fe}^{2+}$ ions are further oxidized by atmospheric oxygen to $\text{Fe}^{3+}$, forming rust.

### V. Faraday's Laws of Electrolysis (Quantitative Aspects)

Faraday gave two laws describing the quantitative relationship between electricity passed and the chemical change during **electrolysis**.

1. **Faraday's First Law:**
    
    - **Statement:** The mass ($W$) of a substance deposited or liberated at any electrode is directly proportional to the quantity of electricity (charge, $Q$) passed through the electrolyte.
    - **Formulas:** $W \propto Q$ or $W = ZQ$. Since $Q = I \times t$ (current $\times$ time), $W = ZIT$.
    - **Faraday Constant ($F$):** The charge on one mole of electrons, $\approx 96,500 \text{ C mol}^{-1}$.
    - **Electrochemical Equivalent ($Z$):** If $1 \text{ ampere}$ of current is provided for $1 \text{ second}$, $W = Z$. $Z$ can be calculated using the molar mass ($M$) and valency ($n$): $Z = \frac{M}{n \cdot F}$ (where $F$ is the Faraday constant).
2. **Faraday's Second Law:**
    
    - **Statement:** The amounts of different substances deposited or liberated by the **same quantity of electricity** passing through different electrolytic solutions are proportional to their **chemical equivalent weights** ($E$).
    - **Formula:** $W_1 / W_2 = E_1 / E_2$.
	    - **Equivalent Weight ($E$):** Defined as the (Atomic Mass of Metal / Number of electrons required to reduce the cation).