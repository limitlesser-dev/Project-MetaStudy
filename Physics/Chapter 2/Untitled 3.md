Based on the provided excerpts, here are detailed notes covering the concepts of Electric Charges, Fields, Coulomb's Law, and Gauss's Law.

---

## Detailed Notes on Electric Charges and Fields

### 1.1 Introduction

- Common experiences like seeing sparks when removing synthetic clothes, hearing crackles in dry weather, lightning during thunderstorms, or feeling an electric shock when touching a car door or bus bar are examples of **electric discharge**.
- These discharges involve electric charges accumulated due to rubbing insulating surfaces.
- This phenomenon is associated with the generation of **static electricity**, where 'static' means anything that does not move or change with time.
- **Electrostatics** is the field of study that deals with the forces, fields, and potentials arising from static charges.

### 1.2 Electric Charge

- **Discovery:** Thales of Miletus, Greece (around 600 BC), discovered that amber rubbed with wool or silk cloth attracts light objects.
- The name **electricity** is coined from the Greek word _elektron_, meaning amber.
- **Observations on Electrification:** Bodies rubbed together (like glass and silk, or plastic and cat's fur) acquire an electric charge and become **electrified**.
- **Interaction Rules:** There are two kinds of electric charge:
    1. **Like charges repel**.
    2. **Unlike charges attract** each other.
- The property that differentiates these two kinds of charges is called the **polarity of charge**.
- **Naming Convention:** Benjamin Franklin named the charges positive and negative.
    - Charge on a glass rod rubbed with silk or cat’s fur is conventionally called **positive**.
    - Charge on a plastic rod or silk is conventionally termed **negative**.
- **Neutralization:** When a charged object (like a glass rod) is brought into contact with the material it was rubbed with (like silk), the acquired unlike charges neutralize or nullify each other’s effect, and they become electrically neutral again.
- **Charge Generation Mechanism:**
    - Normally, matter is electrically neutral because its charges are exactly balanced.
    - To electrify a neutral body, one must add or remove one kind of charge, resulting in an excess or deficit of charge.
    - In solids, some electrons are loosely bound and are the charges transferred from one body to another during rubbing.
    - A body becomes **positively charged** by losing electrons and **negatively charged** by gaining electrons.
    - Crucially, **no new charge is created** during the process of rubbing; charge is merely transferred.

### 1.3 Conductors and Insulators

- **Conductors:** Substances that easily allow electricity to pass through them. They possess electric charges (electrons) that are comparatively free to move inside the material.
    - Examples: Metals, human and animal bodies, and the earth.
    - Behavior: Charge transferred to a conductor readily gets distributed over its entire surface.
- **Insulators (Non-conductors):** Substances that offer high resistance to the passage of electricity.
    - Examples: Glass, porcelain, plastic, nylon, and wood.
    - Behavior: Charge put on an insulator stays localized at the same place.
- **Semiconductors:** A third category that offers resistance to charge movement intermediate between conductors and insulators.
- **Grounding/Leakage:** Charges on a metal article, like a spoon, leak through a human body (a conductor) to the ground (a conductor), which is why metals generally do not become electrified when held and rubbed.

### 1.4 Basic Properties of Electric Charge

#### Point Charges

- When the sizes of charged bodies are very small compared to the distances between them, they are treated as **point charges**, with all charge content concentrated at one point.

#### 1.4.1 Additivity of charges

- Charges are scalar quantities and add algebraically like real numbers (similar to mass).
- The total charge of a system is the sum of individual charges, using proper signs (positive or negative). Example: Total charge of a system containing $q_1, q_2, ..., q_n$ is $q_1 + q_2 + q_3 + ... + q_n$.
- Unlike mass, which is always positive, charge can be positive or negative.

#### 1.4.2 Charge is conserved

- The **total charge of an isolated system is always conserved**.
- This means that charges are neither created nor destroyed; they are only transferred (e.g., electrons moving from one body to another during rubbing).
- Charge-carrying particles (like protons and electrons) can be created or destroyed, but the net charge carried by the isolated system remains zero.

#### 1.4.3 Quantisation of charge

- **Quantisation of charge** is the principle that all free charges are integral multiples of a basic unit of charge, $e$.
- The charge $q$ on a body is given by $q = ne$, where $n$ is any positive or negative integer.
- $e$ is the magnitude of charge carried by an electron ($-e$) or a proton ($+e$).
- This quantisation was suggested by Faraday and experimentally demonstrated by Millikan in 1912.
- **SI Unit of Charge:** The **coulomb (C)**.
    - $1 \text{ C}$ is defined as the charge flowing through a wire in $1 \text{ s}$ if the current is $1 \text{ A}$ (ampere).
    - The value of the basic unit of charge is $\mathbf{e = 1.602192 \times 10^{-19} \text{ C}}$.
    - In electrostatics, smaller units are often used, such as $1 \mu\text{C} = 10^{-6} \text{ C}$ or $1 \text{ mC} = 10^{-3} \text{ C}$.
- **Macroscopic Scale:** At the macroscopic level, where charges are enormous compared to $e$ (e.g., $1 \mu\text{C}$ is $\sim 10^{13}$ times the electronic charge), the grainy nature of charge is lost, and it appears continuous; thus, quantisation can be ignored.

### 1.5 Coulomb’s Law

- **Definition:** A quantitative statement describing the force between two point charges.
- **Dependence (Magnitude):** The magnitude of the force ($F$) between two point charges $q_1$ and $q_2$ separated by distance $r$ in vacuum is:
    1. Directly proportional to the product of the magnitudes of the charges ($q_1 q_2$).
    2. Inversely proportional to the square of the distance ($r^2$) between them.
    3. Acts along the line joining the two charges.
- **Mathematical Form (Magnitude):** $\mathbf{F = k \frac{q_1 q_2}{r^2}}$.
- **Experimental Verification:** Coulomb used a torsion balance to measure the force. The law holds down to the subatomic level ($r \sim 10^{-10} \text{ m}$).
- **Constant $k$:** In SI units, $\mathbf{k \approx 9 \times 10^9 \text{ Nm}^2\text{ C}^{-2}}$.
- **Defining 1 Coulomb:** $1 \text{ C}$ is the charge that, when placed $1 \text{ m}$ away from another identical charge in vacuum, experiences an electrical force of repulsion of magnitude $9 \times 10^9 \text{ N}$.
- **Permittivity of Free Space ($\epsilon_0$):** $k$ is often written as $k = 1/(4\pi\epsilon_0)$.
    - $\mathbf{\epsilon_0 = 8.854 \times 10^{-12} \text{ C}^2 \text{ N}^{-1}\text{m}^{-2}}$.
    - The law is written as $F = \frac{1}{4\pi\epsilon_0} \frac{q_1 q_2}{r^2}$.
- **Vector Form:** The force on $q_2$ due to $q_1$ is $\mathbf{F}_{21} = \frac{1}{4\pi\epsilon_0} \frac{q_1 q_2}{r_{21}^2} \mathbf{\hat{r}}_{21}$, where $\mathbf{\hat{r}}_{21}$ is the unit vector directed from $q_1$ to $q_2$.
    - If $q_1$ and $q_2$ have the same sign (like charges), $\mathbf{F}_{21}$ is repulsive (along $\mathbf{\hat{r}}_{21}$).
    - If $q_1$ and $q_2$ have opposite signs (unlike charges), $\mathbf{F}_{21}$ is attractive (along $-\mathbf{\hat{r}}_{21}$).
- **Consistency with Newton's Third Law:** Coulomb's law satisfies Newton's third law, meaning $\mathbf{F}_{12} = -\mathbf{F}_{21}$.
- **Comparison to Gravitational Force:** Both follow an inverse-square law. However, electrical forces are enormously stronger than gravitational forces (ratio between an electron and proton is about $2.4 \times 10^{39}$). Gravitational force is always attractive, while Coulomb force can be attractive or repulsive.

### 1.6 Forces Between Multiple Charges (Superposition Principle)

- The mutual electric force between two charges is unaffected by the presence of other charges.
- **Principle of Superposition:** The force on any specific charge (e.g., $q_1$) due to a number of other charges ($q_2, q_3, ...$) is the **vector sum** of the forces due to each of the other charges calculated individually.
- Total force on $q_1$: $\mathbf{F}_1 = \mathbf{F}_{12} + \mathbf{F}_{13} + ... + \mathbf{F}_{1n}$.
- The basis of all electrostatics relies on Coulomb’s law and the superposition principle.

### 1.7 Electric Field

- **Concept:** A source charge ($Q$) produces an electric field ($\mathbf{E}$) everywhere in the surrounding space. When a test charge ($q$) is placed at a point, the field acts on it to produce a force.
- **Definition:** The electric field $\mathbf{E}(\mathbf{r})$ at a point $\mathbf{r}$ is the force ($\mathbf{F}$) exerted on a small positive test charge ($q$) placed at that point, divided by the charge: $\mathbf{F}(\mathbf{r}) = q \mathbf{E}(\mathbf{r})$.
    - Operationally defined as: $\mathbf{E} = \lim_{q \to 0} \left(\frac{\mathbf{F}}{q}\right)$.
- **Source Charge ($Q$):** The charge producing the electric field.
- **Test Charge ($q$):** The charge used to measure the effect of the source charge. It must be negligibly small to avoid disturbing the source charge.
- **Properties of $\mathbf{E}$ due to a Point Charge $Q$:**
    - $\mathbf{E}$ is independent of the test charge $q$.
    - $\mathbf{E}$ is directed **radially outwards** for a positive source charge.
    - $\mathbf{E}$ is directed **radially inwards** for a negative source charge.
    - The magnitude of $\mathbf{E}$ has spherical symmetry, depending only on the distance $r$ from $Q$.
- **SI Unit:** Newton per Coulomb ($\text{N}/\text{C}$).

#### 1.7.1 Electric field due to a system of charges

- Using the superposition principle, the total electric field $\mathbf{E}$ at a point $\mathbf{r}$ due to a system of charges is the **vector sum** of the individual electric fields produced by each source charge.
- $\mathbf{E}(\mathbf{r}) = \mathbf{E}_1(\mathbf{r}) + \mathbf{E}_2(\mathbf{r}) + … + \mathbf{E}_n(\mathbf{r})$.

#### 1.7.2 Physical significance of electric field

- The concept is primarily a convenient way to characterize the electrical environment in electrostatics.
- The field concept becomes truly essential when dealing with **time-dependent electromagnetic phenomena** (beyond electrostatics).
- The field picture accounts for the time delay in interactions: accelerated motion of one charge produces electromagnetic waves traveling at speed $c$, which then propagate and cause a force on the distant charge.
- Electric and magnetic fields are considered **physical entities** that have independent dynamics and can transport energy, rather than just mathematical constructs.

### 1.8 Electric Field Lines

- **Definition:** An electric field line is a curve such that the **tangent to it at each point is in the direction of the net electric field** at that point.
- Field lines are a pictorial way (invented by Faraday, who called them lines of force) of mapping the electric field.
- **Field Strength Indication:** The magnitude of the field is represented by the **density of field lines** (relative closeness).
    - Lines crowd together where the field is strong.
    - Lines are spaced apart where the field is weak.
- **Field Line Properties:**
    1. Field lines start from **positive charges** and end at **negative charges** (or start/end at infinity if a single charge exists).
    2. In a charge-free region, field lines are continuous curves without breaks.
    3. **Two field lines can never cross each other** (if they crossed, the field at that point would not have a unique direction, which is impossible).
    4. Electrostatic field lines **do not form any closed loops** (a consequence of the conservative nature of the electric field).
    5. In regions of constant electric field, field lines are uniformly spaced parallel straight lines.

### 1.9 Electric Flux ($\Phi$)

- **Definition:** Electric flux $\text{D}\Phi$ through a small area element $\mathbf{\Delta S}$ is defined as $\mathbf{D\Phi = E \cdot \Delta S = E \Delta S \cos\theta}$.
    - $\theta$ is the angle between the electric field $\mathbf{E}$ and the area element vector $\mathbf{\Delta S}$ (the normal).
- Flux is proportional to the number of field lines cutting the area element.
- **Area as a Vector:** An area element $\mathbf{\Delta S}$ is treated as a vector whose direction is along the normal ($\mathbf{\hat{n}}$) to the plane.
- **Convention for Closed Surfaces:** For a closed surface, the area element vector $\mathbf{\Delta S}$ is taken to be in the direction of the **outward normal**.
- **Total Flux:** The total flux $\Phi$ through a surface $S$ is the sum (integral) of fluxes over all small area elements: $\Phi \approx \sum_S \mathbf{E} \cdot \mathbf{\Delta S}$.
- **Unit:** $\text{N}\text{ C}^{-1}\text{ m}^2$.

### 1.10 Electric Dipole

- **Definition:** A pair of equal and opposite point charges, $q$ and $-q$, separated by a distance $2a$.
- **Total Charge:** Zero.
- **Field Behavior:** Because the charges are separated, the electric fields do not cancel exactly. At distances much larger than the separation ($r >> 2a$), the field falls off faster than a single charge field ($1/r^2$)—it falls off as $\mathbf{1/r^3}$.
- **Dipole Moment ($\mathbf{p}$):** A vector whose magnitude is $\mathbf{p = q \times 2a}$ and whose direction is along the dipole axis **from $-q$ to $q$**.
- **Field on the Axis (r >> a):** $\mathbf{E} \cong \frac{1}{4\pi\epsilon_0} \frac{2\mathbf{p}}{r^3}$.
- **Field on the Equatorial Plane (r >> a):** $\mathbf{E} \cong -\frac{1}{4\pi\epsilon_0} \frac{\mathbf{p}}{r^3}$.
- **Physical Significance:**
    - **Polar Molecules** (e.g., $\text{H}_2\text{O}$): Have a permanent electric dipole moment because the centers of positive and negative charges do not coincide.
    - **Non-Polar Molecules** (e.g., $\text{CO}_2, \text{CH}_4$): Normally have zero dipole moment because their charge centers coincide, but they can develop a moment when an external electric field is applied.

### 1.11 Dipole in a Uniform External Field

- When a permanent dipole ($\mathbf{p}$) is placed in a uniform external field ($\mathbf{E}$), the forces ($q\mathbf{E}$ and $-q\mathbf{E}$) cancel out, resulting in **zero net force** on the dipole.
- However, since the forces act at different points, the dipole experiences a **torque** ($\mathbf{\tau}$).
- **Torque Equation:** $\mathbf{\tau = p \times E}$.
- This torque tends to align the dipole with the direction of the field $\mathbf{E}$.
- **Non-uniform Field:** If the field is non-uniform, the net force is generally non-zero. A dipole aligns itself parallel to the field gradient:
    - If $\mathbf{p}$ is parallel to $\mathbf{E}$, the dipole experiences a net force toward the direction of **increasing field**.
    - If $\mathbf{p}$ is antiparallel to $\mathbf{E}$, the net force is toward the direction of **decreasing field**.
- This concept explains why a charged comb (which creates a non-uniform field) attracts neutral paper (which is polarized by the field).

### 1.12 Continuous Charge Distribution

- For macroscopic charges, it is more practical to define charge densities rather than working with discrete microscopic charges.
- The notion ignores the microscopic quantisation and discontinuity of charge.
- **Surface Charge Density ($\sigma$):** Charge per unit area: $\sigma = \Delta Q / \Delta S$. Units: $\text{C}/\text{m}^2$.
- **Linear Charge Density ($\lambda$):** Charge per unit length: $\lambda = \Delta Q / \Delta l$. Units: $\text{C}/\text{m}$.
- **Volume Charge Density ($\rho$):** Charge per unit volume (charge density): $\rho = \Delta Q / \Delta V$. Units: $\text{C}/\text{m}^3$.
- The electric field due to a continuous distribution is found by summing (integrating) the Coulomb contributions from all small charge elements ($\rho \Delta V$).

### 1.13 Gauss’s Law

- **Statement:** The total electric flux ($\Phi$) through **any closed surface** ($S$) is equal to $1/\epsilon_0$ times the total charge ($q$) enclosed by $S$.
- **Mathematical Form:** $\mathbf{\Phi = q/\epsilon_0}$.
- **Significance:** If the net electric flux through a closed surface is zero, the total charge contained inside the surface is zero.
- **Key Points:**
    - It is true for any closed surface, regardless of shape or size.
    - The enclosed charge ($q$) includes the sum of all charges **inside** $S$.
    - The electric field ($\mathbf{E}$) whose flux is calculated is due to **all charges**, both inside and outside $S$.
    - The chosen surface is called the **Gaussian surface**.
    - The Gaussian surface must not pass through any discrete charge (where $\mathbf{E}$ is ill-defined), but it can pass through a continuous charge distribution.
    - The law is especially useful for calculating $\mathbf{E}$ when the charge distribution possesses simple symmetry.
    - Gauss’s law is fundamentally based on the inverse square dependence of distance found in Coulomb’s law.

### 1.14 Applications of Gauss’s Law

#### 1.14.1 Field due to an infinitely long straight uniformly charged wire

- Due to symmetry, the electric field $\mathbf{E}$ is radial and depends only on the perpendicular distance $r$.
- Gaussian Surface: A coaxial cylinder of length $l$ and radius $r$.
- Result: $\mathbf{E} = \frac{\lambda}{2\pi\epsilon_0 r} \mathbf{\hat{n}}$, where $\lambda$ is the linear charge density.

#### 1.14.2 Field due to a uniformly charged infinite plane sheet

- Due to symmetry, the electric field $\mathbf{E}$ is everywhere perpendicular to the plane and its magnitude is independent of the coordinates parallel to the plane.
- Gaussian Surface: A rectangular parallelepiped (or cylinder) crossing the sheet normally.
- Result: $\mathbf{E} = \frac{\sigma}{2\epsilon_0} \mathbf{\hat{n}}$, where $\sigma$ is the surface charge density. The field magnitude $E$ is independent of the distance from the sheet.

#### 1.14.3 Field due to a uniformly charged thin spherical shell (Radius R)

- **Field outside the shell ($r \ge R$):**
    - Gaussian Surface: A sphere of radius $r$ centered at the shell.
    - Result: The field is exactly as if the entire total charge $q$ was concentrated at the center. $\mathbf{E} = \frac{1}{4\pi\epsilon_0} \frac{q}{r^2} \mathbf{\hat{r}}$.
- **Field inside the shell ($r < R$):**
    - The Gaussian surface encloses zero charge.
    - Result: $\mathbf{E = 0}$. This result confirms the inverse square dependence in Coulomb’s law.