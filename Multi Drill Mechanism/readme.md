# Multi Drill Mechanism (Reverse Engineered)

This project is a **reverse-engineering reproduction** of a compact, gear-driven head that rotates **four M8 drill spindles** in parallel. The design was studied from an online source and recreated in CAD with full assembly details and a BOM for reference.

> **Theme:** Reverse Engineering — the mechanism was analyzed, reconstructed, and documented for learning and design practice.
> **Sources:** The original rotating video was taken from [Pinterest](https://it.pinterest.com/pin/691161874100365576/) and the PDF drawing was recreated based on it.

---

## Contents

* `Multi Drill Mechanism.pdf` — Reverse-engineered assembly drawing with BOM and orthographic views. Scale noted as **3:1** on **Sheet 1 of 1**.
* `Multi Drill Mechanism Rotating.mp4` — Reverse-engineered rotating preview of the assembled unit (for quick orientation).

---

## Overview

The mechanism mounts **four M8 drill bits** symmetrically and drives them via a central hub and gear/link interface. It’s intended as a compact multi-spindle solution for simultaneous drilling operations on a fixed pitch. This version was **reproduced through reverse engineering** for study and prototyping purposes.

---

## Bill of Materials (from the drawing)

| Item | Part Number / Spec        | Qty | Notes                                           |
| ---: | ------------------------- | --: | ----------------------------------------------- |
|    1 | PART1                     |   1 | Base/central body                               |
|    2 | PART2                     |   1 | **Rotating element that drives the drills**     |
|    3 | ISO 4162 — M6 × 20 × 20–N |   2 | Hexagon flange screws per ISO 4162              |
|    4 | PART11                    |   1 | Main shaft / central transmission               |
|    5 | PART6                     |   1 | Secondary body/cover                            |
|    6 | PART7                     |   1 | **Linked with the main shaft (PART11)**         |
|    7 | PART3                     |   4 | Spindle carriers (x4)                           |
|    8 | PART4                     |   4 | Couplers or caps (x4)                           |
|    9 | **M8 Drill**              |   4 | Working tools; not included as fabricated parts |
|   10 | PART9                     |   4 | Bushings/spacers (x4)                           |
|   11 | ISO 2338 — 6 M6 × 16 — ST |   1 | Dowel/parallel pin for alignment                |
|   12 | ISO 4762 — M3 × 8 — 8N    |   4 | Socket head cap screws                          |

---

## How it Works (at a glance)

* **PART2** is the rotating element responsible for driving the drills.
* **PART7** is connected to the **main shaft (PART11)**, transmitting motion from the input to the rotating assembly.
* Motion from the central shaft is evenly distributed to the four spindles.
* The body (PART1/PART6) ensures synchronous drilling on a fixed pattern.

This function was deduced through **reverse engineering** by observing the mechanism video and reconstructing the part relationships.

---

## Assembly Notes

1. **Prepare the Body:** Assemble **PART1** with **PART6**, keeping datum alignment consistent with the drawing views.
2. **Install Alignment Pin:** Fit the **ISO 2338 M6×16 pin** to lock key features before fastening.
3. **Fit the Transmission:** Install **PART7** linked with **PART11**, then position **PART2** as the rotating element for the drills; verify free rotation.
4. **Build Spindles (×4):** Stack **PART3 / PART9 / PART4** and secure with the specified **ISO 4762 M3×8** screws. Insert **M8 drills** last.
5. **Final Fasteners:** Use the **ISO 4162 M6×20×20–N** flange screws to close up the assembly.

---

## CAD & Simulation

* **CAD:** Entire assembly was recreated in SOLIDWORKS based on reverse-engineered geometry. Mates were added to simulate gear-driven motion, consistent with the original video.
* **FEA:** Recommended for stiffness checks: fix the body (PART1), apply axial drilling loads at spindle tips, and evaluate deflection and shear on the pin and fasteners.

---

## Manufacturing & 3D Printing

* **Critical fits:** Spindle components (**PART3/9/4**) need precise tolerances; bushings can be press-fit.
* **Material hints:** PA-CF / PETG-CF for 3D printed prototypes; Al 6061/7075 or steel for production.
* **Tolerances:** No explicit tolerances were provided; assumptions were made during the reverse-engineering process.

---

## Using the Mechanism

1. **Mount the head** securely to your fixture.
2. **Insert four M8 drills** equally.
3. **Spin test** at low RPM, check vibration.
4. Increase speed/feed conservatively.

---

## Attribution & License

* **Video Source:** [Pinterest link](https://it.pinterest.com/pin/691161874100365576/) — basis for reverse engineering.
* **Drawing & CAD:** Reverse engineered and reproduced for educational and prototyping purposes.

If you publish or share derivatives, clearly state that this is a **reverse-engineered reproduction** and retain credit to the original source.

---

## Changelog

* **v1.0** — Initial reverse-engineered drawing and video reproduction.
* **v1.1** — Clarified roles of PART2 and PART7 in the motion system.
* **v1.2** — Highlighted reverse engineering theme and origin of source video.

---

## Contact

Questions, improvements, or CAD contributions? Open an issue or PR. This project is a **reverse-engineering study** and not an official release from the original author/company.
