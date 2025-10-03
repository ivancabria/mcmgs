The name of the code is 'mcmgs', an abbreviation of 'Monte Carlo
Methods of Gas Storage'.

The code 'mcmgs' calculates the gas storage capacities of a solid material,
by means of a Grand Canonical Monte Carlo, GCMC, simulation.

The code calculates the volumetric and gravimetric capacities.
It calculates the total, usable and excess capacities.

The present version calculates the hydrogen, methane and CO2 storage
capacities of a solid material.

It uses the theory of GCMC simulations, the SRK equation of state of
hydrogen, methane and CO2 and the Lennard-Jones interaction potentials
between the molecules and between the molecules and the atoms of the
solid materials. It also includes the option of applying Feynmann-Hibbs
quantum corrections.

The code 'mcmgs' is written in fortran and only for Unix/Linux environments.

It has been compiled and tested on different hosts based on Unix/Linux

The source files, the user manual of the code and some examples of input and output files 
are in the branches of this project.

To compile the code:
a) tar zxvf mcmgs-source.tar.gz   The source files are in the directory mcmgs/source
b) cd mcmgs/source
c) Enter 'make' or 'make -s'

The file inputandoutputfiles.tar.gz contains some examples of input and output files. To get 
those files, enter 'tar zxvf inputandoutputfiles.tar.gz'.

The file ljparameters.pdf contains the LJ (Lennard-Jones) parameters of the 
103 atoms and six molecules used by the code 'mcmgs'.

<a href="https://doi.org/10.5281/zenodo.15708498"><img src="https://zenodo.org/badge/996108119.svg" alt="DOI"></a>


