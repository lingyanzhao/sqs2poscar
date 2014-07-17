sqs2poscar
==========

A c++ code to convert bestsqs.out from mcsqs (ATAT) to POSCAR for VASP.

Compile: `c++ ./sqs2poscar.cpp -o ./sqs2poscar`

Usage: `sqs2poscar bestsqs.out`
  
Output file: `bestsqs.out-POSCAR`

Post-processing: change `xxx` in the second line of output POSCAR file to your lattice constant.

Note: `bestsqs.out` can be any file at present working directory.
