
## 1. Upsetting Presses (The "Upsetter")
An upsetting press (Horizontal Forging Machine) is a specialized mechanical power press designed to provide a two-stage motion: **clamping** the workpiece and **heading** (deforming) the material.



### A. Kinematic Drive System
Unlike standard vertical presses, an upsetter operates on a synchronized dual-slide system:
* **The Main Slide (Heading Slide):** Moves horizontally to provide the primary forging blow.
* **The Side Slide (Grip Slide):** Moves perpendicular to the main slide to lock the bar stock in place.
* **Synchronization:** These slides are mechanically linked via a single crankshaft. The grip slide must reach "full lock" (clamping position) before the heading tool makes contact with the workpiece to prevent axial slippage.

### B. Tonnage Distribution and Force Logic
The machine must balance two distinct forces to maintain part quality:
1. **Clamping Force (Fc):** The force required to hold the bar.
2. **Upsetting Force (Fu):** The force required to deform the metal.

> **Rule of Thumb:** To ensure process stability, the machine is engineered so that Fc is approximately **20–30% higher** than Fu. 
> 
> **Failure Mode:** If Fu > Fc, the dies will "gape" (separate slightly), causing "flash" (excess metal leakage) and dimensional inaccuracy.

### C. The Energy Theory (Flywheel Drive)
Most upsetting presses utilize a mechanical **Crank-Drive** system:
* **Energy Storage:** Energy is stored in a massive rotating flywheel according to the formula: 
  $$E = \frac{1}{2} I \omega^2$$
* **Load Application:** Upon engagement of the clutch, kinetic energy is converted into a high-impact load. This high strain rate is ideal for filling complex die cavities before the workpiece cools.

---

## 2. Extrusion Presses
Extrusion press theory is based on the **High-Pressure Vessel principle** and **Controlled Displacement**.



### A. Hydraulic Power and Flow Control
Extrusion requires a sustained, long-stroke force, making **Hydraulic Systems** the industrial standard:
* **Constant Velocity:** To maintain consistent metallurgical properties and surface finish, the ram must maintain a constant speed .
* **Pressure Management:** The system must overcome the **Breakout Pressure** (initial peak force to start flow) and then transition to a lower **Running Pressure** as the billet length decreases.

### B. Pre-Stressed Container Theory
The container must withstand internal radial pressures that exceed the tensile strength of standard tool steel.
* **Multi-Layer Construction:** Containers use **Shrink-fitting theory**. An outer "mantle" is heated, slipped over an inner "liner," and cooled.
* **Pre-compression:** This creates a pre-compressive stress on the liner. During extrusion, internal pressure "unloads" this pre-compression rather than putting the steel into tension, significantly extending tool life and preventing catastrophic failure.

### C. The "Stiff-Frame" (Tie-Rod Theory)
To manage forces ranging from **500 to 10,000 tons**, the press frame must be exceptionally rigid.
* **Tie-Rod Construction:** Four massive, pre-stressed tie-rods connect the **Platen** (die end) to the **Main Cylinder** (power end).
* **Elastic Stretching:** The frame must resist stretching. Excessive elastic deformation leads to misalignment, resulting in "eccentric" or lopsided profiles.

---

## 3. Critical Comparison of presses

| Feature | Upsetting Press Theory | Extrusion Press Theory |
| :--- | :--- | :--- |
| **Drive System** | Mechanical (Flywheel/Crank) | Hydraulic (Pumps/Accumulators) |
| **Motion Type** | High-speed impact (Cycle-based) | Slow, steady displacement (Stroke-based) |
| **Force Logic** | Clamping Force > Heading Force | Ram Pressure > Material Flow Stress |
| **Tooling Stress** | Repeated Thermal Shock & Impact | Constant High Pressure & Friction |
| **Orientation** | Primarily Horizontal | Horizontal (Standard) or Vertical |

