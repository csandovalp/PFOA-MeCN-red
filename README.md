# README: Organization of Input, Output, and Optimized Structures

This directory contains DFT calculations used to compute the reduction potentials for the concerted and stepwise mechanisms of PFOA electroreduction in acetonitrile.

## **Main Directories**

1. **F**  
2. **F•**  
3. **PFO-**  
4. **PFOA**  
5. **PFO---H2O**  

Each of these directories contains subfolders organized by the level of theory and type of calculation (e.g., optimization and frequency calculations) carried out in the solvent media using the SMD solvation model implemented in ORCA 6.0.0.

---

## **Folder Structure and Contents**

### **F**
This directory contains calculations performed using ORCA 6.0.0 with the SMD solvation model to compute the solution state energies of the F- anion
- Files: `.inp` and `.out` for each calculation.

### **F•**
This directory contains single-point energy calculations using the SMD solvation model to compute the solution state energy of the F• radical that was used to compute bond dissociation energies.
- Files: `.inp` and `.out` for each calculation.

### **PFO-**
This directory contains geometry optimizations  single-point energy calculations using the SMD solvation model to compute the reduction potentials for the concerted and stepwise mechanisms for the electrochemical reduction of PFO- anion.
- Files: `.inp`, `.xyz`, and `.out` for each calculation.

### **PFOA**
This directory contains geometry optimizations  single-point energy calculations using the SMD solvation model to compute the reduction potentials for the concerted and stepwise mechanisms for the electrochemical reduction of the neutral PFOA molecule.
- Files: `.inp`, `.xyz`, and `.out` for each calculation.

### **PFO---H2O**
This directory contains geometry optimizations  single-point energy calculations using the SMD solvation model to compute the reduction potentials for the concerted and stepwise mechanisms for the electrochemical reduction of PFO- anion considering the explicit interaction of the carboxylic head group with one and two water molecules.
- Files: `.inp`, `.xyz`, and `.out` for each calculation.

---

## **Summary of Methodology**
- ORCA calculations are performed with SMD solvation models. Geometry optimizations and frequency calculations are carried out in the solvent phase at three different levels of theory:
- TPSSh-D3/def2-TZVP, B3LYP-D3/def2-TZVP, and r2SCANh-D3/def2-TZVP

---

## **Reference to Manuscript**
- The data presented in this repository is distributed as part of the publication "Electrochemical reduction  of perfluorooctanoic acid (PFOA) in organic media: mechanistic insights and reorganization effects."
- DOI: (currently under review).
- Data gathered and prepared by:
- Rosa. R. Fabela Robledo, PhD Student, The University of Texas at El Paso, El Paso, TX 79968, USA
- Christian Sandoval-Pauker, Postdoctoral Fellow, Smalley-Curl Institute, Rice University, Houston, TX,77005, USA
