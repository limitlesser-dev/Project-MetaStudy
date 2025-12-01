The following detailed notes draw comprehensively from the provided transcript excerpts on the topic of Electrochemistry:

---

## Detailed Notes on Electrochemistry

### I. Introduction and Definition of Electrochemistry

Electrochemistry is the branch of chemistry that deals with the relationship between **chemical energy and electric energy** and their interconversion.

**Conversions:**

1. **Electric Energy $\rightarrow$ Chemical Energy:** Example: Charging a phone, where electric energy is converted into chemical energy stored in the battery.
    - This process is studied under **Electrolysis**.
2. **Chemical Energy $\rightarrow$ Electric Energy:** Example: A battery powering a device (like a phone or microphone) uses stored chemical energy to produce electric energy.
    - This process is studied under **Electrochemical Reactions**.

All batteries and cells operate based on these two fundamental principles. The chapter primarily focuses on the study of cells and batteries.

### II. Electrochemical Cells: Electrolytic vs. Electrochemical

| Feature               | Electrolytic Cell                                                      | Electrochemical Cell (Galvanic/Voltaic)                                |
| :-------------------- | :--------------------------------------------------------------------- | :--------------------------------------------------------------------- |
| **Energy Conversion** | Electric Energy $\rightarrow$ Chemical Energy                          | Chemical Energy $\rightarrow$ Electric Energy                          |
| **Process**           | Electrolysis (often causes chemical decomposition)                     | Redox Reaction (spontaneous chemical change produces current)          |
| **Compartments**      | One compartment (electrodes in the same vessel)                        | Two separate compartments (Half Cells)                                 |
| **Anode Sign**        | Positive (+)                                                           | Negative (-)                                                           |
| **Cathode Sign**      | Negative (-)                                                           | Positive (+)                                                           |
| **Electron Flow**     | Electrons leave Anode (Oxidation); Electrons enter Cathode (Reduction) | Electrons leave Anode (Oxidation); Electrons enter Cathode (Reduction) |
![[Pasted image 20251019213354.png]]
#### A. Universal Definitions for Electrodes

It is preferable to define electrodes based on the chemical process rather than their electrical sign, as the sign changes between the cell types.

- **Anode:** The electrode where **Oxidation** takes place (loss of electrons).
- **Cathode:** The electrode where **Reduction** takes place (gain of electrons).

#### B. Purpose of Two Compartments (Half Cells)

Electrochemical cells use two separate compartments (half cells) to ensure that the transferred electrons are forced to travel through an external wire, allowing the generated electricity to be utilized. Each compartment consists of an electrode and an electrolyte solution.

#### C. Role of the Salt Bridge

The Salt Bridge connects the two half cells internally, often consisting of a U-shaped tube filled with a gel containing an inert salt like $KNO_3$ or KCl.

- **Function 1:** Completes the electrical circuit.
- **Function 2:** Maintains **electrical neutrality** in both half cells, preventing charge buildup that would otherwise affect the potential.

#### D. Daniel Cell (Example of Electrochemical Cell)

The Daniel Cell is a relatively easier version of the electrochemical cell, consisting of a Zinc rod in $ZnSO_4$ solution and a Copper strip in $CuSO_4$ solution.

- **Anode Half Reaction (Oxidation):** $Zn \rightarrow Zn^{2+} + 2e^-$ (Zinc is more reactive and oxidizes). The Anode is negative.
- **Cathode Half Reaction (Reduction):** $Cu^{2+} + 2e^- \rightarrow Cu$ (Copper ions gain electrons). The Cathode is positive.
- **Overall Reaction:** $Zn + Cu^{2+} \rightarrow Zn^{2+} + Cu$.
- **Standard Potential ($E^0$ Cell):** 1.1 Volts (under standard conditions).
- **Cell Representation:** $Zn | Zn^{2+} || Cu^{2+} | Cu$.

### III. Electrode Potential and Nernst Equation

#### A. Electrode Potential

- **Electrode Potential (E):** The tendency of a metal to lose or gain electrons when placed in contact with its own electrolyte solution.
- **Standard Electrode Potential ($E^0$):** The electrode potential measured under standard conditions:
    - Temperature: 298 K.
    - Pressure: 1 ATM (if applicable).
    - Concentration: 1 Molar.

#### B. Standard Hydrogen Electrode (SHE)

