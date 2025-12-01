This roadmap outlines the major topics and concepts covered in the sources concerning **MOVING CHARGES AND MAGNETISM**.

### Roadmap: Moving Charges and Magnetism

#### 4.1 Introduction: The Relationship Between Electricity and Magnetism

- **Historical Context:** Both electricity and magnetism were known for over 2000 years, but their intimate relationship was only realized about 200 years ago, in 1820.
- **Oersted's Discovery:** Danish physicist Hans Christian Oersted observed in 1820 that a current in a straight wire caused a noticeable deflection in a nearby magnetic compass needle. He concluded that **moving charges or currents produced a magnetic field** in the surrounding space.
- **Unification:** James Maxwell unified the laws obeyed by electricity and magnetism in 1864.
- **Conventions:** A current or field **emerging out of the plane of the paper** is shown by a **dot (¤)**, and one **going into the plane of the paper** is shown by a **cross ()**.

#### 4.2 Magnetic Force and the Lorentz Force

- **Source of Magnetic Field (B):** Just as static charges produce an electric field (E), **currents or moving charges produce (in addition) a magnetic field (B)**.
- **Lorentz Force:** The total force ($\mathbf{F}$) on a point charge $q$ moving with velocity $\mathbf{v}$ in the presence of both an electric field ($\mathbf{E}$) and a magnetic field ($\mathbf{B}$) is called the Lorentz force: $$\mathbf{F} = q [\mathbf{E} (\mathbf{r}) + \mathbf{v} \times \mathbf{B} (\mathbf{r})]$$
- **Magnetic Force Characteristics:** The magnetic part of the force ($\mathbf{F}_{magnetic} = q [\mathbf{v} \times \mathbf{B}]$) has the following features:
    - It **vanishes** if the velocity ($\mathbf{v}$) and magnetic field ($\mathbf{B}$) are **parallel or anti-parallel**.
    - It is **zero** if the charge is **not moving** ($|\mathbf{v}|=0$).
    - Its direction is determined by the **screw rule or right-hand rule** and is **perpendicular to both the velocity and the magnetic field**.
- **Unit of Magnetic Field:** The SI unit of $\mathbf{B}$ is the **tesla (T)**, where $[B] = [F/qv]$. A smaller non-SI unit is the gauss ($1 \text{ gauss} = 10^{-4} \text{ tesla}$).
- **Force on a Current-Carrying Conductor:** A straight rod of length $l$ carrying current $I$ in an external magnetic field $\mathbf{B}$ experiences a force given by: $$\mathbf{F} = I \mathbf{l} \times \mathbf{B}$$

#### 4.3 Motion in a Magnetic Field

- **Work and Energy:** Since the magnetic force $q (\mathbf{v} \times \mathbf{B})$ is perpendicular to the velocity ($\mathbf{v}$), **no work is done**, and there is **no change in the magnitude of the velocity** (kinetic energy).
- **Circular Motion:** If $\mathbf{v}$ is perpendicular to $\mathbf{B}$, the magnetic force acts as a centripetal force, causing the particle to describe a **circular motion** perpendicular to the magnetic field.
    - The radius of the circular path is $r = \frac{m v}{q B}$.
    - The angular frequency (cyclotron frequency) is $\omega = 2\pi\nu = \frac{q B}{m}$, which is **independent of velocity or energy**.
- **Helical Motion:** If the velocity has a component parallel to $\mathbf{B}$, the particle follows a **helical path**.

#### 4.4 & 4.5 Calculating Magnetic Fields

- **Biot-Savart Law (Section 4.4):** This law relates the current ($I$) to the magnetic field ($\mathbf{B}$) it produces. The magnitude of the field ($\mathbf{dB}$) due to a current element ($I\mathbf{dl}$) is proportional to the current, the length of the element, and $\sin \theta$ (where $\theta$ is the angle between $\mathbf{dl}$ and the displacement vector $\mathbf{r}$), and inversely proportional to $r^2$: $$d\mathbf{B} = \frac{\mu_0}{4\pi} \frac{I d\mathbf{l} \times \mathbf{r}}{r^3}$$
    - $\mu_0$ is the **permeability of free space**.
    - Unlike the electrostatic field, the magnetic field is produced by a **vector source** ($I\mathbf{dl}$) and is **perpendicular** to the plane containing $I\mathbf{dl}$ and $\mathbf{r}$.
