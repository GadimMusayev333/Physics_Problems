Below is the **fully corrected version of Tasks 1–10** written in **Markdown with `$$` LaTeX blocks**, ready to paste directly into **Google Colab / Jupyter Notebook**.

---

# **Section 0: Mathematical Foundations — Corrected Solutions**

---

# **1. Vector Algebra**

Given:

$$
\vec{a} = [2,1,-3], \qquad \vec{b} = [4,-2,1]
$$

---

### **a) Magnitude of each vector**

Magnitude formula:

$$
|\vec{v}|=\sqrt{x^2+y^2+z^2}
$$

For vector **a**:

$$
|\vec a|=\sqrt{2^2+1^2+(-3)^2}
$$

$$
=\sqrt{4+1+9}
$$

$$
=\sqrt{14}
$$

For vector **b**:

$$
|\vec b|=\sqrt{4^2+(-2)^2+1^2}
$$

$$
=\sqrt{16+4+1}
$$

$$
=\sqrt{21}
$$

---

### **b) Dot Product**

Formula:

$$
\vec a \cdot \vec b = a_x b_x + a_y b_y + a_z b_z
$$

Calculation:

$$
\vec a \cdot \vec b =
(2)(4)+(1)(-2)+(-3)(1)
$$

$$
=8-2-3
$$

$$
=3
$$

---

### **c) Cross Product**

Using the determinant:

$$
\vec a \times \vec b =
\begin{vmatrix}
i & j & k \
2 & 1 & -3 \
4 & -2 & 1
\end{vmatrix}
$$

Expanding:

# 

##
$$
i(1\cdot1-(-3)(-2))
$$

j(2\cdot1-(-3)(4))
+
k(2(-2)-1(4))
$$

$$
=(-5,-14,-8)
$$

---

### **d) Angle Between the Vectors**

Formula:

 $$
\cos\theta = \frac{\vec a \cdot \vec b}{|\vec a||\vec b|}
$$

Substitute values:

$$
\cos\theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

#

$$
\frac{3}{\sqrt{294}}
$$

Angle:

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

$$
\theta \approx 79.9^\circ
$$

---

# **2. Systems of Equations**

Solve:

$$
2x + 3y = 12
$$

$$
x - y = 1
$$

From the second equation:

$$
x = y + 1
$$

Substitute into the first equation:

$$
2(y+1) + 3y = 12
$$

$$
2y + 2 + 3y = 12
$$

$$
5y + 2 = 12
$$

$$
5y = 10
$$

$$
y = 2
$$

Now substitute into (x = y + 1):

$$
x = 2 + 1
$$

$$
x = 3
$$

Final solution:

$$
(x,y) = (3,2)
$$

---

# **3. Proportionality**

Universal law of gravitation:

$$
F = G\frac{m_1 m_2}{r^2}
$$

Changes:

$$
m_1' = \frac{1}{2}m_1
$$

$$
m_2' = \frac{1}{2}m_2
$$

$$
r' = 2r
$$

Substitute:

$$
F' = G\frac{(\frac12 m_1)(\frac12 m_2)}{(2r)^2}
$$

$$
=G\frac{\frac14 m_1m_2}{4r^2}
$$

$$
=\frac{1}{16}G\frac{m_1m_2}{r^2}
$$

Therefore:

$$
F' = \frac{1}{16}F
$$

The gravitational force becomes **1/16 of the original**.

---

# **4. Rearranging Formulas**

Pendulum period:

$$
T = 2\pi\sqrt{\frac{L}{g}}
$$

Divide both sides by (2\pi):

$$
\frac{T}{2\pi}=\sqrt{\frac{L}{g}}
$$

Square both sides:

$$
\frac{T^2}{4\pi^2}=\frac{L}{g}
$$

Solve for (g):

$$
g = \frac{4\pi^2 L}{T^2}
$$

---

# **5. Trigonometry**

Given:

Magnitude:

$$
|A| = 15
$$

Angle:

$$
\theta = 60^\circ
$$

---

### Horizontal component

$$
A_x = A\cos\theta
$$

$$
A_x = 15\cos60^\circ
$$

$$
A_x = 15(0.5)
$$

$$
A_x = 7.5
$$

---

### Vertical component

$$
A_y = A\sin\theta
$$

$$
A_y = 15\sin60^\circ
$$

$$
A_y = 15\frac{\sqrt3}{2}
$$

$$
A_y \approx 12.99
$$

---

# **6. Function Analysis**

Given:

$$
f(x)=3x^2-12x+7
$$

First derivative:

$$
f'(x)=6x-12
$$

Set derivative to zero:

$$
6x-12=0
$$

$$
x=2
$$

Second derivative:

$$
f''(x)=6
$$

Since:

$$
6>0
$$

the point is a **local minimum**.

Value of the function:

$$
f(2)=3(2)^2-12(2)+7
$$

$$
=12-24+7
$$

$$
=-5
$$

Minimum point:

$$
(2,-5)
$$

---

# **7. Logic Problem (Fly and Bicycle)**

Distance to wall:

$$
10,m
$$

Bicycle speed:

$$
1,m/s
$$

Time until bicycle reaches wall:

$$
t=\frac{distance}{speed}
$$

$$
t=\frac{10}{1}
$$

$$
t=10;seconds
$$

Fly speed:

$$
2,m/s
$$

Total fly distance:

$$
d = vt
$$

$$
d = 2 \times 10
$$

$$
d = 20,m
$$

The fly travels **20 meters** before the bicycle reaches the wall.

---

# **8. Definite Integrals**

Calculate:

$$
\int_0^\pi \sin(x),dx
$$

Integral of sine:

$$
\int \sin x,dx = -\cos x
$$

Evaluate:

$$
[-\cos x]_0^\pi
$$

$$
= -\cos(\pi) - (-\cos(0))
$$

$$
= -(-1) - (-1)
$$

$$
= 2
$$

Area:

$$
2
$$

---

# **9. Optimization Problem**

Curve:

$$
y = 3 - x^2
$$

Rectangle area:

$$
A = x \cdot y
$$

Substitute (y):

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

Derivative:

$$
A'(x) = 3 - 3x^2
$$

Set to zero:

$$
3 - 3x^2 = 0
$$

$$
x^2 = 1
$$

$$
x = 1
$$

Height:

$$
y = 3 - (1)^2
$$

$$
y = 2
$$

Maximum rectangle dimensions:

$$
x=1, \quad y=2
$$

---

# **10. Infinite Series**

Movement pattern:

* (1) m east
* (1/2) m north
* (1/3) m west
* (1/4) m south
* (1/5) m east

---

### Horizontal displacement

Series:

$$
1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This equals:

$$
\arctan(1)
$$

$$
=\frac{\pi}{4}
$$

---

### Vertical displacement

Series:

$$
\frac12 - \frac14 + \frac16 - \frac18 + \dots
$$

Factor out (1/2):

$$
\frac12 \left(1-\frac12+\frac13-\frac14+\dots\right)
$$

This equals:

$$
\frac12 \ln(2)
$$

---

### Final Position

$$
\left(\frac{\pi}{4}, \frac{\ln 2}{2}\right)
$$


