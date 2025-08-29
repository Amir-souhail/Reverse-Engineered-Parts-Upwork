Ah! I see the issue. GitHub Markdown **doesn’t center standard Markdown lists** even if you wrap them in `<div align="center">`. To truly center bullet points, you need to **use HTML `<ul>` or `<ol>` and apply `style="text-align:center"`** to the `<li>` items.

Here’s a corrected version where the bullets are actually centered:

---

<div align="center">

# Reverse-Engineered Projects & Parts

This repository contains my collection of **reverse-engineered parts and projects** created in **SOLIDWORKS**.
Each project starts from a **2D technical drawing sourced online**, which I then use to:

<ul style="list-style-type: disc; text-align: center; padding-left: 0;">
<li>Recreate an accurate <b>3D CAD model</b>.</li>
<li>Regenerate the <b>2D engineering drawing</b> based on my 3D model.</li>
<li>(When applicable) Build complete <b>assemblies</b>.</li>
</ul>

---

## 📌 Purpose

<ul style="list-style-type: disc; text-align: center; padding-left: 0;">
<li>Strengthen my skills in <b>3D CAD modeling</b> and <b>technical drawing recreation</b>.</li>
<li>Develop a personal library of <b>reverse-engineered components and assemblies</b>.</li>
<li>Practice generating <b>engineering drawings</b> from models.</li>
<li>Document my workflow and methodology as part of my learning journey.</li>
</ul>

---

## 🛠️ Tools & Software

<ul style="list-style-type: disc; text-align: center; padding-left: 0;">
<li><b>SOLIDWORKS</b> – For part, assembly, and drawing creation.</li>
<li><b>STEP/IGES Exports</b> – For compatibility and sharing.</li>
<li><b>Technical Drawings (sourced online)</b> – Used as references for reconstruction.</li>
</ul>

---

## 📖 Workflow

<ol style="text-align: center; padding-left: 0;">
<li>Collect <b>2D drawings</b> from publicly available references.</li>
<li>Recreate the <b>3D CAD model</b> in SOLIDWORKS.</li>
<li><b>Regenerate the 2D drawing</b> from the 3D model, matching the original as closely as possible.</li>
<li>Export parts, assemblies, and drawings in <b>neutral CAD formats</b> for sharing.</li>
<li>Document assumptions, sources, and challenges for each project.</li>
</ol>

---

## 🖼️ Gallery

A showcase of selected reverse-engineered models and assemblies.

**Gear Box Housing**

<img src="Gearbox Housing Cover Plate/Gearbox Housing Cover Plate.JPG" alt="Gearbox Housing Cover Plate" width="300"/>

---

## ⚠️ Disclaimer

<ul style="list-style-type: disc; text-align: center; padding-left: 0;">
<li>All models and drawings are created <b>for educational and practice purposes only</b>.</li>
<li>Source drawings are taken from freely available references on the internet.</li>
<li>No proprietary or confidential designs are included.</li>
</ul>

---

## 🚀 Future Scope

<ul style="list-style-type: disc; text-align: center; padding-left: 0;">
<li>Expand with more <b>mechanical parts, assemblies, and detailed drawings</b>.</li>
<li>Organize projects by <b>categories and complexity</b>.</li>
<li>Explore reverse engineering from <b>real-world references (photos, videos, or measurements)</b> in addition to 2D drawings.</li>
</ul>

</div>  

---

If you want, I can **also update the gallery section to display multiple images in a row**—so it looks like a proper grid of projects on GitHub. This makes the README look much more professional. Do you want me to do that next?
