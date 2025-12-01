The following notes provide a detailed summary of the concepts, laws, and applications related to Moving Charges and Magnetism, drawing exclusively from the provided source material.

## Chapter 4: Moving Charges and Magnetism

### 4.1 Introduction: Historical Context and Conventions

- **Historical Discovery:** While electricity and magnetism were known for over 2000 years, their intimate relationship was only realized about **200 years ago, in 1820**.
- **Oersted's Experiment (1820):** Danish physicist Hans Christian Oersted observed that a current in a straight wire caused a noticeable **deflection in a nearby magnetic compass needle** during a lecture demonstration.
    - The needle's alignment was tangential to an imaginary circle centered on the straight wire, with its plane perpendicular to the wire.
    - Reversing the current reversed the needle's orientation.
    - Iron filings sprinkled around the wire arranged themselves in **concentric circles**.
- **Fundamental Conclusion:** Oersted concluded that **moving charges or currents produced a magnetic field** in the surrounding space.
- **Unification:** The laws obeyed by electricity and magnetism were unified and formulated by **James Maxwell in 1864**, who subsequently realized that light consisted of electromagnetic waves.
- **Conventions:** The direction of a current or field is shown using two symbols:
    - **Dot (¤):** Depicts a current or field **emerging out of the plane** of the paper (like the tip of an arrow pointed at you).
    - **Cross ( ):** Depicts a current or field **going into the plane** of the paper (like the feathered tail of an arrow moving away from you).

### 4.2 Magnetic Force (Lorentz Force)

#### Sources and Fields

- Just as static charges produce an electric field ($\mathbf{E}$), **currents or moving charges produce (in addition) a magnetic field ($\mathbf{B}$) **. $\mathbf{B}$ is a vector field defined at each point in space.
- The magnetic field, like the electric field, obeys the **principle of superposition**, meaning the field of several sources is the vector sum of individual source fields.

#### The Lorentz Force

- The total force ($\mathbf{F}$) on a point charge $q$ moving with velocity $\mathbf{v}$ in the presence of both an electric field ($\mathbf{E}$) and a magnetic field ($\mathbf{B}$) is the **Lorentz force**: $$\mathbf{F} = q [\mathbf{E} (\mathbf{r}) + \mathbf{v} \times \mathbf{B} (\mathbf{r})]$$
- **Characteristics of the Magnetic Force ($\mathbf{F}_{magnetic} = q [\mathbf{v} \times \mathbf{B}]$):**
    1. It is **zero** if the charge is **not moving** ($|\mathbf{v}|=0$). Only a moving charge feels the magnetic force.
    2. It involves a vector product ($\mathbf{v} \times \mathbf{B}$).
    3. It **vanishes** (is zero) if the velocity ($\mathbf{v}$) and magnetic field ($\mathbf{B}$) are **parallel or anti-parallel**.
    4. The force direction is always **perpendicular to both the velocity and the magnetic field** (sideways direction). Its direction is determined by the **screw rule or right-hand rule**.
    5. The force on a negative charge is opposite to that on a positive charge.

#### Unit of Magnetic Field

- The SI unit of $\mathbf{B}$ is the **tesla (T)**, named after Nikola Tesla.
- Dimensionally, $[\mathbf{B}] = [\text{F/qv}]$.
- One tesla is the magnitude of the magnetic field when a force of one newton acts on a unit charge (1 C) moving perpendicular to $\mathbf{B}$ at 1 m/s.
- A smaller, non-SI unit is the **gauss** ($1 \text{ gauss} = 10^{-4} \text{ tesla}$).

#### Magnetic Force on a Conductor

- A straight rod of length $l$ carrying a steady current $I$ in an external magnetic field $\mathbf{B}$ experiences a force given by: $$\mathbf{F} = I \mathbf{l} \times \mathbf{B}$$ _Note: $\mathbf{l}$ is a vector of magnitude $l$ with a direction identical to the current $I$. $\mathbf{B}$ must be the external field, not the field produced by the rod itself._

### 4.3 Motion in a Magnetic Field

- **Work and Energy:** Since the magnetic force $q (\mathbf{v} \times \mathbf{B})$ is always perpendicular to the velocity ($\mathbf{v}$), **no work is done**, and the **magnitude of the velocity** (kinetic energy) **remains unchanged**.
- **Circular Motion:** If the velocity ($\mathbf{v}$) is perpendicular to the uniform magnetic field ($\mathbf{B}$), the magnetic force acts as a **centripetal force** ($q v B$), resulting in **circular motion** perpendicular to $\mathbf{B}$.
    - **Radius of the path ($r$):** $$r = \frac{m v}{q B}$$
    - **Angular frequency ($\omega$) or Cyclotron frequency ($\nu$):** $$\omega = 2\pi \nu = \frac{q B}{m}$$ This frequency is **independent of the particle’s velocity or energy**. This independence is utilized in the design of a cyclotron.