Measuring the potential of a single half-cell is impossible. Therefore, the Standard Hydrogen Electrode (SHE) is used as a reference, and its **Standard Potential is assumed to be zero**.

#### C. Calculating Standard Cell Potential ($E^0$ Cell)

To calculate the total potential of a cell ($E^0$ cell), the potentials of the two half cells are combined. Chemistry convention uses **Standard Reduction Potentials (SRP)**.

- **Formula (using SRP values):** $$E^0 \text{cell} = E^0 \text{Cathode (SRP)} - E^0 \text{Anode (SRP)}$$.
- **Identifying Electrodes:** The element with the **higher (more positive) SRP** acts as the **Cathode** (it is reduced), and the one with the lower SRP acts as the Anode (it is oxidized).
- **Conversion:** Standard Oxidation Potential = - (Standard Reduction Potential).

#### D. Nernst Equation (E Cell)

The Nernst Equation is used to calculate the cell potential ($E_{cell}$) when conditions are not standard (i.e., concentration is not 1M or temperature is not 298 K).

- **General Equation (for $T \neq 298 K$):** $$E_{cell} = E^0 \text{cell} - \frac{2.303 RT}{nF} \log \left( \frac{[\text{Products ions}]}{[\text{Reactants ions}]} \right)$$
    - $R$ is the Gas Constant (8.314 J/K/mol).
    - $T$ is the Temperature in Kelvin.
    - $n$ is the moles of electrons transferred.
    - $F$ is the Faraday constant (96,500 C/mol).
- **Simplified Equation (for $T = 298 K$):** $$E_{cell} = E^0 \text{cell} - \frac{0.059}{n} \log \left( \frac{[\text{Products ions}]}{[\text{Reactants ions}]} \right)$$
    - **Note:** Only the concentrations of **ions** (aqueous species) are included in the log term; solids are excluded.

#### E. Relationships with Gibbs Energy and Equilibrium Constant

1. **Standard Gibbs Free Energy ($\Delta G^0$)**: $$\Delta G^0 = - n F E^0 \text{cell}$$ (The negative sign implies a spontaneous process).
    
2. **Equilibrium Constant ($K_c$)**: At equilibrium, $E_{cell} = 0$. $$\Delta G^0 = - 2.303 R T \log K_c$$
    
    - If $T = 298 K$: $$E^0 \text{cell} = \frac{0.059}{n} \log K_c$$.

### IV. Conductance, Conductivity, and Molar Conductivity

#### A. Basic Definitions

|Term|Symbol|Relation|SI Unit (Common Chemistry Unit)|
|:--|:--|:--|:--|
|**Resistance**|R|$R = \rho (L/A)$|Ohm ($\Omega$)|
|**Resistivity**|$\rho$|$\rho = R (A/L)$|$\Omega \cdot m$ ($\Omega \cdot cm$)|
|**Conductance**|G|$G = 1/R$|Siemens (S) or Moh ($\mho$)|
|**Conductivity**|$\kappa$ (Kappa)|$\kappa = 1/\rho$|$S \cdot m^{-1}$ ($S \cdot cm^{-1}$)|
|**Cell Constant**|$G^*$|$G^* = L/A$|$m^{-1}$ ($cm^{-1}$)|
|**Relation:**|$\kappa = G \cdot G^*$|||

#### B. Molar Conductivity ($\Lambda_m$)

Molar conductivity is defined as the conductivity per unit concentration (molarity).

- **Formula:** $$\Lambda_m = \frac{\kappa \times 1000}{C}$$
    - The factor 1000 is included to ensure unit consistency when $\kappa$ is in $S \cdot cm^{-1}$ and concentration (C) is in $mol/L$.
- **Unit:** Siemens centimeter squared mole inverse ($S \cdot cm^2 \cdot mol^{-1}$).

#### C. Variation with Concentration and Dilution

1. **Conductivity ($\kappa$):** Increases with concentration, as there are more ions available to carry the charge.
2. **Molar Conductivity ($\Lambda_m$):** Decreases with increasing concentration, as it is inversely proportional to concentration.
3. **Dilution:** On dilution (decreasing concentration), molar conductivity **increases**.

#### D. Molar Conductivity at Infinite Dilution ($\Lambda^0_m$)

