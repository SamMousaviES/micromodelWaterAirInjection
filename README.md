Title: Enhanced Oil Recovery Simulations with OpenFOAM 11

This repository contains the simulation files and resources used in the study of enhanced oil recovery (EOR) techniques, as detailed in the blog post "Exploring Enhanced Oil Recovery: A Comparative Study of Water and Air Injection with OpenFOAM’s multiphaseInterFoam Solver" by Sam Mousavi.

Overview:
The project explores the application of water and air injection strategies in a micromodel environment to analyze fluid dynamics and recovery efficiency using the multiphaseInterFoam solver in OpenFOAM. The simulations replicate small-scale representations of porous media, initially saturated with oil, to understand the impact of different fluid injections on oil recovery processes.

Contents:

Geometry and mesh files for the micromodel.
OpenFOAM case setup files for both water and air injection scenarios.
Boundary and initial condition configurations.
Post-processing scripts for result analysis.
Video files showing the comparative analysis of water and air injection simulations.
Objective:
The aim is to provide a comprehensive set of files that can be used to replicate the study, facilitate further research, and serve as an educational tool for those interested in CFD applications in EOR.

Usage:
Run following command in Terminal
- IdeasUnvToFoam
- multiphaseInterFoam
- it is also possible to run in parallel using 'decomposePar' and 'mpirun -np 12 multiphaseInterFoam -parallel' commands


Contribution:
Contributions to this project are welcome. Whether it's refining the simulation setup, enhancing the post-processing tools, or expanding the scope of the study, your input can help advance the understanding of EOR techniques.

License:
This project is open-source and distributed under the MIT license.
