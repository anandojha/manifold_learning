manifold_learning
==============================
[//]: # (Badges)
[![GitHub Actions Build Status](https://github.com/REPLACE_WITH_OWNER_ACCOUNT/manifold_learning/workflows/CI/badge.svg)](https://github.com/REPLACE_WITH_OWNER_ACCOUNT/manifold_learning/actions?query=workflow%3ACI)
[![codecov](https://codecov.io/gh/REPLACE_WITH_OWNER_ACCOUNT/manifold_learning/branch/main/graph/badge.svg)](https://codecov.io/gh/REPLACE_WITH_OWNER_ACCOUNT/manifold_learning/branch/main)



# Jupyter Notebooks for the ManifoldEM Python Suite

## Installation Requirements 

```bash
conda create -n manifold_learning python=3.10
```
```bash
conda activate manifold_learning 
```
```bash
pip install notebook==6 seaborn mrcfile scipy nptyping scikit-learn numba tqdm imageio PyQt5
```
## Downloading the sample cryo-EM data for the notebooks
```bash
wget -P ~/manifold_learning https://zenodo.org/records/10728025/files/data.zip?download=1
```

```bash
cd ~/manifold_learning
```

```bash
unzip 'data.zip?download=1'
```

```bash
rm 'data.zip?download=1'
```
### Copyright

Copyright (c) 2024, Anupam Anand Ojha


#### Acknowledgements
 
Project based on the 
[Computational Molecular Science Python Cookiecutter](https://github.com/molssi/cookiecutter-cms) version 1.1.
