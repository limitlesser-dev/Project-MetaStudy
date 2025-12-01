The following are detailed notes based on the provided transcript excerpts covering the chapter "Electrostatic Potential & Capacitance."

---

## I. Introduction and Course Context

- This video is a "Super One Shot" covering the second chapter of physics, **Electrostatic Potential & Capacitance**.
- The entire one-shot is approximately 2 hours 10 minutes to 2 hours 20 minutes long.
- Every derivation in the chapter will be written out by hand.
- Questions and answers are included at the end of the one-shot. Viewers focused only on questions can skip the initial explanation.
- Students should skip parts they already know (smart work).
- Questions include subjective questions and objective (MCQ) questions, some taken from the "Winner Series" book.
- Information regarding the **Batch 2.0** paid course is provided, noting that orientation classes begin on the 12th, and a 40% discount is available.
- Chapters 1 and 2 fall under **Electrostatics**, meaning the charge being studied is at **rest**. Later chapters (3 and 4) will cover Electro-dynamics, where charge is in motion.
- The chapter has two significantly different parts: **Electrostatic Potential** and **Capacitance**, which could potentially be taught as separate chapters.

---

## II. Electrostatic Potential and Potential Difference

The concepts of Electric Potential and Potential Difference are introduced as foundational elements of the chapter.

### A. Potential Difference (PD)

- **Definition:** The work done ($W$) in moving a positive test charge ($q_{0}$) from one given point (A) to another given point (B) in the presence of an external electric field (created by charge $Q$).
- This work is done against the electrostatic force (repulsion, if $Q$ and $q_0$ are both positive).
- **Formula:** Potential Difference $= \frac{\text{Work Done}}{\text{Charge moved}} = W/q$.

### B. Electric Potential (V)

- **Definition:** The work done ($W$) in moving a charge ($q_{0}$) from **infinite** (an unknown or very distant point) to a specific, known point.
- **Formula:** Electric Potential $= \frac{\text{Work Done}}{\text{Charge moved}} = W/q$.
- **Difference:** The key difference lies in the starting point: PD is between one _given_ point and another; Electric Potential is from _infinite_ to a point.
- **Practical Note:** While Potential Difference is what is typically measured in daily life (e.g., by a voltmeter between two points), **Electric Potential** is the first step and the primary focus of study in this chapter.

### C. Common Properties

- **Symbol:** $V$.
- **SI Unit:** **Joule per Coulomb (J/C)**, which is also called the **Volt (V)**. The Volt unit is named in honor of Alessandro Volta.
- **Definition of 1 Volt:** 1 Joule of work must be done to move 1 Coulomb of charge.
- **Nature:** Both Electric Potential and Potential Difference are **Scalar Quantities**.

---

## III. Electric Potential Calculations

### A. Electric Potential Due to a Point Charge

- **Goal:** Calculate the electric potential ($V$) produced by a fixed charge $Q$ at a distance $r$.
- **Methodology:** Bring a test charge $q_{0}$ from infinite distance to the point $r$.
- The work done ($W$) is calculated by integrating the small work done ($dW$) against the electrostatic force.
- $dW = F \cdot dx \cos(180^\circ) = -F dx$.
- $dW = - \frac{k Q q_{0}}{x^2} dx$ (where $x$ is the variable distance).
- Integrating from $\infty$ to $r$, and noting that $1/\infty$ is zero, the total work done is $W = \frac{k Q q_{0}}{r}$.
- Since $V = W/q_{0}$, the formula for Electric Potential due to a point charge is: $$V = \frac{k Q}{r} \quad \text{or} \quad V = \frac{1}{4\pi\epsilon_0} \frac{Q}{r}$$.
- **Note:** This potential formula is inversely proportional to distance ($1/r$), unlike force and electric field, which are proportional to $1/r^2$.

### B. Electric Potential Due to an Electric Dipole

Since potential is a scalar quantity, calculating it for a dipole is simpler than calculating the electric field.

#### 1. Axial Point

- The total potential is the scalar sum of the potential due to the positive charge ($+q$) and the negative charge ($-q$).
- $V_{axial} = V_{+q} + V_{-q} = \frac{k q}{r-a} + \frac{-k q}{r+a}$.
- **General Formula:** $$V_{axial} = \frac{-k p}{r^2 - a^2}$$ where $p = q \cdot 2a$ (dipole moment).
- **For a Short Dipole ($r \gg a$):** The $a^2$ term in the denominator is ignored. $$V_{axial} = \frac{-k p}{r^2}$$.

