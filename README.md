# Accelerating-Molecular-Dynamics-with-Support-Vector-Machines

## Overview
This page includes results and implementation of a novel method for accelerating molecular dynamics with support vector machines I developed. This methods uses One Class Support Vector Machines (OCSVM) to identify probable regions on a potential energy surface as well as the hyperdynamics method to accelerate molecular dynamic simulations.  I will refer to this method as hyperdynamics with OCSVM (HD-OCSVM).

## Implementation 

HD-OCSVM is implemented  within the Transition State Library for ASE (TSASE), a python package for atomic simulations and uses the scikit-learn library. In order to to use run  you will need to install TSASE.  TSASE depends on Atomic Simulation Environment (ASE). 

### ASE

You can find installation instructions for ASE at the following webpage: 

https://wiki.fysik.dtu.dk/ase/install.html

### TSASE 

You can find installation instructions for TSASE at the following webpage:

http://theory.cm.utexas.edu/tsase/download.html

### HD-OCSVM documentation

You can find documentation of how to use HD-OCSVM in TSASE is here:

http://theory.cm.utexas.edu/tsase/svm.html

## Results 

OCSVM_publication.pdf is the publication associated with this project.
