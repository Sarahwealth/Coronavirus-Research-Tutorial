![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
# CoronaVirus-Research
# SiddhantSharma : 27-03-2020 to 04-04-2020

A tutorial [Jupyter](https://jupyter.org/) Notebook illustrating how to use [Biopython](https://github.com/biopython/biopython) to identity and perform some basic characterization of a coronavirus genome sequence. Note, the use of a coronavirus genome is merely illustrative, the analyses are generic, and could be applied to any small genome.

## Viewing the Notebook

Simply open the [Notebook link here](https://github.com/ssiddhantsharma/Coronavirus-Research-Tutorial/blob/master/biopython-coronavirus-notebook.ipynb).

Or, view the notebook in [nbviewer](https://nbviewer.jupyter.org/github/ssiddhantsharma/Coronavirus-Research-Tutorial/blob/master/biopython-coronavirus-notebook.ipynb).

## Running the Notebook online

Via Binder :

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/chris-rands/biopython-coronavirus/master?filepath=biopython-coronavirus-notebook.ipynb)

## Running the Notebook locally

First clone this repository:
```
git clone https://github.com/chris-rands/biopython-coronavirus;
cd biopython-coronavirus
```

Requires Python (version 3.6 or higher) with the `jupyter` and `biopython` modules. One of two options is recommended:

1) Installation via [pip](https://pip.pypa.io/en/stable/)

```
pip3 install jupyter biopython
```

For installation without root access add the `--user` flag.

2) Installation via [conda](https://docs.conda.io/en/latest/)
  
```
conda env create -f environment.yml
conda activate biopython-coronavirus
```

Open the Notebook as follows:
```
jupyter-notebook biopython-coronavirus-notebook.ipynb
```

