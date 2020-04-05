![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
## Coronavirus-Research
### SiddhantSharma : 27-03-2020 to 04-04-2020

A tutorial [Jupyter](https://jupyter.org/) Notebook illustrating how to use [Biopython](https://github.com/biopython/biopython) to identity and perform some basic characterization of a coronavirus genome sequence. Note, the use of a coronavirus genome is merely illustrative, the analyses are generic, and could be applied to any small genome.

## Viewing the Notebook

Simply open the [Notebook link here](https://github.com/ssiddhantsharma/Coronavirus-Research-Tutorial/blob/master/biopython-coronavirus-notebook.ipynb).

Or, view the notebook in [nbviewer](https://nbviewer.jupyter.org/github/ssiddhantsharma/Coronavirus-Research-Tutorial/blob/master/biopython-coronavirus-notebook.ipynb).

## Running the Notebook online

Via Binder :

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ssiddhantsharma/Coronavirus-Research-Tutorial/master?urlpath=https%3A%2F%2Fgithub.com%2Fssiddhantsharma%2FCoronavirus-Research-Tutorial%2Fblob%2Fmaster%2Fbiopython-coronavirus-notebook.ipynb)

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

### Open questions
- How is orf1ab cleaved into polypeptides? Can we predict this from the sequence?
- How do the researchers know (guess?) where orf1ab cleaves?
  - nsp3 and nsp5 do it -- https://www.pnas.org/content/pnas/103/15/5717.full.pdf
- Which protein is the immune system responding to?
  - "spike" and "nucleocapsid" -- http://www.cmi.ustc.edu.cn/1/3/193.pdf
  - Are some people already immune from exposure to other coronavirus?
- Find the "furin cleavage site" in the "spike glycoprotein"
  - It might be at the "PRRA" -- https://www.sciencedirect.com/science/article/pii/S0166354220300528
  - Use ProP or PiTou to predict? -- https://en.wikipedia.org/wiki/Furin
- How similar are the other coronaviruses? (causes colds, not either SARS or MERS)
  - alpha
    - https://en.wikipedia.org/wiki/Human_coronavirus_229E (simpler, though targets APN)
    - https://en.wikipedia.org/wiki/Human_coronavirus_NL63 (targets ACE2!)
      - https://www.ncbi.nlm.nih.gov/nuccore/MG772808
  - beta
    - https://en.wikipedia.org/wiki/Human_coronavirus_OC43 (targets Neu5Ac)
      - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2095096/pdf/JIDMM17330.pdf
      - Specifically, how similar is the N protein OC43, SARS v1, and SARS v2?
    - https://en.wikipedia.org/wiki/Human_coronavirus_HKU1 (targets Neu5Ac)
    - MERS-CoV
    - SARS-CoV
    - SARS-CoV-2
- What adds the phosphate group to the N protein? Kinase?


 


