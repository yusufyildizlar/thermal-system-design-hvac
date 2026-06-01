# Comprehensive Thermal System Design & HVAC Installation Project

An end-to-end mechanical engineering project focusing on the thermal system design, heat loss analysis, and hydronic heating network optimization for a multi-story residential and commercial building located in Esenyurt, Istanbul.[span_1](start_span)[span_1](end_span)

This repository documents the complete engineering workflow, from raw structural layout and material properties down to computerized verification using industry-standard HVAC software.[span_2](start_span)[span_2](end_span)

---

## 📌 Project Executive Summary
* **Location:** Istanbul / Esenyurt (2nd Climate Zone according to TS 825)[span_3](start_span)[span_3](end_span)
* **Design Ambient Temperature:** -3°C (Winter outdoor design temperature for Istanbul)[span_4](start_span)[span_4](end_span)
* **Building Structure:** 6-Story Complex (Basement, Ground Floor Commercial, Upper Residential Floors)[span_5](start_span)[span_5](end_span)
* **Total Gross Construction Area:** 584.14 m²[span_6](start_span)[span_6](end_span)
* **Total Building Heat Loss (Calculated):** 16.53 kW[span_7](start_span)[span_7](end_span)
* **Total Installed Radiator Capacity:** ≈ 26 kW (Adjusted for real-world manufacturer availability and temperature correction factors)[span_8](start_span)[span_8](end_span)
* **Primary Compliance Standards:** 
  * **TS 825** (Thermal Insulation Requirements for Buildings)[span_9](start_span)[span_9](end_span)
  * **TS 2164** (Principles for the Design of Central Heating Systems)[span_10](start_span)[span_10](end_span)
* **Core Software Utilized:** MTH (Mechanical Thesis Heating) Package Software Suite[span_11](start_span)[span_11](end_span)

---

## 📁 Technical Breakdown by Project Phases

The complete engineering study is divided into seven sequential phases, representing a rigorous, professional HVAC project workflow:[span_12](start_span)[span_12](end_span)

### 1. Architectural Analysis & Boundary Conditions (Report 1)
* Detailed inspection of the 6-story structural drawings located at Esenyurt, Atatürk Mahallesi (Sheet No: 23B-3A, Parcel: 3).[span_13](start_span)[span_13](end_span)
* Zonal separation between unheated spaces (basements, stairwells) and conditioned zones (commercial ground floor, residential apartments).[span_14](start_span)[span_14](end_span)
* Definition of volume, net floor areas, and orientation correction metrics (North, South, East, West components).[span_15](start_span)[span_15](end_span)

### 2. Thermal Transmittance (U-Value) Calculations (Report 2)
Layer-by-layer composite material breakdown to compute the Overall Heat Transfer Coefficients (U-values) in compliance with TS 825 limits:[span_16](start_span)[span_16](end_span)
* **Exterior Walls:** Plaster, insulated brick core, high-density insulation layer, and outer cladding.[span_17](start_span)[span_17](end_span)
* **Roof & Ceilings:** Weatherproofing layers, structural reinforced concrete slab, and internal finishes.[span_18](start_span)[span_18](end_span)
* **Exposed Floors:** Flooring matrix positioned over unheated basement boundaries.[span_19](start_span)[span_19](end_span)
* **Mathematical Basis:** 

$$U = \frac{1}{R_{si} + \sum \frac{d_i}{\lambda_i} + R_{se}}$$

*(Where **d** represents thickness, **λ** represents material thermal conductivity, and **R** represents surface thermal resistances).*[span_20](start_span)[span_20](end_span)