#### 2. Equatorial Point

- At any point on the equatorial plane, the distance ($r$) from the positive charge is equal to the distance from the negative charge.
- Since $V_{+q} = \frac{k q}{r}$ and $V_{-q} = \frac{-k q}{r}$, when added, they cancel out.
- **Result:** The electric potential at any point on the equatorial plane of a dipole is **zero ($\boldsymbol{V_{equatorial} = 0}$)**.

#### 3. Any General Point

- This calculation is performed for a **short dipole** at a point P located at distance $r$ and angle $\theta$ from the center.
- The general approach starts with $V_{total} = k q (1/r_1 - 1/r_2)$.
- For a short dipole, approximations are made: $r_1 \approx r_2 \approx r$ (in the denominator) and the difference $r_2 - r_1 \approx 2a \cos \theta$ (in the numerator).
- **Short Dipole Formula:** $$V_{any_point} = \frac{-k p \cos \theta}{r^2}$$.
- **Verification:** This general formula works for axial ($\theta=0^\circ, \cos 0^\circ=1 \implies V = -kp/r^2$) and equatorial ($\theta=90^\circ, \cos 90^\circ=0 \implies V = 0$) points.

### C. Electric Potential Due to a Uniformly Charged Spherical Shell (Hollow Sphere)

This is a conceptual topic rather than a full derivation.

1. **Outside the Shell ($r > R$):** The shell behaves like a point charge $Q$ concentrated at the center. $$V_{out} = \frac{k Q}{r}$$.
2. **On the Surface ($r = R$):** $$V_{surface} = \frac{k Q}{R}$$.
3. **Inside the Shell ($r < R$):**
    - The electric field ($E$) inside a hollow shell is zero.
    - Because $E=0$ inside, no extra work is done moving a charge _within_ the shell.
    - The potential inside is equal to the potential achieved by bringing the charge from infinity _to the surface_.
    - **Result:** Potential inside is **constant** and equal to the surface potential. $$V_{inside} = V_{surface} = \frac{k Q}{R}$$.
4. **Graph of Potential ($V$) vs. Distance ($r$):** Potential remains constant ($kQ/R$) from the center ($r=0$) up to the radius ($r=R$), and then decreases proportional to $1/r$ outside the sphere.

---

## IV. Relation Between Electric Field and Potential

A critical relationship is established between $E$ and $V$.

- **Derivation:** By equating the work done formulas ($dW = -F dx$ and $dW = q_0 dV$), and substituting $F = q_0 E$, we arrive at the relation: $$E = -\frac{dV}{dx}$$.
    
- **Significance of the Negative Sign:** The negative sign indicates that the electric field and the change in potential are always opposite.
    
    - **In the direction of the electric field, potential always drops (decreases)**.
    - _Example:_ If the E-field points right, a point furthest to the left has the highest potential.
- **Unit and Terminology:**
    
    - From $E = -dV/dx$, the unit of electric field is also **Volt per meter (V/m)**.
    - Since potential ($V$) is divided by length ($x$), Electric Field is also known as the **Potential Gradient**.

---

## V. Equipotential Surfaces

### A. Definition and Properties

- **Definition:** Any surface that has the same electric potential (equal potential) at every point on it.
- **Properties:**
    1. **Zero Work Done:** No electric work is required to move a charge from one point to another on an equipotential surface, because the potential difference ($\Delta V$) is zero ($W = q \cdot \Delta V$).
    2. **Electric Field is Normal:** Electric field lines are always **perpendicular (normal)** to the equipotential surface.
    3. **Spacing and Field Strength:** Equipotential surfaces are spaced **closer together** in regions where the electric field is **stronger**, and **farther apart** where the field is **weaker**.
    4. **No Intersection:** Two equipotential surfaces can never intersect, as this would mean a single point possesses two different potential values, which is physically impossible.

### B. Examples of Equipotential Surfaces

- **Point Charge:** Concentric spheres, where the radius is increasing, and the spacing between the spheres also increases as they move away from the charge (because the field weakens).
- **Two Equal & Opposite Charges (Dipole):** Surfaces are closer together in the region between the charges where the field is strong.
- **Uniform Electric Field:** Parallel, equally spaced plane sheets perpendicular to the direction of the electric field. If the field is non-uniform (increasing), the sheets will become progressively closer in the direction of the field increase.

