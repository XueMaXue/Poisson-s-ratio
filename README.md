This repository contains the data supporting our paper “A Polar-displacement mechanism for negative Poisson's ratio in ferroelectric perovskites” (DOI: https://doi.org/10.1103/hh37-m1lt). These data were used to generate the figures presented in the main text and the supplemental material.


# PR_PTO (Fig. 1 & Fig. S1 & Fig. S3 & Fig. S7 & Fig. S9):

This folder contains the calculated strain–Poisson-ratio data for PbTiO3 in both the tetragonal and cubic phases.  
Results are obtained using both direct strain–response calculations and the indirect elastic-constant method.

## File description

### PTO-P4mm-0deg.txt
### PTO-Pm-3m-0deg.txt

Direct calculations with strain applied along the [100] direction for the tetragonal (P4mm) and cubic (Pm-3m) phases, respectively.

Columns 5–9:

5. Applied strain along [100]  
6. Induced strain along [010]  
7. Induced strain along [001]  
8. In-plane Poisson's ratio  
9. Out-of-plane Poisson's ratio

### PTO-P4mm-45deg.txt
### PTO-Pm-3m-45deg.txt

Direct calculations with strain applied along the [110] direction.

Columns 5–9:

5. Applied strain along [110]  
6. Induced strain along [1-10]  
7. Induced strain along [001]  
8. In-plane Poisson's ratio  
9. Out-of-plane Poisson's ratio

### PTO-P4mm.txt
### PTO-Pm-3m.txt

Poisson's ratios obtained using the indirect method based on elastic constants.

Columns:

1. θ (angle, in radians)  
2. In-plane Poisson's ratio  
3. Out-of-plane Poisson's ratio

---

# PR_BTO (Fig. 2 & Fig. S2 & Fig. S4 & Fig. S7 & Fig. S9):

This folder contains strain–Poisson-ratio data for BaTiO3 obtained from first-principles calculations. 
Both direct strain–response simulations and indirect calculations based on elastic constants are provided.

All files are plain text (.txt) format.

## Crystal phases

The datasets correspond to the following phases:

- T: P4mm
- C: Pm-3m
- C': I-43m
- T': I4cm

## Direct strain calculations

### Files (0° loading direction, along [100])

BTO-P4mm-0deg.txt   
BTO-I-43m-0deg.txt   
BTO-I4cm-0deg.txt   
BTO-Pm-3m-0deg.txt   

Columns 5–9:

5. Applied strain along [100]  
6. Induced strain along [010]  
7. Induced strain along [001]  
8. In-plane Poisson's ratio  
9. Out-of-plane Poisson's ratio  

### Files (45° loading direction, along [110])

BTO-P4mm-45deg.txt   
BTO-I-43m-45deg.txt   
BTO-I4cm-45deg.txt   
BTO-Pm-3m-45deg.txt   

Columns 5–9:

5. Applied strain along [110]  
6. Induced strain along [1-10]  
7. Induced strain along [001]  
8. In-plane Poisson's ratio  
9. Out-of-plane Poisson's ratio  

## Indirect method (elastic-constant approach)

### Files

BTO-P4mm.txt  
BTO-I-43m.txt   
BTO-I4cm.txt   
BTO-Pm-3m.txt   

Columns:

1. θ (angle in radians)  
2. In-plane Poisson's ratio  
3. Out-of-plane Poisson's ratio  

---

# Potential_Energy_Surfaces (Fig. 3 & Fig. S10):

This folder contains potential energy surface (PES) datasets calculated under different strain conditions for multiple structural phases of BaTiO3 and PbTiO3.

The data are intended for constructing a two-dimensional contour of the potential energy surfaces as functions of polarization and strain.

Each phase/strain subfolder includes three plain text (.txt) files:

- energy.txt
- epsilon_2.txt
- polar.txt

## Data structure

Each dataset corresponds to a 2D PES grid.

For every grid point:

- x-axis: polarization (polar.txt)
- y-axis: responsive strain (epsilon_2.txt)
- color (value): total energy (energy.txt)

Thus, the three files share the same grid ordering and can be directly combined to reconstruct the PES.

---

# PR_Expt (Fig. S5 & Fig. S6):

This folder contains Poisson's ratio datasets derived from experimentally reported elastic constants for BaTiO3 and PbTiO3 in different structural phases.

The Poisson's ratios are calculated indirectly from literature elastic constants using the elastic-tensor formalism.

All files are provided in plain text (.txt) format.

## Column definitions

Each file contains three columns:

1. θ (angle in radians)  
2. In-plane Poisson's ratio  
3. Out-of-plane Poisson's ratio  

---

# Apply_E (Fig. 4):

Electric-field–induced sign reversal of the Poisson’s ratio in tetragonal PbTiO3 under ε_[100] = +1% strain.
## File description

### 1. free_strain.txt
Structural response without mechanical constraint.

Columns:
1. Applied electric field (MV/m)  
2. Lattice constant a (Å)  
3. Lattice constant b (Å)  
4. Lattice constant c (Å)

### 2. +1%_strain.txt
Structural response under a uniaxial +1% strain applied along the [100] direction.

Columns:
1. Applied electric field (MV/m)  
2. Lattice constant a (Å)  
3. Lattice constant b (Å)  
4. Lattice constant c (Å)

### 3. polar.txt
Polarization change under applied electric fields with a +1% strain imposed along the [100] direction.

Columns:
1. Applied electric field (MV/m)  
2. Polarization (C/m²)

---

# PR_ML (Fig. S11 & Fig. S12):

This folder contains temperature-dependent Poisson's ratio datasets for BaTiO3 and PbTiO3.

The Poisson's ratios are obtained indirectly from elastic constants predicted using machine-learning models. 
Specifically, temperature-dependent elastic tensors are first evaluated by ML potentials, and the corresponding Poisson's ratios are then calculated using the elastic-constant formalism.

All files are provided in plain text (.txt) format.

## Column definitions

Each file contains three columns:

1. θ (angle in radians)  
2. In-plane Poisson's ratio  
3. Out-of-plane Poisson's ratio  
