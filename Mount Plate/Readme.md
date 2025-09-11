

# Reverse-Engineered Projects & Parts

This repository contains my collection of **reverse-engineered parts and projects** created in **SOLIDWORKS 2025**.  
Each project starts from a **2D technical drawing** (sourced online or from a job reference), which I then use to:

* Recreate an accurate **3D CAD model**.  
* Regenerate the **2D engineering drawing** based on my 3D model.  
* (When applicable) Build complete **assemblies**.  

---

## 📌 Purpose

* Strengthen my skills in **3D CAD modeling** and **technical drawing recreation**.  
* Develop a personal library of **reverse-engineered components and assemblies**.  
* Practice generating **engineering drawings** from models.  
* Document my workflow and methodology as part of my learning journey.  

---

## 🛠️ Tools & Workflow

1. Collect **2D drawings** (publicly available or company references).  
2. Recreate the **3D CAD model** in SOLIDWORKS.  
3. **Regenerate the 2D drawing** from the 3D model.  
4. Export parts, assemblies, and drawings in **neutral CAD formats**.  
5. Document assumptions, challenges, and references for each project.  

---

## 🖼️ Gallery of Projects

### 🔹 Gearbox Housing Cover Plate  
- Based on a **public exercise drawing**.  
- Reverse-engineered to recreate the part geometry and 2D drawings.  

<img src="Gearbox Housing Cover Plate/Gearbox Housing Cover Plate.JPG" alt="Gearbox Housing Cover Plate" width="300"/>

---

### 🔹 Support Arm / Bracket  
- Based on a **public technical drawing**.  
- A **triangular structural arm** with ribs and multiple holes for shafts/pivots.  
- Likely used as a **lever arm or support bracket** in machinery.  

<img src="Support Arm Bracket/Support_Arm_Bracket.JPG" alt="Support Arm Bracket" width="300"/>

---

### 🔹 Mount Plate  
- Original design is the **property of Prad Equipments Pvt Ltd** (sourced from an Upwork job post).  
- Reverse-engineered in **SOLIDWORKS sheet metal** for educational purposes.  

#### ⚠️ Key Challenge: K-Factor Ambiguity
One tricky aspect of this drawing is that the **K-Factor (bend allowance)** was **not defined**.  
This caused a mismatch between the **front view dimensions** and the **flat pattern dimensions** when modeled in SOLIDWORKS.  

- **SOLIDWORKS default K-Factor = 0.5** (neutral axis at mid-thickness).  
- **Actual drawing requirement = 0.33**.  
- Because of this difference, the **developed flat length** and the **folded front view length** did not add up until the correct **K-Factor (0.33)** was applied.  

👉 This highlights the importance of explicitly specifying **bend allowance/K-Factor** in technical drawings to avoid confusion during manufacturing or reverse engineering.  

<img src="Mount Plate/Mount_Plate.JPG" alt="Mount Plate" width="300"/>

---

## 🏷️ Ownership & Attribution

This repository contains a mix of **reverse-engineered models from public drawings** and **models recreated from company-owned references**.  
All work is done solely for **educational, portfolio, and skill development purposes**.  

### 🔹 Educational References
- **Gearbox Housing Cover Plate** → Based on a publicly available exercise drawing.  
- **Support Arm / Bracket** → Based on a publicly available technical drawing.  

### 🔹 Company-Owned References
- **Mount Plate** → Original design is the **property of Prad Equipments Pvt Ltd**.  
  - My recreation is **for portfolio purposes only** and not intended for commercial use.  

---

⚠️ **Disclaimer:**  
No proprietary or confidential information is shared in this repository.  
All models here are either recreated from **publicly available sources** or are **company-owned references credited to their rightful owners**.  
This repository is strictly for **personal learning and showcasing CAD skills**.  

---

## 🚀 Future Scope

* Expand with more **mechanical parts, assemblies, and detailed drawings**.  
* Organize projects by **categories and complexity**.  
* Explore reverse engineering from **real-world references (photos, videos, or measurements)** in addition to 2D drawings.  
* Add **FEA and motion studies** for selected parts.  
* Perform **K-Factor comparison studies** to demonstrate sheet metal design accuracy.  

