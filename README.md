# Quantum Seizures: codes to sonify data from epilepsy, and quantum-simulated data.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18679847.svg)](https://doi.org/10.5281/zenodo.18679847)


## Structure overview

Here is what you will find in this repo:

- (`root`): this Readme instructions, and several jupyter notebooks
- `channels_for_sonification/`: epilepsy data from patient 1 and 2
- `computed_sonification_data/`: the computed data, ready to be sonified
- `dataset/`: where you should clone the [original dataset](https://openneuro.org/datasets/ds003029/versions/1.0.6) into
- `output/`: graph plots and rendered audio files


## Running notebooks

- Make sure you have [Python](https://www.python.org/) installed.
- navigate to folder directory
- create virtual environment
  - `python -m venv venv`
- activate virtual environment
  - `source venv/bin/activate`
- upgrade pip and setuptools
  - `pip install --upgrade pip setuptools`
- install jupyter notebook
  - `pip install notebook`
- run jupyter notebook
  - `jupyter notebook`
  - this will open a browser window/tab to open and run notebooks


## Related research

This code was used in the research papers:

Mannone, M., Itaboraí, P. V., Hamido, O. C., Goldack, M., Marwan, N., Fazio, P., & Ribino, P. (2026). _Sonified Quantum Seizures. Sonification of time series in epileptic seizures and simulation of seizures via quantum modelling_. **PDF/DOI: [10.5281/zenodo.18206481](https://doi.org/10.5281/zenodo.18206481)**

Itaboraí, P. V., Hamido, O. C., Marwan, N., Fazio, P., & Ribino, P., Mannone, M. (2026). _Quantum Seizures. Sonifying Quantum Modelling of Epileptic Time Series_. **In Review**
