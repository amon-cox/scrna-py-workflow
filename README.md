# scrna-py-workflow

A practice workflow for processing and analyzing single-cell RNA data in Python.

## Project Plan

- [x] Establish and manage libraries and dependencies in a venv.
- [ ] Identify single-cell RNA dataset available on GEO.
  - Treatment vs control study design, or variable with multiple groups.
  - Limited sample size to reduce time spent on sequencing files.
- [ ] File processing.
- [ ] Data preprocessing (QC, normalization)
- [ ] Overview analyses (PCA)
- [ ] Feature analysis (Scanpy)

## Recreate environment

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