- When infinite dilution is performed (concentration approaches zero), the molar conductivity reaches its maximum possible value, called **Molar Conductivity at Infinite Dilution** ($\Lambda^0_m$).
- **Degree of Dissociation ($\alpha$):** This is defined by the ratio: $$\alpha = \frac{\Lambda_m}{\Lambda^0_m}$$.
- **Dissociation Constant ($K_a$):** Related by $K_a = \frac{C \alpha^2}{1 - \alpha}$ (from 11th-grade equilibrium).

#### E. Kohlrausch's Law (of Independent Migration of Ions)

Kohlrausch's Law states that the molar conductivity at infinite dilution ($\Lambda^0_m$) is the sum of the limiting molar conductivities ($\lambda^0$) of its individual ions.

- **Formula:** $$\Lambda^0_m (\text{Salt}) = \nu_+ \lambda^0_{+} + \nu_- \lambda^0_{-}$$ (Where $\nu$ is the stoichiometric coefficient).
- Example: For $CaCl_2$, $\Lambda^0_m = \lambda^0_{Ca^{2+}} + 2 \lambda^0_{Cl^{-}}$.
- This law is used to find the molar conductivity at infinite dilution for weak electrolytes using the values of strong electrolytes.

### V. Types of Electrochemical Cells (Primary and Secondary)

#### A. Primary Cells (Non-Rechargeable)

These cells use an irreversible chemical reaction and are for single use; they cannot be easily recharged.

1. **Dry Cell (Leclanche Cell):** Used in remotes, clocks, and toys.
    - Anode: Zinc undergoes oxidation ($Zn \rightarrow Zn^{2+}$).
    - Cathode: Manganese (Mn) undergoes reduction (Mn +4 $\rightarrow$ +2).
2. **Mercury Cell (Button Cell):** Used in wristwatches, calculators, and hearing aids.
    - Anode: Amalgamated Zinc ($Zn(Hg)$).
    - **Special Feature:** Provides a **constant potential** because **no ions** are involved in the overall reaction, meaning the Nernst concentration term remains fixed.

#### B. Secondary Cells (Rechargeable)

These cells use a reversible chemical reaction and can be recharged after being discharged. The reactions usually provided are for **discharging**; charging reactions are the reverse.

1. **Lead Storage Battery:** Used in cars and inverters.
    - A key feature is that **both the Anode and Cathode involve Lead**.
    - Anode: Lead (0 $\rightarrow$ +2).
    - Cathode: Lead (+4 $\rightarrow$ +2).
    - Electrolyte: Sulfuric Acid ($H_2SO_4$) (around 38% concentration).
2. **Nickel Cadmium Cell:** Has a long life and was used frequently in laptops.
    - Anode: Cadmium (0 $\rightarrow$ +2) (Oxidation).
    - Cathode: Nickel (+3 $\rightarrow$ +2) (Reduction).

#### C. Fuel Cells (e.g., $H_2/O_2$ Cell)

Fuel cells convert the energy produced by the **combustion of a fuel** directly into electrical energy.

- **Example Use:** Apollo Program (space missions).
- **Advantages:** High efficiency, environmental friendliness (e.g., $H_2$ combustion only produces water).
- **Overall Reaction:** $2H_2 + O_2 \rightarrow 2H_2O$.
- Anode: Hydrogen undergoes oxidation.
- Cathode: Oxygen undergoes reduction.

### VI. Faraday's Laws of Electrolysis

Faraday's Laws apply specifically to **Electrolytic Cells** (Electrolysis).

#### A. Faraday's First Law

The mass (W) of a substance deposited or liberated at an electrode is directly proportional to the quantity of charge (Q) passed through the electrolyte.

- **Relationship:** $W \propto Q$, and since $Q = I \times T$, $W \propto I \times T$.
- **Formula:** $$W = Z \cdot I \cdot T$$.
    - $W$: Mass deposited (in grams).
    - $I$: Current (Amperes).
    - $T$: Time (Seconds).
    - $Z$: Electrochemical Equivalent, given by: $$Z = \frac{\text{Molar Mass}}{\text{Valency} \times 96500}$$.
    - Note: To get the final mass in grams, the calculation must be divided by the Faraday constant (96,500 C).

#### B. Faraday's Second Law

When the same quantity of electricity is passed through different electrolytic cells connected in series, the amounts of different substances liberated are proportional to their equivalent weights ($Z$).

- **Relationship:** $$\frac{W_1}{W_2} = \frac{Z_1}{Z_2}$$.