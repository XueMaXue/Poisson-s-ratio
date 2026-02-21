This repository contains the data supporting our paper “A Polar-displacement mechanism for negative Poisson's ratio in ferroelectric perovskites” (DOI: https://doi.org/10.1103/hh37-m1lt). These data were used to generate the figures presented in the main manuscript and the supplemental material.

# Apply_E (Fig. 4):

This folder contains the raw simulation data used to analyze the structural and polarization responses of the material under externally applied electric fields.

## File description

### 1. free_strain.txt
Structural response without mechanical constraint.

Columns:
1. Applied electric field (MV/m)  
2. Lattice constant a (Å)  
3. Lattice constant b (Å)  
4. Lattice constant c (Å)

---

### 2. +1%_strain.txt
Structural response under a uniaxial +1% strain applied along the [100] direction.

Columns:
1. Applied electric field (MV/m)  
2. Lattice constant a (Å)  
3. Lattice constant b (Å)  
4. Lattice constant c (Å)

---

### 3. polar.txt
Polarization change under applied electric fields with a +1% strain imposed along the [100] direction.

Columns:
1. Applied electric field (MV/m)  
2. Polarization (C/m²)

---

## Notes

- All data are provided in plain text (.txt) format.
- Electric fields are given in MV/m.
- Lattice constants are in angstroms (Å).
- Polarization values are reported in C/m².
- These datasets are directly generated from first-principles simulations and are intended for reproducibility and further analysis.