- **Helical Motion:** If the velocity has a component parallel to $\mathbf{B}$ ($v_{||}$), this component is unaffected, and the particle follows a **helical path**.
    - **Pitch ($p$):** The distance moved along the magnetic field during one rotation: $$p = v_{||} T = \frac{2\pi m v_{||}}{q B}$$

### 4.4 Magnetic Field Due to a Current Element, Biot-Savart Law

- The relationship between the current ($I$) and the magnetic field ($\mathbf{B}$) it produces is given by the Biot-Savart law.
- **Vector Form:** The magnetic field element ($\mathbf{dB}$) due to a current element ($I\mathbf{dl}$) at a distance $\mathbf{r}$ is: $$d\mathbf{B} = \frac{\mu_0}{4\pi} \frac{I d\mathbf{l} \times \mathbf{r}}{r^3}$$
- **Magnitude Form:** $$d B = \frac{\mu_0}{4\pi} \frac{I dl \sin \theta}{r^2}$$ _($\theta$ is the angle between $I\mathbf{dl}$ and the displacement vector $\mathbf{r}$)._
- **Permeability of Free Space ($\mu_0$):** The constant $\frac{\mu_0}{4\pi}$ has the exact value $10^{-7} \text{ T m/A}$ in SI units.
- **Direction:** $\mathbf{dB}$ is **perpendicular to the plane containing $I\mathbf{dl}$ and $\mathbf{r}$**. The sense is given by the Right Hand Screw rule.
- **Comparison with Coulomb's Law (Electrostatics):**
    - Both laws are long range (inverse square dependence) and linear in their source, obeying superposition.
    - **Difference in Source:** $\mathbf{E}$ is produced by a scalar source (charge); $\mathbf{B}$ is produced by a **vector source** ($I\mathbf{dl}$).
    - **Difference in Field Direction:** $\mathbf{E}$ is along the displacement vector ($\mathbf{r}$); $\mathbf{B}$ is **perpendicular** to the plane containing $\mathbf{r}$ and $I\mathbf{dl}$.
    - $\mathbf{B}$ is zero along the line of the current element itself ($\theta=0$).

### 4.5 Magnetic Field on the Axis of a Circular Current Loop

- **Setup:** For a circular loop of radius $R$ carrying steady current $I$, the magnetic field is evaluated along the axis at distance $x$ from the center.
- **Calculation:** Due to symmetry, the components of $\mathbf{dB}$ perpendicular to the axis cancel out. Integrating the axial components yields: $$\mathbf{B} = \frac{\mu_0 I R^2}{2(x^2 + R^2)^{3/2}} \mathbf{\hat{i}}$$
- **Field at the Center ($x=0$):** $$B = \frac{\mu_0 I}{2 R}$$
- **Field Direction:** Given by the **right-hand thumb rule**: Curl the palm of the right hand around the wire with fingers pointing in the current direction; the thumb points in the direction of the magnetic field ($\mathbf{B}$).

### 4.6 Ampere’s Circuital Law

- **Statement:** The integral of the magnetic field ($\mathbf{B}$) around a closed loop ($C$) is equal to $\mu_0$ times the total current ($I$) passing through the surface bounded by $C$: $$\oint \mathbf{B} \cdot d\mathbf{l} = \mu_0 I$$
- **Sign Convention:** Determined by the right-hand rule; if fingers curl in the direction of the loop integral, the thumb points in the positive direction for current $I$.
- **Simplified Form:** For systems with high symmetry (where $\mathbf{B}$ is tangential and constant over length $L$, or normal/zero elsewhere): $$BL = \mu_0 I_e$$ _($I_e$ is the net current enclosed by the loop)._
- **Field of an Infinite Straight Wire:** Applying Ampere's law to a concentric circular loop yields: $$B = \frac{\mu_0 I}{2\pi r}$$
    - The magnetic field lines form **closed loops** (concentric circles), unlike electrostatic field lines.
- **Analogy:** Ampere's circuital law is analogous to Gauss’s law in electrostatics; both relate a physical quantity on the boundary (field) to the source in the interior (current or charge). Ampere's law holds for **steady currents**.

### 4.7 The Solenoid

- **Definition:** A long solenoid consists of a long wire wound in a helix with closely spaced turns (meaning its length is large compared to its radius).
- **Field Characteristics (Ideal Solenoid):** The field is **uniform, strong, and parallel to the axis inside** the solenoid. The field outside approaches zero.
- **Magnetic Field Magnitude ($B$):** Using Ampere's law and assuming the field outside is zero, the magnitude of the field inside is calculated to be: $$B = \mu_0 n I$$ _($n$ is the number of turns per unit length and $I$ is the current)._
- Solenoids are commonly used to obtain a **uniform magnetic field**.

