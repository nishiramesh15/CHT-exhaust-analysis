
# Simulation Portfolio – Nishaanth R

**M.Tech Design Engineering | FEA & CFD Simulation Engineer**  
Creo • ANSYS • SolidWorks  
[LinkedIn](https://linkedin.com/in/nishaanthramesh) | Nishiramesh15@gmail.com  

---

## 🔧 Project: CHT Analysis on Exhaust Port

### **Objective:**
1. Understand why and where a CHT (Conjugate Heat Transfer) analysis is used.
2. Maintain the y+ value according to the turbulence model and justify the results.
3. Calculate the wall/surface heat transfer coefficient on the internal solid surface and show velocity & temperature contours in appropriate areas.
4. Determine how to verify if the HTC (Heat Transfer Coefficient) predictions from the simulations are accurate and what factors affect prediction accuracy.

### **Tools Used:** ANSYS Fluent, SolidWorks

### **Steps Taken:**
- Imported CAD model and defined fluid domain.
- Meshed the geometry with refinement near the valve seat.
- Set boundary conditions: inlet velocity and outlet pressure.
- Solved using k-epsilon turbulence model and transient solver.

### **Factors Affecting Simulation Accuracy:**
- SHARE TOPOLOGY quality affects heat transfer smoothness between regions.
- INFLATION LAYER improves mesh quality for refined results.
- Proper selection of TURBULENCE model and Y+ values.
- CHT involves interaction between conduction in solids and convection from the surface to fluid.

### **Results:**
- Increased elements result in higher velocity, temperature, and wall heat transfer coefficients.
- High HTC at junction due to increased velocity from fluid to solid.
- Velocity increases from inlet to outlet due to mass conservation and mixing of air.
- Higher velocity leads to higher Reynolds number and increased heat transfer.
- CHT analysis helps predict component behavior accurately before physical testing.

### **HTC Prediction from Simulation:**
Nusselt Number (Nu) formula:  
**Nu = hL/k**  
Where:  
- **Nu** – Nusselt Number  
- **h** – Heat Transfer Coefficient  
- **L** – Characteristic Length  
- **k** – Thermal Conductivity  

=> HTC is directly proportional to flow velocity. Maximum HTC is expected near the outlet. Simulation results confirm this prediction.

### **Screenshots:**  
*(Insert simulation visuals here: mesh, temperature contours, velocity vectors, etc.)*
