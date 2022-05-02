## About

Contains the input files required for the simulation. 

## Description
1. eq1 - the configuration file for minimization
2. eq2, eq3 -  the configuration files for NPT run to stablize the system to prevent bad contact and system from crashing
3. eq4 - the configuration file for NVT run.
4. par_all27_prot_lipid, top_all27_prot_lipid - (topology file) Contains all the molecular-specific information needed to apply a particular force field to the molecular system.
5. solvate (PDB, PSF) - Contains information on the coordinates of atoms of the Protein.
6. pbs_sharanga_longer - SBATCH file required to run the simulation on the HPC (High Performance Computing) cluster.
