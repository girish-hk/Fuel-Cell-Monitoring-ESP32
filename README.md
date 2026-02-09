# Fuel Cell Monitoring PCB – ESP32-S3

**Master’s Project | Hochschule Wismar (HS Wismar)**

This repository contains the hardware design of a **Fuel Cell Monitoring and Measurement Board** developed as part of my Master’s project.  
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



##  Author
**Girish**  
Master’s Student – HS Wismar  
