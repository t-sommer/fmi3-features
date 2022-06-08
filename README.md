# FMI 3.0 Feature Demo

The Jupyter notebooks below showcase some of the new features in in FMI 3.0.

- [adjoint_derivatives.ipynb](adjoint_derivatives.ipynb) - retrieve adjoint derivatives efficiently
- [array_variables.ipynb](array_variables.ipynb) - work efficiently with array variables
- [cs_events.ipynb](cs_events.ipynb) - Co-Simulation with events
- [intermediate_update.ipynb](intermediate_update.ipynb) - access the model at internal solver steps

## Run the notebooks in the cloud

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/t-sommer/fmi3-features/HEAD)

## Run the notebooks locally

- install [mambaforge](https://github.com/conda-forge/miniforge#mambaforge)
- if mamba is not on the `PATH` run `<mamba_install_dir>/condabin/activate`
- `mamba create -n fmi3-features fmpy jupyterlab-plotly-extension`
- `mamba activate fmi3-features`
- clone the repository and change into the directory
- run `jupyter lab`

------------------------------------

&copy; 2022 Dassault Syst&egrave;mes
