The sources provide an extensive analysis of Ohm's Law and Resistance, situating them as foundational concepts within the study of **Current Electricity** (Chapter 3). This branch of physics deals with **charges in motion** (Electro-dynamics), contrasting with the earlier study of Electrostatics, where charges were considered to be at rest.

Current Electricity seeks to establish the basic laws governing the **steady flow of electric current**.

---

## ⚡ Ohm's Law: The Fundamental Relationship

Ohm's Law, discovered by G.S. Ohm in 1828, is a basic law concerning the flow of electric currents.

### Definition and Formula

Ohm's Law states that the current ($I$) flowing through a conductor is **directly proportional to the potential difference** ($V$) applied across its ends.

The mathematical representation is: $$\mathbf{V \propto I \quad \text{or} \quad V = IR}$$

### Necessary Conditions

The proportionality between $V$ and $I$ only holds if certain physical conditions of the conductor remain constant. These constant conditions typically include:

1. 🌡️ **Constant Temperature**.
2. 📏 **Constant Dimensions**, such as the length ($l$) and the area of cross-section ($A$).

The law asserts that the plot of current ($I$) versus voltage ($V$) is a **straight line**.

### Derivation from Microscopic Principles

The sources demonstrate that Ohm's Law can be derived from the characteristics of electron drift, linking the macroscopic formula ($V=IR$) to microscopic properties.

The derivation involves relating the current ($I$) to the electric field ($E$) and the properties of the material (electron density $n$, mass $m$, charge $e$, and relaxation time $\tau$). By replacing the electric field ($E$) with voltage ($V$) using the relationship $E = V/L$ (Potential Gradient), the equation becomes: $$V = \left( \frac{m l}{e^2 n A \tau} \right) I$$

For constant temperature (which keeps the relaxation time, $\tau$, constant) and fixed dimensions ($l, A$), the entire bracketed term is constant, thus proving $\mathbf{V \propto I}$.

---

## 🚧 Resistance ($R$): The Constant of Opposition

Resistance ($R$) is the constant of proportionality in Ohm's Law.

### Conceptual Understanding and Unit

Resistance is defined as a **property of a substance** that opposes or **resists the flow of electric current**. It is conceptually compared to **friction** in a circuit.

Microscopically, resistance arises because, during transit, charge carriers collide with the ions and atoms in the conductor, dissipating the energy gained from the electric field as heat. This process is known as "ohmic loss".

- **SI Unit:** The unit of resistance is the **Ohm**, denoted by the symbol $\mathbf{\Omega}$.
- **Definition of 1 Ohm:** A conductor has a resistance of 1 Ohm when 1 Volt of potential difference across its ends causes 1 Ampere of current to flow. Resistance can also be expressed as Volt per Ampere.

### Independence and Dependence

Although calculated using $R=V/I$, resistance ($R$) is **purely independent** of the current ($I$) or voltage ($V$) applied across it because it acts as a constant in the Ohm's Law equation.

Instead, resistance depends on the material and the **dimensions of the conductor**.

Resistance is:

1. **Directly proportional to the length ($l$)** of the conductor ($\mathbf{R \propto l}$).
2. **Inversely proportional to the area of cross-section ($A$)** ($\mathbf{R \propto 1/A}$).
3. Dependent on the **Nature of Material** and **Temperature**.

Combining the dimensional factors leads to the formula: $$\mathbf{R = \rho \frac{l}{A}}$$

---

## 🔍 Resistivity ($\rho$) and Conductivity ($\sigma$)

### Resistivity ($\rho$)

Resistivity (or specific resistance, $\rho$) is the constant in the resistance formula $R = \rho l/A$.

- Resistivity is an **intrinsic property of the material**; it does not depend on the conductor's dimensions.
- It is determined by the nature of the material and the temperature.
- **SI Unit:** $\mathbf{\Omega \text{ m}}$ (ohm meter).

Materials are broadly classified based on their resistivity values:

|Material Type|Resistivity ($\rho$) Range (in $\Omega$ m)|
|:-:|:-:|
|**Conductors (Metals)**|Very Low: $10^{-8}$ to $10^{-6}$|
|**Semiconductors**|Intermediate: Roughly in the range of $10^{-4}$ to $10^6$|
|**Insulators**|Very High: $10^8$ or greater (up to $10^{24}$ times that of metals)|

Microscopically, resistivity is related to mass ($m$), electron density ($n$), elementary charge ($e$), and relaxation time ($\tau$) by the formula: $$\mathbf{\rho = \frac{m}{n e^2 \tau}}$$

### Temperature Dependence of Resistivity

For metallic conductors, resistivity ($\rho$) increases as temperature ($T$) increases. This happens because higher temperature increases the average speed of electrons, leading to more frequent collisions, thereby decreasing the average time between collisions ($\tau$).

The temperature dependence for metallic conductors over a limited temperature range is given approximately by: $$\mathbf{\rho_T = \rho_0 [1 + \alpha (T - T_0)]}$$

### Conductivity ($\sigma$)

Conductivity ($\sigma$) is defined as the **reciprocal of resistivity** ($\mathbf{\sigma = 1/\rho}$). Conductors have low resistivity and high conductivity. The SI unit of conductivity is $\mathbf{\Omega^{-1} \text{ m}^{-1}}$.

---

## 📉 Limitations of Ohm's Law

Ohm's Law is widely applicable but is not a universal law of nature. Substances that follow Ohm's Law (where the V-I graph is a straight line) are called **Ohmic Conductors** (e.g., metals). Devices that do not follow the law are **Non-Ohmic Conductors** (e.g., semiconductors and PN junctions).

The sources describe three broad types of deviations from Ohm's Law:

1. **Non-Linearity:** The voltage ($V$) is no longer proportional to the current ($I$), leading to a curved V-I graph.
2. **Directional Dependence:** The relationship depends on the sign of $V$. Reversing the voltage does not produce a current of the same magnitude in the opposite direction (e.g., in a diode).
3. **Non-Uniqueness:** There may be more than one value of $V$ for a single value of $I$, as seen in materials like GaAs.