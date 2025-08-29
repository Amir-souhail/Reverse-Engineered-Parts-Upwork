# Gearbox Housing Cover Plate (Reverse Engineering Project)

## 📌 Project Overview
This project is a **reverse engineered 3D CAD model** of a **Gearbox Housing Cover Plate**.  
The original **2D technical drawing** was taken from publicly available sources, and the 3D model was completely regenerated from scratch using **SolidWorks**.  

The main theme of this project is **Reverse Engineering** – converting incomplete or reference 2D documentation into a functional and fully defined 3D CAD part.

---

## 🛠️ Description of the Part
The **Gearbox Housing Cover Plate** is a structural component used in mechanical assemblies such as gearboxes, pumps, or compressors. Its primary roles include:  
- Supporting **bearings and shafts** through precision holes (H6/J6 fits).  
- Serving as a **cover plate** to seal one side of a gearbox or machinery housing.  
- Ensuring **shaft alignment** and structural stability of gears or rotating components.  
- Allowing **bolted mounting** to the main body through distributed holes.  
- Providing **oil flow channels and recesses** for lubrication.  

---

## 🔧 Key Features
- **Bearing seats (Ø30 H6, Ø53 J6, Ø45, Ø70)** → For supporting and aligning gear shafts.  
- **Perimeter mounting holes (Ø12, M6 threaded)** → For securing the plate to a gearbox body.  
- **Multiple cutouts and recesses** → For weight reduction and clearance for gears.  
- **Oil grooves & cavity sections** → Indicate use in lubricated systems such as gearboxes.  

---

## 📐 Suggested Materials
The part is typically made from materials that balance **strength, wear resistance, and machinability**:  
- **Cast Iron (GG25 / EN-GJL-250)** → Common in gearbox housings for vibration damping.  
- **Aluminum Alloys (e.g., Al 6061, Al 7075)** → Lightweight option, good for automotive/robotics applications.  
- **Mild Steel (e.g., C45, EN8)** → For higher load-bearing and durability requirements.  

---

## ⚙️ Possible Applications
- Gearbox assemblies (industrial machinery, automotive).  
- Pump housing covers (oil pumps, compressors).  
- Motor mounting or end plates.  
- Any **machinery requiring precise shaft and bearing alignment**.  

---

## 📊 Reverse Engineering Theme
This project emphasizes **reverse engineering** by:  
- Extracting design intent from **2D drawings**.  
- Reconstructing a **parametric 3D model** in SolidWorks.  
- Ensuring **assembly feasibility** through dimensional tolerances (H6/J6 fits).  
- Preparing the part for **future modifications, 3D printing, or CNC machining**.  

---

## 📚 Engineering Formulas Relevant to the Design

### 1. **Bolt Preload (Clamping Force)**
\[
F = \frac{T}{K \cdot d}
\]
Where:  
- \( F \) = Preload force (N)  
- \( T \) = Applied torque (N·m)  
- \( K \) = Torque coefficient (~0.2 for steel bolts)  
- \( d \) = Nominal bolt diameter (m)  

---

### 2. **Bearing Life (L10)**
\[
L_{10} = \left(\frac{C}{P}\right)^p \cdot 10^6 \text{ revolutions}
\]
Where:  
- \( L_{10} \) = Bearing life (revolutions at 90% reliability)  
- \( C \) = Dynamic load rating (N)  
- \( P \) = Equivalent dynamic bearing load (N)  
- \( p \) = 3 (ball bearings), 10/3 (roller bearings)  

---

### 3. **Bending Stress in Plate**
\[
\sigma = \frac{M \cdot y}{I}
\]
Where:  
- \( \sigma \) = Bending stress (MPa)  
- \( M \) = Applied moment (N·mm)  
- \( y \) = Distance from neutral axis (mm)  
- \( I \) = Moment of inertia of the section (mm⁴)  

---

### 4. **Safety Factor (FS)**
\[
FS = \frac{\sigma_{yield}}{\sigma_{working}}
\]
Where:  
- \( \sigma_{yield} \) = Yield strength of material (MPa)  
- \( \sigma_{working} \) = Actual stress in operation (MPa)  

---

### 5. **Shear Stress on Bolts**
\[
\tau = \frac{F}{A}
\]
Where:  
- \( \tau \) = Shear stress (MPa)  
- \( F \) = Applied shear force (N)  
- \( A \) = Cross-sectional area of bolt (mm²)  

---

## 📂 Project Files
- **3D CAD Model (SolidWorks)**  
- **Technical Drawing (2D to 3D regeneration)**  
- **PDF Documentation**  

---

## 👤 Author
**Amir Souhail**  
Research and Development Engineer  
Autonomous Underwater Vehicle – La Spezia, Italy  
📧 amir.souhail@gmail.com  

---
