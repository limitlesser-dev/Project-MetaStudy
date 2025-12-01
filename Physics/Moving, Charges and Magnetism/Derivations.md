The sources contain several key derivations and formulas used to calculate magnetic forces, fields, and the resulting motion or torque. Below is a list of these derivations, organized by section.

### List of Derivations and Key Formulas

#### 4.2 Magnetic Force (Lorentz Force)

- **Lorentz Force Law (Total Force):** $$\mathbf{F} = q [\mathbf{E} (\mathbf{r}) + \mathbf{v} \times \mathbf{B} (\mathbf{r})]$$ _This fundamental equation is stated based on experimental evidence and detailed by H.A. Lorentz._
    
- **Magnetic Force on a Current-Carrying Conductor:** The force ($\mathbf{F}$) on a straight rod of length $l$ carrying current $I$ in an external magnetic field $\mathbf{B}$ is derived from the forces on individual charge carriers: $$\mathbf{F} = I \mathbf{l} \times \mathbf{B}$$ _This result is obtained by substituting the current density ($\mathbf{j}$) and volume ($lA$) into the magnetic force expression on the carriers: $\mathbf{F} = [(nq \mathbf{v}_d)lA] \times \mathbf{B} = [\mathbf{j} A\mathbf{l}] \times \mathbf{B} = I \mathbf{l} \times \mathbf{B}$._
    

#### 4.3 Motion in a Magnetic Field

- **Radius of Circular Path:** For a charged particle moving perpendicular to a uniform magnetic field, the magnetic force ($qvB$) provides the centripetal force ($mv^2/r$): $$r = \frac{m v}{q B}$$ _This is derived by equating the magnetic force and the centripetal force: $m v^2/r = q v B$._
    
- **Angular Frequency (Cyclotron Frequency):** Derived from the radius equation using $v = \omega r$: $$\omega = 2\pi \nu = \frac{q B}{m}$$ _This result is shown to be independent of velocity or energy._
    
- **Pitch of Helical Path:** The pitch ($p$) is the distance moved parallel to the magnetic field during one revolution ($T$): $$p = v_{||} T = \frac{2\pi m v_{||}}{q B}$$ _This derivation uses the parallel velocity component ($v_{||}$) and the period ($T = 2\pi/\omega$)._
    

#### 4.4 Magnetic Field Due to a Current Element

- **Biot-Savart Law (Vector Form):** The magnetic field element ($\mathbf{dB}$) produced by a current element ($I\mathbf{dl}$) at a distance $\mathbf{r}$ is: $$d\mathbf{B} = \frac{\mu_0}{4\pi} \frac{I d\mathbf{l} \times \mathbf{r}}{r^3}$$ _This is presented as the basic equation for the magnetic field produced by current._
    
- **Biot-Savart Law (Magnitude Form):** $$d B = \frac{\mu_0}{4\pi} \frac{I dl \sin \theta}{r^2}$$ _This form is derived directly from the vector cross-product property._
    

#### 4.5 Magnetic Field on the Axis of a Circular Current Loop

- **Magnetic Field on the Axis:** The magnetic field ($\mathbf{B}$) at a point $x$ along the axis of a circular loop of radius $R$ is derived by integrating the Biot-Savart contributions ($dB_x = dB \cos \theta$) over the loop: $$\mathbf{B} = \frac{\mu_0 I R^2}{2(x^2 + R^2)^{3/2}} \mathbf{\hat{i}}$$ _This formula is obtained by summing the axial components of $d\mathbf{B}$ (with perpendicular components canceling)._
    
- **Magnetic Field at the Center:** Setting $x=0$ in the axial field equation yields the field at the center: $$B = \frac{\mu_0 I}{2 R}$$ _This is a special case derived from the general axial field derivation._
    
- **Magnetic Field (Approximation for $x \gg R$):** For points far from the loop ($x \gg R$), the denominator simplifies, relating the field to the magnetic moment ($m = IA$): $$B \simeq \frac{\mu_0}{4\pi} \frac{2 \mathbf{m}}{x^3}$$ _This result is obtained by dropping $R^2$ in the denominator of the axial field formula and substituting $A = \pi R^2$._
    

#### 4.6 & 4.7 Applications of Ampere's Circuital Law

- **Magnetic Field of an Infinite Straight Wire:** Using the simplified Ampere's law ($BL = \mu_0 I_e$) with an Amperian circle of radius $r$ ($L = 2\pi r$): $$B = \frac{\mu_0 I}{2\pi r}$$ _This is derived by applying Ampere's law, $B(2\pi r) = \mu_0 I$._
    
- **Magnetic Field Inside a Long Solenoid:** Using the simplified Ampere's law over a rectangular loop, where $h$ is the length of the segment inside the solenoid ($L=h$) and the enclosed current is $I_e = I (n h)$: $$B = \mu_0 n I$$ _This derivation relies on the assumption that the field is zero outside and uniform inside, yielding $B h = \mu_0 I (n h)$._
    

#### 4.8 Force Between Two Parallel Currents

- **Force Per Unit Length Between Parallel Wires:** The magnitude of the force per unit length ($f_{ba}$) exerted by wire $a$ on wire $b$ is derived using the magnetic field of wire $a$ ($B_a = \mu_0 I_a / (2\pi d)$) and the force equation on a conductor ($\mathbf{F} = I \mathbf{l} \times \mathbf{B}$): $$f_{ba} = \frac{\mu_0}{2\pi} \frac{I_a I_b}{d}$$ _This derivation defines the Ampere unit._

#### 4.9 Torque on Current Loop

- **Torque on a Rectangular Loop (General Case):** The torque ($\mathbf{\tau}$) on a rectangular loop of area $A=ab$ and current $I$ placed in a uniform field $\mathbf{B}$ is derived by summing the torques due to forces $\mathbf{F}_1$ and $\mathbf{F}_2$: $$\tau = I A B \sin \theta$$ _This is derived from the forces $F_1 = F_2 = IbB$ and the perpendicular distance between them ($a \sin \theta$)._
    
- **Vector Torque using Magnetic Moment:** Using the magnetic moment definition ($\mathbf{m} = I \mathbf{A}$ or $\mathbf{m} = N I \mathbf{A}$ for $N$ turns): $$\mathbf{\tau} = \mathbf{m} \times \mathbf{B}$$ _This expression is analogous to the electric dipole torque._
    

#### 4.10 Moving Coil Galvanometer (MCG)

- **Equilibrium Deflection:** The principle of the MCG relies on balancing the magnetic torque ($\tau = NIAB$, since the field is radial, $\sin \theta = 1$) with the restoring torque of the spring ($k\phi$): $$k\phi = N I A B$$ _This relation is used to determine the deflection ($\phi$) based on the current ($I$)._