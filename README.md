# Velocity-Pressure-contours-of-a-moving-lid
CFD simulations using ANSYS Fluent 2025 R2 Student Edition. Includes residual plots, static pressure contours, and convergence analysis for different flow setups. Documenting solver behavior, boundary conditions, and results as part of an aerodynamics learning portfolio.
# CFD Simulation: ANSYS Fluent 2025 R2

This repository documents a CFD case study performed using ANSYS Fluent (Student Edition).  
The focus is on solver convergence and static pressure distribution for a 2D flow domain.

---

## 📂 Contents
- Residual plots showing solver convergence
- Static pressure contour visualizations
- Notes on boundary conditions and velocity adjustments

---

## ⚙️ Setup
- **Software:** ANSYS Fluent 2025 R2 Student Edition  
- **Domain:** 2D square domain  
- **Boundary Conditions:** Inlet velocity adjusted for stable convergence  
- **Solver:** Pressure-based, steady-state  

---

## 📊 Results
### Residuals
![Residuals Plot](residuals.png)  
Residuals for continuity, x-velocity, and y-velocity dropped several orders of magnitude, indicating full convergence.

### Static Pressure Contours
![Pressure Contours](pressure_contours.png)  
Low-pressure regions appear in the central domain, with higher pressure near boundaries, consistent with expected flow behavior.

---

## 🔍 Learnings
- Adjusting inlet velocity improved solver stability and allowed continuity residuals to converge.  
- Residual monitoring is essential to confirm mass balance and momentum conservation.  
- Pressure contours provide qualitative insight into flow distribution and boundary effects.  

---

## 🎯 Purpose
This project is part of a learning portfolio in aerodynamics and fluid mechanics, documenting simulation setups, convergence strategies, and results for future aerospace applications.
