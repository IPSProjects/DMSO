[![DagsHub](https://bit.ly/33Q1Dv9)](https://dagshub.com/PythonFZ/SDR)
[![ZnTrack](https://img.shields.io/badge/Powered%20by-ZnTrack-%23007CB0)](https://zntrack.readthedocs.io/en/latest/)
[![zincware](https://img.shields.io/badge/Powered%20by-zincware-darkcyan)](https://github.com/zincware)

# Collaboration on Machine Learned Potentials with IPSuite: A Modular Framework for Learning-on-the-Fly
This repository contains the workflows for machine learned potentials for DMSO.

To use this repository make sure, you've installed the correct versions of [IPSuite](https://github.com/zincware/IPSuite), [apax](https://github.com/apax-hub/apax), [MACE](https://github.com/ACEsuit/mace) and [NequIP](https://github.com/mir-group/nequip).
Furthermore, to access the data you need to `pip install dvc-s3`.

To get started, clone this repository:
```bash
git clone https://github.com/IPSProjects/DMSO
cd DMSO
```

## apax
```bash
git checkout apax
dvc pull -j 1
```

## MACE
```bash
git checkout mace
dvc pull -j 1
```

## MACE (small)
```bash
git checkout mace_small
dvc pull -j 1
```

## NequIP
```bash
git checkout nequip
dvc pull -j 1
```
