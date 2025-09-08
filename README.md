# Extremal Hyperbolic Surfaces

This directory contains GAP and SAGE scripts for the study and generation of extremal hyperbolic surfaces, both closed and non-closed (ie. with geodesic boundary and/or cusps). The codes are organized to count and generate fundamental domains, triangle subgroups, and extremal disc configurations associated with these surfaces.

## Structure

- **GAP codes/**
  - **Extremal closed surfaces/**
    - *Counting extremal closed surfaces.txt*: GAP script to enumerate all the Dirichlet domains and uniformizing subgroups for closed extremal surfaces with a given Euler characteristic.
    - *Counting extremal orientable closed surfaces.txt*: GAP script to enumerate all the Dirichlet domains and uniformizing subgroups for orientable closed extremal surfaces with a given genus.
    - *Generating extremal closed surfaces.txt*: GAP script to generate a certain number of Dirichlet domains and uniformizing subgroups for closed extremal surfaces with a given Euler characteristic.
    - *Generating extremal orientable closed surfaces.txt*: GAP script to generate a certain number of Dirichlet domains and uniformizing subgroups for orientable closed extremal surfaces with a given genus.
  - **Extremal non-closed surfaces/**
    - *Counting extremal non-closed surfaces.txt*: GAP script to enumerate all the Dirichlet domains and uniformizing subgroups for non-closed extremal surfaces with a given Euler characteristic and a given extended number of boundary components.
    - *Counting extremal orientable non-closed surfaces.txt*: GAP script to enumerate all the Dirichlet domains and uniformizing subgroups for orientable non-closed extremal surfaces with a given genus and a given extended number of boundary components.
    - *Generating extremal non-closed surfaces.txt*: GAP script to generate a certain number of Dirichlet domains and uniformizing subgroups for non-closed extremal surfaces with a given Euler characteristic and a given extended number of boundary components.
    - *Generating extremal orientable non-closed surfaces.txt*: GAP script to generate a certain number of Dirichlet domains and uniformizing subgroups for orientable non-closed extremal surfaces with a given genus and a given extended number of boundary components.

- **SAGE codes/**
  - Scripts for further analysis and visualization of each particular extremal surface and their extremal disc centers. The only extremal surfaces considered are the non-closed extremal surfaces with Euler characteristic -1 and the (orientable) extremal surfaces of genus zero with extended number of boundary components 4.

## Usage

To run the GAP scripts, install [GAP](https://www.gap-system.org/) and execute the `.txt` files in the GAP console. For SAGE scripts, use [SageMath](https://www.sagemath.org/).

Each GAP script is documented with comments describing input parameters (such as the genus, the Euler characteristic or the extended number of boundary components) and the mathematical objects being constructed or counted.

## Mathematical Background

The scripts focus on:
- Enumerating and constructing all subgroups of Fuchsian triangle groups and extended triangle groups associated to the construction of Dirichlet domains of extremal hyperbolic surfaces.
- Describing explictly the Dirichlet domains of some extremal hyperbolic surfaces, handing both orientable and non-orientable cases, as well as surfaces with geodesic boundary or cusps.
- Studying the number of extremal discs in each particular extremal surface considered in the SAGE codes, as well as the location of their centers, by the numerical approximation of their uniformizing groups. 

## References

The main reference is an unpublished preprint titled _THE NEC GROUP UNIFORMIZATION OF EXTREMAL HYPERBOLIC SURFACES WITH BOUNDARY AND/OR CUSPS_, written by Ernesto Girondo and Claudia Muñoz. For more details on the mathematical theory, see the comments in each script and relevant literature on hyperbolic geometry, extremal surfaces and Fuchsian/NEC groups.

---

*Authors: Claudia Muñoz and Ernesto Girondo.