### 4.8 Force Between Two Parallel Currents, The Ampere

- **Interaction:** Two parallel current-carrying conductors exert magnetic forces on each other.
- **Direction Rule:**
    - **Parallel currents attract** each other.
    - **Antiparallel currents repel** each other. (This is the opposite of electrostatics where like charges repel).
- **Force Per Unit Length ($f$):** For two long parallel conductors carrying currents $I_a$ and $I_b$ separated by distance $d$: $$f = \frac{\mu_0}{2\pi} \frac{I_a I_b}{d}$$ _This result is consistent with Newton's Third Law for steady currents._
- **Definition of the Ampere (SI Base Unit):** The force equation is used to define the ampere: **One ampere (A)** is the steady current which, when maintained in two very long, straight, parallel conductors of negligible cross-section, placed one metre apart in vacuum, produces on each conductor a force equal to **$2 \times 10^{-7} \text{ newtons per metre}$** of length.
- **Definition of the Coulomb (Derived Unit):** One coulomb (1 C) is the quantity of charge that flows through a cross-section in 1s when a steady current of 1A is established.

### 4.9 Torque on Current Loop, Magnetic Dipole

- **Force and Torque:** A current-carrying rectangular loop placed in a uniform magnetic field experiences **no net force** but experiences a **torque**.
- **Torque Magnitude:** If the plane of the loop makes an angle $\theta$ with the normal to the coil (area vector $\mathbf{A}$), the torque is: $$\tau = I A B \sin \theta$$
- **Magnetic Moment ($\mathbf{m}$):** The magnetic moment of a current loop of area $A$ with $N$ closely wound turns is defined as a vector: $$\mathbf{m} = N I \mathbf{A}$$ _The direction of $\mathbf{A}$ (and $\mathbf{m}$) is given by the right-hand thumb rule. The unit of $\mathbf{m}$ is $\text{A m}^2$._
- **Vector Torque Expression:** $$\mathbf{\tau} = \mathbf{m} \times \mathbf{B}$$ _This is analogous to the torque on an electric dipole ($\mathbf{\tau} = \mathbf{p}_e \times \mathbf{E}$)._
- **Equilibrium:** The torque vanishes when $\mathbf{m}$ is parallel or anti-parallel to $\mathbf{B}$.
    - **Stable Equilibrium:** Occurs when $\mathbf{m}$ and $\mathbf{B}$ are parallel ($\theta=0$). In this orientation, the magnetic flux of the total field (external + loop's field) is maximized.
- **Circular Loop as a Dipole:** For points far from a circular loop ($x \gg R$), the magnetic field along the axis behaves like that of a dipole, proportional to $1/x^3$: $$B \simeq \frac{\mu_0}{4\pi} \frac{2 m}{x^3}$$
- **Fundamental Difference (Monopoles):** While an electric dipole is built of two charges (monopoles), the magnetic dipole (current loop) is the most elementary magnetic element. **Magnetic monopoles are not known to exist**.

### 4.10 The Moving Coil Galvanometer (MCG)

- **Function:** A device for detecting and measuring currents and voltages.
- **Construction:** Consists of a coil with many turns free to rotate in a strong, **uniform radial magnetic field**. A cylindrical soft iron core is used to make the field radial and increase its strength.
- **Principle (Equilibrium):** When current $I$ flows, the magnetic torque ($\tau = NIAB$) is balanced by the counter torque ($k\phi$) provided by a spring, resulting in a steady angular deflection ($\phi$): $$k\phi = N I A B$$ _($k$ is the torsional constant of the spring)._
- **Current Sensitivity:** Deflection per unit current: $$\frac{\phi}{I} = \frac{N A B}{k}$$
- **Conversion to Ammeter:**
    1. The galvanometer (G) is connected in **series** in the circuit.
    2. A small resistance ($r_s$) called a **shunt resistance** is connected **in parallel** with the galvanometer coil.
    3. This arrangement ensures most of the current bypasses the sensitive coil and keeps the total resistance low (approximately $r_s$).
- **Conversion to Voltmeter:**
    1. The galvanometer (G) is connected **in parallel** across the section of the circuit whose voltage is to be measured.
    2. A large resistance ($R$) is connected **in series** with the galvanometer.
    3. This arrangement ensures the instrument draws a very small current, preventing disturbance to the original circuit. The voltmeter resistance is approximately $R$.
- **Voltage Sensitivity:** Deflection per unit voltage: $$\frac{\phi}{V} = \frac{N A B}{k R_G}$$ _Note: Increasing the number of turns ($N$) may double the current sensitivity, but since the galvanometer resistance ($R_G$) also doubles, the voltage sensitivity may remain unchanged._