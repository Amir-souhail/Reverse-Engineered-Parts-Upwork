

# Reverse-Engineered Part: Mount Plate

This project contains my **reverse-engineered CAD model** of a **Mount Plate**, created in **SOLIDWORKS 2025**.  
The original design is the **property of Prad Equipments Pvt Ltd**.  
I have **recreated the 3D model and 2D drawing** purely for **educational and portfolio purposes**.

---

## 📌 Part Overview

The **Mount Plate** is a sheet metal structural component used to **support and secure cylindrical elements** such as motors, bearings, or shafts.  
It is designed with a bent **L-shaped profile** for stability, providing a strong mounting base while keeping the assembly compact.

### 🔎 Key Characteristics:
- **Central Circular Cutout (Ø94 mm)** → For holding a cylindrical component such as a **motor housing or bearing**.  
- **Two Through Holes (Ø10 mm)** → For fasteners that secure the mounted component.  
- **Slotted Holes on the Base** → Allow for **adjustable mounting**, enabling flexibility during alignment.  
- **L-Bend Geometry** → Provides rigidity and allows vertical components to be fixed onto a flat surface.  
- **Fillets & Rounded Edges** → Reduce stress concentration and improve manufacturability.  

---

## ⚠️ Key Challenge: K-Factor & Dimensional Mismatch

One tricky aspect of this drawing is that the **K-Factor (bend allowance)** was **not defined**.  
This omission created a mismatch between the **front view dimensions** and the **flat pattern dimensions** when modeled in SOLIDWORKS.

- **SOLIDWORKS default K-Factor = 0.5** (neutral axis at mid-thickness).  
- **Actual requirement = 0.33**.  
- With the default value, the developed flat length and folded dimensions **did not add up correctly**.  
- Once adjusted to **K-Factor = 0.33**, the flat pattern and front view dimensions matched the drawing.  

👉 This case highlights the importance of explicitly specifying **bend allowance/K-Factor** in technical drawings to ensure correct flat patterns during manufacturing.  

---

## 🛠️ Tools & Workflow

1. Start from the **2D reference drawing** (property of Prad Equipments Pvt Ltd).  
2. Recreate the **3D CAD model** in SOLIDWORKS using sheet metal features.  
3. Apply **cutouts, slots, and bends** as per the drawing.  
4. Adjust **K-Factor** to 0.33 to match drawing intent.  
5. Regenerate the **2D drawing** from the 3D model.  
6. Document assumptions and note dimensional ambiguities.  

---


## 📂 Files in This Folder

This folder contains multiple formats of the **Mount Plate** model and drawings for compatibility and sharing:

- **Mount_Plate.SLDPRT** → SOLIDWORKS part file (native CAD model).  
- **Mount_Plate.SLDDRW** → SOLIDWORKS 2D drawing file.  
- **Mount_Plate.PDF** → PDF export of the 2D drawing for easy viewing.  
- **Mount_Plate.STEP** → Neutral CAD format for sharing across CAD software.  
- **Mount_Plate.DXF** → Flat pattern export for sheet metal manufacturing (laser/waterjet cutting).  
- **Mount_Plate.STL** → Mesh format for 3D printing or quick visualization.  

---




## 🏷️ Ownership & Attribution

- The original **Mount Plate design** is the **property of Prad Equipments Pvt Ltd**.  
- This reverse-engineered version was created **only for educational and portfolio purposes**.  
- No commercial use or redistribution is intended.  

---

⚠️ **Disclaimer:**  
This project does not contain any proprietary information.  
It is a **recreation based on a publicly shared job drawing** and is included here solely to demonstrate my **CAD modeling and reverse engineering skills**.  

---

## 🚀 Future Scope

* Perform **finite element analysis (FEA)** to test load capacity.  
* Compare results of **different K-Factors and bend allowances**.  
* Extend this into an **assembly project** with the mounted component.  
* Document a general **best-practice workflow for sheet metal parts**.  



Do you also want me to **include a small table in the README** showing the **dimension mismatch with K=0.5 vs corrected K=0.33**? That would make the problem (and your solution) very clear to recruiters/clients.
