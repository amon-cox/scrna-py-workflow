# scrna-py-workflow

A practice workflow for processing and analyzing single-cell RNA data in Python.

- Establish and manage libraries and dependencies in a venv.
- Identify single-cell RNA dataset available on GEO.
  - Treatment vs control or variable with multiple groups.
  - Lower sample size to reduce time on processing FASTQ files.
- File processing.
- Data preprocessing (QC, normalization)
- Overview analyses (PCA)
- Feature analysis (Scanpy)

## Recreate environment

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
