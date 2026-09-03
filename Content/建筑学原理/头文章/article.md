# Particle Movement in Magnetic Field

> **Category:** Essay | **Words:** ~600   
> **Cover:** ![Cover](cover.jpg)

---
## 1. Core Concept
In the magnetic field, a charged particle will experience an external force called the *Lorentz force*, which will alter its trajectory into a helix.
The function of the Lorentz force is:
$$
\vec{F} = q (\vec{v} \times \vec{B})
$$
where 
* $q$ is the charge of the particle
* $\vec{v}$ is the velocity of the particle
* $\vec{B}$ is the magnetic field
* $\vec{F}$ is the Lorentz force exerted on the particle

## 2. Resolution of Motion
The initial velocity $\vec{v}_0$ can be seen as the vector sum of the velocities parallel to the magnetic field $\vec{v}_{\parallel}$ and perpendicular to the magnetic field $\vec{v}_{\perp}$.
The component velocity that is parallel to the magnetic field:
$$
v_{\parallel} = v \cos\theta
$$
Since it is parallel with the magnetic induction line, the component force is $q(v_{\parallel} \times B) = 0$, according to Newton's first law of motion, the particle maintains a constant linesar motion in the *z* direction.
The component velocity that is perpendicular to the magnetic field:
$$
v_{\perp} = v \sin\theta
$$
In the *x-y* surface, the component force is always in the direction perpendicular to the velocity, therefore acting as a centripetal force $F = m\frac{v^2}{r}$. The particle maintains circular motion in the *x-y* direction.

## 3. Circular Motion
Combining both functions:
$$
q v_{\perp} B = m \frac{v_{\perp}^2}{R}
$$
The cyclotron radius $R$ is：
$$
R = \frac{m v_{\perp}}{q B} = \frac{m v \sin\theta}{q B}
$$
The period $T$ is:
$$
T = \frac{2\pi R}{v_{\perp}} = \frac{2\pi m}{q B}
$$
The pitch of the particle is:
$$
d = v_{\parallel} T = (v \cos\theta) \left( \frac{2\pi m}{q B} \right) = \frac{2\pi m v \cos\theta}{q B}
$$

## 4. Visualization
Tap the link below to see demonstration.
https://physicssimulation-zgfugwmkhk2e2gfsz5vls6.streamlit.app/

---

*Cover image: A trail showing how a charged particle moves in the magnetic field.*