---

## VI. Electric Potential Energy

- **Definition:** Energy stored when work is done against the electrostatic (conservative) force.
- **Formula for Two Charges ($q_1$ and $q_2$):** The work done in bringing a second charge ($q_2$) into the field of the first ($q_1$) from infinity is stored as potential energy ($U$). $$U = W = \frac{k q_1 q_2}{r}$$.
    - Note: Potential energy requires at least two charges.
- **Potential Energy of a System of Charges:** For multiple charges, the total potential energy is the scalar sum of the potential energy of every unique pair in the system.
    - Example (Three charges $q_1, q_2, q_3$): $$U_{total} = \frac{k q_1 q_2}{r_{12}} + \frac{k q_1 q_3}{r_{13}} + \frac{k q_2 q_3}{r_{23}}$$.

### Potential Energy of a Dipole in a Uniform Electric Field

When a dipole is rotated against the electric field, work is done, which is stored as potential energy.

- The small work done is $dW = \text{Torque} \cdot d\theta$.
- Using $\tau = p E \sin \theta$ (from Chapter 1), integrating $dW$ from an initial angle ($\theta_1$) to a final angle ($\theta_2$) yields the work done.
- **Formula:** $$U = W = p E (\cos \theta_1 - \cos \theta_2)$$.

---

## VII. Capacitance

### A. Core Concept and Formula

- **Capacitance:** The ability or capacity of a body to hold or store electric charge.
- Charging a body increases its potential ($Q \propto V$).
- **Fundamental Relation:** $$Q = C V$$ where $C$ is the constant of proportionality called **Capacitance**.
- **Formula:** $C = Q/V$. Capacitance is the charge stored per unit voltage.
- A higher capacitance means the body can store more charge ($Q$) for a smaller increase in potential ($V$).

### B. Factors Affecting Capacitance

Capacitance is a constant specific to the device and does _not_ change by varying $Q$ or $V$. It depends only on:

1. **Dimensions** (size, shape, radius, area, or separation) of the conductor/capacitor.
2. **Nature of the Material** (dielectric/medium) separating the conductors.

### C. Units and Dimensions

- **SI Unit:** **Farad (F)**, named after Michael Faraday.
- 1 Farad = 1 Coulomb per Volt (C/V).
- **Note:** 1 Farad is an extremely large unit; practical capacitors are usually measured in microFarads ($\mu F$), nanoFarads ($n F$), or picoFarads ($p F$).
- **Dimensions:** $[M^{-1} L^{-2} T^4 A^2]$.

---

## VIII. Types of Capacitors and Energy Storage

### A. Spherical Capacitor

- For an isolated spherical conductor of radius $r$, using $V = k Q/r$: $$C = 4\pi\epsilon_0 r$$.
- **1 Farad Difficulty:** To achieve a capacitance of 1 Farad (F), the required radius $r$ must be $9 \times 10^9$ meters, which is roughly 1000 times the radius of the Earth, making 1 Farad capacitance highly impractical for a single conductor.
- **Capacitor Symbols:**
    - Fixed Capacitor: Two parallel lines of equal length. (Distinguish from battery, which has unequal lines and fixed polarity).
    - Variable Capacitor: Two parallel lines of equal length with an arrow drawn across them.

### B. Parallel Plate Capacitor (PPC)

The most important structure in this chapter.

- **Structure:** Two parallel conductive plates (Area $A$) separated by a distance $d$.
- **Electric Field Inside:** The total electric field $E$ between the plates (in free space) is the sum of the fields from each plate: $$E = E_1 + E_2 = \frac{\sigma}{2\epsilon_0} + \frac{\sigma}{2\epsilon_0} = \frac{\sigma}{\epsilon_0}$$.
- Using the relations $E = V/d$ and $\sigma = Q/A$, and substituting into $C = Q/V$: $$\boldsymbol{C_{PPC} = \frac{\epsilon_0 A}{d}}$$.

### C. Capacitors in Combination

The rules for combining capacitors are the **reverse** of those for resistors.

