# Gyro-Surface-

### **What is the Gyro Surface in Your Code?**
The **Gyro Surface** in your code is a 3D parametric surface created using `THREE.ParametricGeometry`. A **parametric surface** is a mathematical surface defined by a set of parametric equations, where the position of each point on the surface is given by a function of two parameters, \( u \) and \( v \).

Your code defines the **Gyro Surface** with the following equation:

\[
r = \cos(2u)
\]

\[
x = r \cdot \sin(0.5u) \cdot \cos(3u)
\]

\[
y = r \cdot \sin(0.5u) \cdot \sin(3v)
\]

\[
z = r \cdot \cos(0.5u)
\]

where \( u \) and \( v \) range from \( 0 \) to \( 2\pi \). This means that each point on the surface is determined by **trigonometric functions** that control its shape and curvature.

---

### **Explanation of the Parametric Equations**
1. **\( r = cos(2u) \):**  
   - This determines a radius \( r \) that oscillates between \(-1\) and \(1\), shaping the overall structure of the surface.
   
2. **\( x = r • sin(0.5u) • cos(3u) \):**  
   - The **\( sin(0.5u) \)** factor controls the stretching of the surface.
   - The **\( cos(3u) \)** creates a periodic pattern along the \( x \)-axis, forming twists or ripples.

3. **\( y = r • sin(0.5u) • sin(3v) \):**  
   - Similar to \( x \), but it uses **\( sin(3v) \)** instead of \( cos(3u) \), adding a swirling or twisting motion in the \( y \)-direction.

4. **\( z = r • cos(0.5u) \):**  
   - Defines the height variation of the surface, contributing to its **wave-like** appearance.

---

### **Visual Effect of These Equations**
- The use of **sine and cosine** functions introduces a **wave-like motion** in the surface.
- The factor **\( cos(3u) \) and \( sin(3v) \)** causes **twisting** and **looping** patterns.
- The **\( r = cos(2u) \)** term modulates the radius, creating variations in how the surface expands and contracts.
