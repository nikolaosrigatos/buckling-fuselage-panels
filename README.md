# buckling-fuselage-panels
A master’s thesis for my Mechanical and Aeronautical Engineering degree focused on the investigation and numerical modelling of the buckling and post-buckling behaviour of metallic stiffened aircraft panels

This repository contains the ANSYS APDL codes, validation studies, and supporting material developed as part of my diploma thesis. The work focuses on buckling and combined loading behavior of plates and stiffened fuselage panels under compression, shear, and combined compression–shear loading.

## Repository Structure

### 📁 Ansys APDL Codes and Validations
Contains all ANSYS APDL scripts used in this thesis, along with their corresponding validation material.

The validation models are organized as follows:

- **Compression**
- **Shear**
- **Combined Compression and Shear / Plate**

For **Compression** and **Shear**, validations are performed at multiple structural levels:
- Plate  
- Stiffened plate  
- Shell  
- Stiffened fuselage panel  

For **Combined Compression and Shear**, validation is carried out at the **plate level only**.

Each folder typically includes:
- ANSYS APDL code files  
- Validation sources (analytical solutions and/or experimental literature)  
- Excel files used for validation and comparison  
- Figures such as eigenmodes, displacement plots, and related results  

---

### 📁 Combined Loading Stiffened Fuselage Panel
This folder contains the main research study on **combined loading of stiffened fuselage panels**.

The work investigates both **isotropic** and **orthotropic** panels with identical geometry. Interaction curves are generated and compared to examine the influence of material anisotropy on the combined compression–shear response.

Key contents include:
- ANSYS APDL models  
- Post-processing results  
- Interaction curves  
- Supporting figures and data  

---

### 📁 Compression  
Standalone compression validation cases (also included in the broader validation workflow).

---

### 📁 Shear  
Standalone shear validation cases (also included in the broader validation workflow).

---

### 📄 Diploma Thesis Presentation.pdf / .pptx
These files contain the presentation of my diploma thesis, summarizing:
- Problem formulation  
- Modeling approach  
- Validation studies  
- Combined loading investigation  
- Key results and conclusions  

---

## Summary

In short:

- **ANSYS APDL Codes and Validations**: All modeling scripts and validation studies.  
- **Compression / Shear**: Validation at plate, stiffened plate, shell, and stiffened fuselage levels.  
- **Combined Compression and Shear (Plate)**: Plate-level validation only.  
- **Combined Loading Stiffened Fuselage Panel**: Core research comparing isotropic vs orthotropic stiffened panels under combined loading using interaction curves.  
- **Diploma Thesis Presentation**: Overview of the complete thesis work.
- **DT_M_RIGATOS_NIKOLAOS_1054457**: Thesis work (in Greek)

---