### 3. Comprehensive Heat Loss Analysis (Report 3)
Space-by-space calculations implementing the complete thermal equilibrium equations across all six floors:[span_21](start_span)[span_21](end_span)
* **Transmission Heat Losses (Q_T):** Heat conducted through walls, windows, doors, and structural interfaces.[span_22](start_span)[span_22](end_span)
* **Infiltration Heat Losses (Q_V):** Air change rate allowances (n_50) and natural air leakage through building envelope seams.[span_23](start_span)[span_23](end_span)
* **Incremental Additions (Z):** Safety margins for directional exposure (e.g., North-facing walls), intermittent heating intervals, and structural thermal bridges.[span_24](start_span)[span_24](end_span)
* **Result:** Finalization of the exact peak heating load (16.53 kW) needed under worst-case winter conditions.[span_25](start_span)[span_25](end_span)

### 4. Hydronic Radiator Selection & Sizing (Report 4)
* Mapping room-specific heat demands to physical emitter capacities.[span_26](start_span)[span_26](end_span)
* **Selection Matrix:** Panel radiators (Type 22 / PKKP) and towel warmers (havlupan) chosen from standardized manufacturer catalogs.[span_27](start_span)[span_27](end_span)
* **Correction Factor Implementation (F_k):** Raw radiator outputs nominalized at ΔT = 50K (75/65/20°C system) adjusted to meet specific internal design temperatures of distinct living zones (22°C for living rooms, 24°C for bathrooms, 18°C for corridors).[span_28](start_span)[span_28](end_span)

### 5. Hydraulic Piping Network & Pressure Drop Analysis (Report 5)
* Design of the two-pipe hydronic loop distribution layout.[span_29](start_span)[span_29](end_span)
* **Critical Circuit Identification:** Explicit mapping of the hydraulically longest, most restrictive pipe run to establish peak system head requirements.[span_30](start_span)[span_30](end_span)
* **Sizing Methodology:** Flow rates calculated via the standard fluid dynamics relation:

$$V = \frac{Q}{c \cdot \Delta T}$$

* Pipe diameters optimized to balance velocity limitations (preventing erosion/noise) and frictional resistances.[span_31](start_span)[span_31](end_span)
* **Circulation Pump Selection:** Sizing the primary pump based on the cumulative head loss of the critical path and the total volumetric design flow.[span_32](start_span)[span_32](end_span)

### 6. Auxiliary Equipment & Subsystem Sizing (Report 6)
* **Expansion Tank Dimensions:** Calculation of system water volume expansion under peak operating temperatures to size a diaphragm-type closed expansion tank, ensuring safe pressure containment.[span_33](start_span)[span_33](end_span)
* **Chimney & Exhaust Design:** Shaft sizing, draft calculations, and flue diameters tailored to handle the combustion products of the selected high-efficiency boiler configuration.[span_34](start_span)[span_34](end_span)

### 7. Computer-Aided Verification via MTH Software (Report 7)
* Complete digitization of the building envelope within the **MTH (Mechanical Thesis Heating)** software package.[span_35](start_span)[span_35](end_span)
* **Optimization & Validation:** Cross-referencing manual calculations with computer-aided simulations.[span_36](start_span)[span_36](end_span)
* Identified and resolved edge-case room deficits where catalog nominal capacities required slight upward scaling to safely counter structural exposure effects, validating the final real-world feasibility of the heating system.[span_37](start_span)[span_37](end_span)

---

## 🛠️ Key Professional Competencies Demonstrated
* **Regulatory Compliance:** Execution of full-scale **TS 825** and **TS 2164** standard calculation sequences.[span_38](start_span)[span_38](end_span)
* **Engineering Software Proficiency:** Advanced mastery of **MTH software** for thermal zoning and structural fluid modeling.[span_39](start_span)[span_39](end_span)
* **Systems Engineering:** Balancing thermal load calculations directly with practical manufacturing constraints, pressure distributions, and equipment safety margins.[span_40](start_span)[span_40](end_span)

---

<p align="center">
  <b>Advisor:</b> Dr. Öğr. Üyesi Muammer Kanlı <br>
  <b>Developer:</b> Yusuf Yıldızlar <br>
  <i>Mechanical Engineering Department, Beykent University, 2025-2026</i>
</p>
