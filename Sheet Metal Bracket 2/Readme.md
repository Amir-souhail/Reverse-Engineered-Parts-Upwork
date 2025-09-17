
# Sheet Metal Bracket Design

This repository contains all the CAD files for a **sheet metal bracket**. The project demonstrates a complete design and documentation workflow, from 3D modeling to the creation of a flat pattern and detailed 2D drawings. This is a practical example of a **sheet metal fabrication** project suitable for a portfolio.

### Project Files

The following files are included in this repository:

* **`sheet_metal_bracket.SLDPRT`**: The native SolidWorks part file. This file is fully parametric, allowing for easy modification of dimensions and features.
* **`sheet_metal_bracket.SLDDRW`**: The native SolidWorks drawing file. This contains the detailed 2D documentation, including the folded views, flat pattern, and all necessary dimensions.
* **`sheet_metal_bracket.PDF`**: A universal PDF version of the 2D drawing. This is ideal for sharing with manufacturers or for viewing without SolidWorks.
* **`sheet_metal_bracket.STEP`**: A universal 3D file format for importing the model into other CAD software.
* **`sheet_metal_bracket.STL`**: A mesh file, commonly used for 3D printing.
* **`sheet_metal_bracket.DXF`**: A 2D flat pattern file, specifically for laser cutting, waterjet cutting, or CNC punching. This is the crucial file for fabrication.

***

### Design Details & Fabrication Methods

The bracket was designed with manufacturing in mind, specifically for sheet metal processes. The design includes:

* **Precise Bends**: The model includes specific bend radii and angles (`180° R5` and `30° R4`), which are crucial for accurate forming. The bending process would typically be done using a **press brake**.
* **Flat Pattern**: The most important aspect of a sheet metal part is the **flat pattern**, which is used to cut the initial blank. A flat pattern view is included in the drawing with critical dimensions like `148.85` mm, ensuring it's ready for a fabrication shop. The most common methods for cutting the flat pattern are **laser cutting** or **CNC punching**. .
* **Tolerances and Notes**: All dimensions and notes are clearly defined to prevent errors during manufacturing.
* **Isometric View**: A 3D isometric view is provided for easy visualization of the final product.

***

### How to Use

* For **viewing and documentation**, use the `.PDF` file.
* For **manufacturing**, the `.DXF` file is the primary file for the flat pattern, while the `.PDF` drawing provides the bending instructions and final dimensions.
* For **further design work** or analysis, use the native SolidWorks files (`.SLDPRT` and `.SLDDRW`) or the `.STEP` file.

This project is an excellent example of a complete sheet metal design and is a testament to my skills in **SolidWorks**, **2D technical drawing**, and **manufacturing for sheet metal**.
