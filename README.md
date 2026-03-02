# scrna-py-workflow

A practice workflow for processing and analyzing single-cell RNA data in Python. Currently in early development, so scope and implementation details may change. The first part involves following the Scanpy PBMC3k tutorial to get acquainted with scripting in Python. The second part is to reproduce a similar project structure for an scRNA-seq dataset on GEO. As an R/tidyverse user venturing into Python, I'd also like to acknowledge and boost [this relevant blog post](https://rebeccabarter.com/blog/2023-09-11-from_r_to_python) by Rebecca Barter and the [Python for Data Analysis](https://wesmckinney.com/book/) book by Wes McKinney.

## Project Plan

- [x] Establish and manage libraries and dependencies in a venv.
- [ ] **Part 1:** Reproduce and adapt the [Scanpy PBMC3k workflow](https://scanpy.readthedocs.io/en/latest/tutorials/basics/clustering-2017.html) as a tutorial exercise.
- [ ] **Part 2:** Apply the workflow to a GEO scRNA-seq dataset.
  - [ ] Identify single-cell RNA dataset available on GEO.
    - Treatment vs control study design, or variable with multiple groups.
    - Limited sample size to reduce time spent on sequencing files.
  - [ ] File processing.
  - [ ] Data preprocessing (QC, normalization).
  - [ ] Overview analysis (PCA).
  - [ ] Feature analysis (Scanpy).

## Recreate environment

After cloning and with `requirements.txt` available, run:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
