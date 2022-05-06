SMURFF - Scalable Matrix Factorization Framework
================================================

SMURFF is a machine learning framework used as a driver for EPEEC.
SMURFF has been developed in the `ExCAPE H2020 project <http://excape-h2020.eu/>`,
and is open source.


Source Code:
	https://github.com/ExaScience/smurff

Documentation:
	http://smurff.readthedocs.io/en/latest/

SMURFF in EPEEC
~~~~~~~~~~~~~~~~

This directory contains:

- smurff: submodule pointing to the GitHub repository of SMURFF
  https://github.com/ExaScience/smurff

- bpmf: mini-application based on SMURFF, much less functionality
  much more optimized for HPC (OpenMP, TBB, MPI, GASPI).
  Submodule pointing to https://github.com/ExaScience/bpmf

- vms: virtual molecule screening mini-app
  Submodule pointing to https://github.com/ExaScience/bpmf
