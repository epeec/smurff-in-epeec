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
  
  In EPEEC we added task-based parallelization to SMURFF.
  

- bpmf: mini-application based on SMURFF, much less functionality
  much more optimized for HPC (OpenMP, TBB, MPI, GASPI, ArgoDSM).
  Submodule pointing to https://github.com/ExaScience/bpmf

  In EPEEC we optimized BPMF using OmpSs@Cluster, and ArgoDSMyy

- vms: virtual molecule screening mini-app
  Submodule pointing to https://github.com/ExaScience/vms

  VMS has been tested on many EPEEC programming models.
