# A Frequency-Based Biological Computer: From DNA Sequence to RF-Controlled Chemical Signaling

This repository contains a **minimal reproducible version** of the simulation code 
and the associated dataset supporting the manuscript:

**Title:** A Frequency-Based Biological Computer: From DNA Sequence to RF-Controlled Chemical Signaling

**Journal:** Bioinformatics (under review)

---

## Note

The code in this repository is a **minimal reproducible version** that illustrates 
the core modeling approach. The full implementation, including all parameters and 
extended analyses, is described in the Methods section of the manuscript.

---

## Contents

- `gfmh.text` — minimal simulation notebook illustrating the core model
- `RF_Codon_Table_64.csv` — codon table dataset used in the simulation (64 codons mapped to RF parameters)

---

## Dataset Description

`RF_Codon_Table_64.csv` contains the codon-to-RF mapping used in the frequency-based 
biological computer model. Each row corresponds to one of the 64 DNA codons, along 
with its associated RF frequency and chemical signaling parameters.

---

## Requirements

- Python 3.x
- Jupyter Notebook
- numpy
- scipy
- matplotlib
- pandas

---

## Usage

1. Install the required packages:

   ```bash
   pip install numpy scipy matplotlib pandas jupyter
