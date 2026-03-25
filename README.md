# Ghost Electric Motorcycle — High-Voltage Battery Subsystem

Engineering repository for the high-voltage lithium-ion battery pack subsystem of the Ghost Electric Motorcycle. Documents mechanical packaging, structural integration, and high-voltage power distribution.

---

## 🔋 Generation Roadmap

* **Gen 1 Concept (Spring 2026):** 3D CAD packaging study, cell retention geometry, and volumetric footprint constraints inside the motorcycle chassis.
* **Gen 2 Production (2026–2027):** Complete ground-up electrical and mechanical redesign featuring modular sub-packs, custom busbar sizing, active Battery Management System (BMS) wiring harness, and CAN bus telemetry.

---

## 📐 Gen 1: Modular Mechanical Packaging

| Isometric Assembly | Top-Down Array Layout |
| :---: | :---: |
| ![Isometric View](gen1-concept/renders/Full-Pack-IsometricView.png) | ![Top-Down View](gen1-concept/renders/Full-Pack-TopView.png) |

### Mechanical & Thermal Architecture
* **Volumetric Packaging:** Multi-tiered module geometry optimized for tight lateral clearances within the motorcycle frame.
* **Cell Retention & Anti-Vibration:** Custom upper and lower retaining plates designed to constrain cylindrical lithium-ion cells against dynamic chassis road vibration.
* **Thermal Spacing:** Standardized inter-cell clearance to promote passive airflow and convective heat dissipation.
* **HV Isolation & Tie Plates:** Vertical standoffs and structural tie plates engineered to secure the stack and provide safe clearance for busbars and cell tap leads.

---

## 📂 Repository Structure

```text
├── gen1-concept/
│   ├── cad/         # Neutral .STEP (AP214) exchange assembly
│   └── renders/     # High-resolution isometric & plan view CAD renders
└── README.md        # Subsystem architecture & specifications