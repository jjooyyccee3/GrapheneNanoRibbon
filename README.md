# Band Structure of Graphene Nanoribbons (GNRs)

This repository contains the numerical implementation and analytical verification of the Tight-Binding Model to study the electronic properties of graphene and Graphene Nanoribbons (GNRs). This project was developed for the Computational Physics course at National Yang Ming Chiao Tung University (NYCU).

## Features

Graphene Modeling: Analytical and numerical solutions for the 2D graphene Hamiltonian.
GNR Simulations: Construction of Tight-Binding Hamiltonians for Armchair GNRs (AGNRs) based on the number of dimer lines ($N_a$).
Edge Effect Analysis: Integration of the "shrinking effect" on edge hopping integrals ($t_e$) to reproduce realistic band gap behaviors.
Validation of Results against established literature (e.g., Son et al., 2006; Wakabayashi et al., 2010).

## Results
Dirac Cones: Successfully plotted the linear dispersion relation of graphene near the K-points.
Band Gap vs. Width: Demonstrated that for AGNRs, the band gap is a function of width, categorized by $N_a = 3p$, $3p+1$, and $3p+2$.+1
Metal-to-Semiconductor Transition: Observed that including edge relaxation ($t_e$) correctly predicts band gaps in ribbons previously thought to be metallic in simple models.