- **Magnetic Field of a Circular Current Loop (Section 4.5):**
    - On the axis, at a distance $x$ from the center, the magnitude of $\mathbf{B}$ is: $$B = \frac{\mu_0 I R^2}{2(x^2 + R^2)^{3/2}}$$
    - At the center ($x=0$), the field reduces to $B = \frac{\mu_0 I}{2 R}$.
    - The direction of the field is given by the **right-hand thumb rule**.

#### 4.6 Ampere's Circuital Law

- **Ampere's Law:** This law provides an alternative way to express the Biot-Savart law, particularly useful for high-symmetry problems. It states that the integral of the magnetic field ($\mathbf{B}$) around a closed loop ($C$) is equal to $\mu_0$ times the total current ($I$) passing through the surface bounded by the loop: $$\oint \mathbf{B} \cdot d\mathbf{l} = \mu_0 I$$
- **Simplified Form (for high symmetry):** If the magnetic field $B$ is constant and tangential along the loop of length $L$, the equation simplifies to $BL = \mu_0 I_e$.
- **Application to Infinite Wire:** For a long, straight wire, Ampere's law easily yields the magnitude of the field at distance $r$: $B = \frac{\mu_0 I}{2\pi r}$.
- **Field Lines:** Magnetic field lines form **closed loops**, unlike electrostatic field lines.

#### 4.7 The Solenoid

- **Definition:** A long solenoid is a long wire wound in the form of a helix where turns are closely spaced.
- **Magnetic Field:** For a very long solenoid, the magnetic field is **uniform, strong, and parallel to the axis inside**, and approaches zero outside.
- **Calculation:** Using Ampere's law, the magnitude of the field inside a solenoid with $n$ turns per unit length is: $$B = \mu_0 n I$$

#### 4.8 Force Between Two Parallel Currents and the Definition of the Ampere

- **Interaction:** Two current-carrying conductors exert magnetic forces on each other.
- **Attraction/Repulsion:** **Parallel currents attract**, and **antiparallel currents repel**.
- **Force per Unit Length ($f$):** For two long parallel conductors carrying currents $I_a$ and $I_b$ separated by distance $d$: $$f = \frac{\mu_0}{2\pi} \frac{I_a I_b}{d}$$
- **The Ampere (A):** The force equation is used to define the **ampere**, which is one of the seven SI base units. One ampere is the steady current which, when maintained in two very long, straight, parallel conductors placed one meter apart in vacuum, produces on each conductor a force equal to $2 \times 10^{-7} \text{ newtons per metre}$ of length.

#### 4.9 Torque on Current Loop, Magnetic Dipole

- **Torque on a Rectangular Loop:** A current loop placed in a uniform magnetic field experiences a **torque** ($\mathbf{\tau}$) but **no net force**.
- **Magnetic Moment (m):** The torque is related to the loop's magnetic moment ($\mathbf{m}$), defined as $\mathbf{m} = I \mathbf{A}$ (or $\mathbf{m} = N I \mathbf{A}$ for $N$ turns).
- **Vector Torque:** $$\mathbf{\tau} = \mathbf{m} \times \mathbf{B}$$
- **Equilibrium:** The torque vanishes when $\mathbf{m}$ is parallel or antiparallel to $\mathbf{B}$ (state of equilibrium). Stable equilibrium occurs when $\mathbf{m}$ and $\mathbf{B}$ are parallel.
- **Magnetic Dipole Analogy:** At large distances, the magnetic field due to a circular current loop behaves similarly to the electric field of an electric dipole. A key difference is that the magnetic dipole is the elementary element, as **magnetic monopoles are not known to exist**.

#### 4.10 The Moving Coil Galvanometer (MCG)

- **Function:** The MCG is a useful instrument for detecting and measuring currents and voltages.
- **Principle:** When current flows through the coil in a radial magnetic field, the magnetic torque ($\tau = NIAB$) is balanced by a counter torque ($k\phi$) provided by a spring.
    - In equilibrium: **$k\phi = NIAB$**.
- **Conversion to Ammeter:** To measure current, a small **shunt resistance ($r_s$)** is connected **in parallel** with the galvanometer coil.
- **Conversion to Voltmeter:** To measure voltage, a large **resistance ($R$)** is connected **in series** with the galvanometer.
- **Sensitivity:** **Current sensitivity** is deflection per unit current ($\frac{\phi}{I} = \frac{NAB}{k}$). **Voltage sensitivity** is deflection per unit voltage ($\frac{\phi}{V} = \frac{NAB}{kR}$).