|Combination|Series|Parallel|
|:--|:--|:--|
|**Shared Property**|Charge ($Q$) is the same.|Potential ($V$) is the same.|
|**Divided Property**|Voltage ($V$) is divided.|Charge ($Q$) is divided.|
|**Net Capacitance**|$\frac{1}{C_{net}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3} + \dots$|$C_{net} = C_1 + C_2 + C_3 + \dots$|

### D. Energy Stored in a Capacitor

- A capacitor stores energy in the form of an **electric field** between its plates, unlike a battery, which stores chemical energy.
- **Derivation:** The total work done ($W$) in bringing small amounts of charge ($dq$) to the capacitor is integrated.
- **Energy Stored Formulas (U):** $$U = \frac{1}{2} \frac{Q^2}{C}$$ $$U = \frac{1}{2} C V^2$$ $$U = \frac{1}{2} Q V$$.

### E. Energy Stored Per Unit Volume (Energy Density)

Energy density ($u$) is a better metric for capacitor quality than total energy stored.

- $u = U / \text{Volume}$. (Volume of PPC $= A d$).
- Substituting $U = \frac{1}{2} CV^2$ and $C = \epsilon_0 A/d$: $$\boldsymbol{u = \frac{1}{2} \epsilon_0 E^2}$$.
- This formula, dependent on the electric field $E$, confirms that the energy stored in a capacitor is purely **electric**.

---

## IX. Dielectrics and Capacitance

### A. Dielectrics and Polarization

- A **Dielectric** is a substance that can be polarized (separating positive and negative charges) when subjected to an external electric field (like the field between capacitor plates).
- **Effect:** Inserting a dielectric slab leads to polarization, generating an internal electric field ($E_D$) opposing the capacitor's field ($E_C$).
- This opposition decreases the net electric field ($E_{net}$), which subsequently decreases the potential difference ($V = E d$). Since $C = Q/V$, decreasing $V$ (while $Q$ is constant) **increases the capacitance**.

### B. PPC Capacitance with a Dielectric Slab (Thickness $t$)

When a dielectric slab of thickness $t$ ($t<d$) and dielectric constant $k$ is inserted into a PPC:

- The net voltage is the sum of the potential drop across the air gap ($d-t$) and the potential drop across the slab ($t$).
- The resulting capacitance formula is: $$\boldsymbol{C = \frac{\epsilon_0 A}{d - t + t/k}}$$.
- If the capacitor is **completely filled** ($t=d$): $$C_{new} = k \frac{\epsilon_0 A}{d} = k C_{old}$$ The capacitance increases by $k$ times ($k > 1$).
- **Note on Connection Status:** Whether the battery remains connected or is disconnected when the slab is inserted affects how $Q$ and $V$ change, but in both cases, the capacitance ($C$) always increases.

---

## X. Redistribution of Charge

When two charged bodies (capacitors $C_A, C_B$) are connected by a conducting wire:

- Charge flows until the **potential (voltage) of both bodies becomes equal** (a common potential $V$).
- The ratio of the final charges ($Q'$), which they hold after connection, is directly proportional to their capacitances ($C$): $$\frac{Q_{A}'}{Q_{B}'} = \frac{C_{A}}{C_{B}}$$.
- **Conclusion:** The final charge stored by each body depends only on its capacitance (dimensions and material), regardless of the initial charge or initial potential difference.

---

## XI. Key Concepts from Question Solving Section

1. **Q vs V Graph Slope:** The slope of a Charge ($Q$) versus Potential ($V$) graph represents the **Capacitance** ($C$).
2. **Work and Potential Difference:** The work done ($W$) in moving a charge is determined solely by the charge and the change in potential ($\Delta V$), $W = q \Delta V$. If $\Delta V$ is the same, the work done is the same, regardless of the shape of the path taken.
3. **Variable Potential and E-Field:** If the potential $V$ is given as a function of position (variable potential), the electric field $E$ must be calculated using the potential gradient formula: $E = -dV/dx$.
4. **Work to Disassociate a System:** The work required to disassemble (separate) a system of charges is equal to the negative of the system's total potential energy ($W_{disassociate} = -U_{system}$).
5. **Circuit Analysis:** In series capacitance: $Q$ is the same, $V$ divides. In parallel capacitance: $V$ is the same, $Q$ divides. To find the potential across an individual capacitor in a series circuit, first calculate the total charge ($Q_{net} = C_{net} V_{total}$), as this charge is the same for every capacitor in the series.