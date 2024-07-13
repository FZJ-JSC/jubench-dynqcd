# JUPITER Benchmark Suite: DynQCD

[![DOI](https://zenodo.org/badge/828238689.svg)](https://zenodo.org/badge/latestdoi/828238689) [![Static Badge](https://img.shields.io/badge/DOI%20(Suite)-10.5281%2Fzenodo.12737073-blue)](https://zenodo.org/badge/latestdoi/764615316)

This benchmark is part of the [JUPITER Benchmark Suite](https://github.com/FZJ-JSC/jubench). See the repository of the suite for some general remarks.

This repository contains the DynQCD benchmark, created by JSC. [`DESCRIPTION.md`](DESCRIPTION.md) contains details for compilation, execution, and evaluation.

DynQCD is a software suit for numerical simulations of lattice quantum chromodynamics. It is mainly used in physics projects of the [Budapest-Marseille-Wuppertal](https://www.bmw.uni-wuppertal.de) lattice collaboration. Using this code the computation of the muon magnetic moment has been performed, with the result published in [Nature](https://www.nature.com/articles/s41586-021-03418-1). The code is written in GNU flavor of C99 and parallelized with openMP and MPI.