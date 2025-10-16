# Decoding Cell–Cell Communication Along the Gut–Brain Axis

**Single‑cell RNA‑seq analysis of mouse small intestine epithelium and enteric nervous system**

---

## Overview

This project explores how gut and brain cells communicate by integrating single‑cell RNA‑seq data from mouse intestinal epithelium and enteric neurons. Using classical bioinformatics and statistical tools, we identify ligand–receptor interactions and transcriptional programs underlying gut–brain signaling.

---

## Files & Structure

```
├─ preprocess.ipynb       # Preprocessing and QC of single‑cell data
├─ Analysis.ipynb         # Integration, analysis, and visualization
├─ requirements.txt       # Python dependencies
├─ README.md              # Project description
└─ data/                  # Input/output data (not included)
```

---

## How to Run

1. **Set up environment**

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
2. **Run notebooks in order**

   ```bash
   jupyter lab preprocess.ipynb
   jupyter lab Analysis.ipynb
   ```

---

## Data Sources

* Haber *et al.* (2017) – Mouse small intestinal epithelium, *Nature*.
* Drokhlyansky *et al.* (2020) – Mouse enteric nervous system, *Cell*.
