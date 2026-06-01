# Comprehensive Thermal System Design & HVAC Installation Project

An end-to-end mechanical engineering project focusing on the thermal system design, heat loss analysis, and hydronic heating network optimization for a multi-story residential and commercial building located in Esenyurt, Istanbul. 

This repository documents the complete engineering workflow, from raw structural layout and material properties down to computerized verification using industry-standard HVAC software.

---

## 📌 Project Executive Summary
* **Location:** Istanbul / Esenyurt (2nd Climate Zone according to TS 825)
* **Design Ambient Temperature:** $-3^\circ\text{C}$ (Winter outdoor design temperature for Istanbul)
* **Building Structure:** 6-Story Complex (Basement, Ground Floor Commercial, Upper Residential Floors)
* **Total Gross Construction Area:** $584.14\text{ m}^2$
* **Total Building Heat Loss (Calculated):** $16.53\text{ kW}$
* **Total Installed Radiator Capacity:** $\approx 26\text{ kW}$ (Adjusted for real-world manufacturer availability and temperature correction factors)
* **Primary Compliance Standards:** * **TS 825** (Thermal Insulation Requirements for Buildings)
  * **TS 2164** (Principles for the Design of Central Heating Systems)
* **Core Software Utilized:** MTH (Mechanical Thesis Heating) Package Software Suite

---

## 📁 Technical Breakdown by Project Phases

The complete engineering study is divided into seven sequential phases, representing a rigorous, professional HVAC project workflow:

### 1. Architectural Analysis & Boundary Conditions (Report 1)
* Detailed inspection of the 6-story structural drawings located at Esenyurt, Atatürk Mahallesi (Sheet No: 23B-3A, Parcel: 3).
* Zonal separation between unheated spaces (basements, stairwells) and conditioned zones (commercial ground floor, residential apartments).
* Definition of volume, net floor areas, and orientation correction metrics (North, South, East, West components).

### 2. Thermal Transmittance ($U$-Value) Calculations (Report 2)
Layer-by-layer composite material breakdown to compute the Overall Heat Transfer Coefficients ($U$-values) in compliance with TS 825 limits:
* **Exterior Walls:** Plaster, insulated brick core, high-density insulation layer, and outer cladding.
* **Roof & Ceilings:** Weatherproofing layers, structural reinforced concrete slab, and internal finishes.
* **Exposed Floors:** Flooring matrix positioned over unheated basement boundaries.
* *Mathematical Basis:* $$U = \frac{1}{R_{\text{si}} + \sum \frac{d_i}{\lambda_i} + R_{\text{se}}}$$
  *(Where $d$ represents thickness, $\lambda$ represents material thermal conductivity, and $R$ represents surface thermal resistances).*

### 3. Comprehensive Heat Loss Analysis (Report 3)
Space-by-space calculations implementing the complete thermal equilibrium equations across all six floors:
* **Transmission Heat Losses ($Q_T$):** Heat conducted through walls, windows, doors, and structural interfaces.
* **Infiltration Heat Losses ($Q_V$):** Air change rate allowances ($n_{50}$) and natural air leakage through building envelope seams.
* **Incremental Additions ($Z$):** Safety margins for directional exposure (e.g., North-facing walls), intermittent heating intervals, and structural thermal bridges.
* **Result:** Finalization of the exact peak heating load ($16.53\text{ kW}$) needed under worst-case winter conditions.

### 4. Hydronic Radiator Selection & Sizing (Report 4)
* Mapping room-specific heat demands to physical emitter capacities.
* **Selection Matrix:** Panel radiators (Type 22 / PKKP) and towel warmers (havlupan) chosen from standardized manufacturer catalogs.
* **Correction Factor Implementation ($F_k$):** Raw radiator outputs nominalized at $\Delta T = 50\text{K}$ ($75/65/20^\circ\text{C}$ system) adjusted to meet specific internal design temperatures of distinct living zones ($22^\circ\text{C}$ for living rooms, $24^\circ\text{C}$ for bathrooms, $18^\circ\text{C}$ for corridors).

### 5. Hydraulic Piping Network & Pressure Drop Analysis (Report 5)
* Design of the two-pipe hydronic loop distribution layout.
* **Critical Circuit Identification:** Explicit mapping of the hydraulically longest, most restrictive pipe run to establish peak system head requirements.
* **Sizing Methodology:** Flow rates calculated via $V = \frac{Q}{c \cdot \Delta T}$. Pipe diameters optimized to balance velocity limitations (preventing erosion/noise) and frictional resistances.
* **Circulation Pump Selection:** Sizing the primary pump based on the cumulative head loss of the critical path and the total volumetric design flow.

### 6. Auxiliary Equipment & Subsystem Sizing (Report 6)
* **Expansion Tank Dimensions:** Calculation of system water volume expansion under peak operating temperatures to size a diaphragm-type closed expansion tank, ensuring safe pressure containment.
* **Chimney & Exhaust Design:** Shaft sizing, draft calculations, and flue diameters tailored to handle the combustion products of the selected high-efficiency boiler configuration.

### 7. Computer-Aided Verification via MTH Software (Report 7)
* Complete digitization of the building envelope within the **MTH (Mechanical Thesis Heating)** software package.
* **Optimization & Validation:** Cross-referencing manual calculations with computer-aided simulations. 
* Identified and resolved edge-case room deficits where catalog nominal capacities required slight upward scaling to safely counter structural exposure effects, validating the final real-world feasibility of the heating system.

---

## 🛠️ Key Professional Competencies Demonstrated
* **Regulatory Compliance:** Execution of full-scale **TS 825** and **TS 2164** standard calculation sequences.
* **Engineering Software Proficiency:** Advanced mastery of **MTH software** for thermal zoning and structural fluid modeling.
* **Systems Engineering:** Balancing thermal load calculations directly with practical manufacturing constraints, pressure distributions, and equipment safety margins.

---

<p align="center">
  <b>Advisor:</b> Dr. Öğr. Üyesi Muammer Kanlı <br>
  <b>Developer:</b> Yusuf Yıldızlar <br>
  <i>Mechanical Engineering Department, Beykent University, 2025-2026</i>
</p>
