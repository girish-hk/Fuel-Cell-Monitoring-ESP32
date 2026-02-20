# Fuel Cell DAQ PCB – ESP32-S3


This repository contains the hardware design of a **Fuel Cell Monitoring and Measurement Board** developed in KiCad.  
The board is designed to monitor key electrical parameters of a PEM fuel cell system and interface with an **ESP32-S3** microcontroller.



  ## Project Overview
- Application: Fuel Cell Monitoring & Data Acquisition
- Input Voltage Range: 24V – 45V DC
- Microcontroller: ESP32-S3
- PCB Design Tool: KiCad 8



##  Key Design Features
- **High-side current sensing** for accurate measurement
- **Galvanic isolation** between control and measurement domains
- **Low-noise analog signal conditioning**
- PCB verified using **ERC and DRC checks** in KiCad



##  3D Board View

### Top View
![Top View](Images/board_3d_top.png)

### Bottom View
![Bottom View](Images/board_3d_bottom.png)



##  Repository Structure
- `Hardware/` – KiCad schematic and PCB layout files  
- `Libraries/` – Custom symbols and footprints  
- `Production/` – Gerber files and Bill of Materials  
- `Docs/` – Schematic PDF and project documentation  
- `Images/` – 3D rendered views of the PCB  



## Tools Used
- KiCad 8 (Schematic & PCB Design)
- ESP32-S3 platform
- GitHub for version control and documentation

---

##  Enclosure Concept Design (Fusion 360)

To extend the PCB into a complete product-level concept, a custom enclosure was modeled in Fusion 360 and integrated with the 3D PCB assembly.

The enclosure was designed to validate mechanical fit, clearance, and component accessibility.

### Design Specifications

- Overall dimensions: 94 mm (L) × 94 mm (W) × 22 mm (H)
- Enclosure wall thickness: 2 mm
- Base clearance from PCB: 3 mm
- Side clearance: 5 mm
- PCB mounting standoff height: 3 mm
- Standoff mounting hole diameter: 3 mm
- Connectors openings are aligned with PCB layout

### Mechanical Integration Highlights

- PCB-to-enclosure alignment verified in 3D assembly
- Internal standoff-based PCB mounting structure
- External connector access defined
- Clearance validated for component height



##  Author
**Girish**  
Master’s Student – HS Wismar  
