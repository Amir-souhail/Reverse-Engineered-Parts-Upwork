# Gearbox Housing Cover Plate (Reverse Engineering Project)

## 📌 Project Overview
This repository contains a **reverse-engineered 3D CAD model** of a **Gearbox Housing Cover Plate**.  
A publicly available **2D drawing** was used as reference, and the entire 3D geometry was **rebuilt from scratch** in SolidWorks to capture design intent, tolerances, and manufacturability.

**Theme:** *Reverse Engineering* — turning incomplete or reference 2D documentation into a fully defined parametric 3D model.

---

## 🛠️ Part Description
A structural cover used in gearboxes/pumps to:
- Support and align **shafts/bearings** via precision bores (e.g., H6/J6 fits).
- Seal a housing face and maintain internal **lubrication**.
- Provide **bolt-down** mounting and stiffness with ribs/pockets.
- Offer **clearance** for rotating elements via recessed cavities and channels.

---

## 🔧 Key Features
- Precision bearing seats: **Ø30 H6**, **Ø53 J6**, **Ø45**, **Ø70**.
- Through and threaded mounting holes (e.g., **Ø12**, **M6**).
- Weight-relief pockets, oil grooves, and sealing land.
- Perimeter geometry tailored for gasket/RTV sealing.

---

## 🧱 Suggested Materials
- **Cast Iron (EN-GJL-250 / GG25):** excellent damping; classic gearbox material.  
- **Aluminum (6061-T6 / 7075-T6):** light, corrosion resistant; good for weight-critical builds.  
- **Medium Carbon Steel (C45 / EN8):** strong and machinable for rugged service.

---

## 🚜 Typical Applications
- Industrial gearboxes, reducers, and pump housings.  
- Compressor/motor end plates requiring accurate shaft alignment.  
- General machinery covers with integrated bearing bores.

---

## 🔁 Reverse Engineering Notes
- Derived all **parametric dimensions** from the 2D drawing.  
- Recreated **datums**, **fits** (H6/J6), and **pattern features**.  
- Produced a model suitable for **CNC**, **casting**, or **3D printing**.  
- Verified design with basic **stress/fit checks** (see formulas below).

---

## 📚 Engineering Formulas (GitHub-friendly LaTeX)

### 1) Bolt Preload (clamping force)
$$
F=\frac{T}{K\,d}
$$
- $F$ — preload force (N)  
- $T$ — tightening torque (N·m)  
- $K$ — nut/bolt torque factor (≈ 0.18–0.25 for lubricated steel)  
- $d$ — nominal bolt diameter (m)

### 2) Bearing Life (basic rating life, $L_{10}$)
$$
L_{10}=\left(\frac{C}{P}\right)^{p}\cdot10^{6}
$$
- $L_{10}$ — life (revolutions, 90% reliability)  
- $C$ — bearing dynamic rating (N)  
- $P$ — equivalent dynamic load (N)  
- $p=3$ (ball), $p=10/3$ (roller)

### 3) Bending stress in the plate
$$
\sigma=\frac{M\,y}{I}
$$
- $\sigma$ — bending stress (MPa)  
- $M$ — bending moment (N·mm)  
- $y$ — distance from neutral axis (mm)  
- $I$ — second moment of area (mm$^{4}$)

### 4) Safety factor
$$
FS=\frac{\sigma_{y}}{\sigma_{w}}
$$
- $\sigma_{y}$ — yield strength of material (MPa)  
- $\sigma_{w}$ — working (computed) stress (MPa)

### 5) Shear stress on bolts/pins
$$
\tau=\frac{F}{A}
$$
- $\tau$ — shear stress (MPa)  
- $F$ — applied shear force (N)  
- $A$ — resisting area (mm$^{2}$)

### 6) True position of a hole (GD\&T)
$$
\text{TP}=2\sqrt{(\Delta x)^{2}+(\Delta y)^{2}}
$$
- $\text{TP}$ — true position tolerance diameter (mm)

### 7) Clearance / interference (fit check)
$$
C = D_{\text{hole}}-d_{\text{shaft}}
$$
- $C>0$ — clearance fit, \; $C<0$ — interference fit

---

## 📂 What’s Included
- SolidWorks 3D model (parametric).  
- Drawing/PDF for documentation.  
- This README with on-page, GitHub-rendered formulas.

---

## 👤 Author
**Amir Souhail**  
Research & Development Engineer, AUV — La Spezia, Italy  
📧 amir.souhail@gmail.com
