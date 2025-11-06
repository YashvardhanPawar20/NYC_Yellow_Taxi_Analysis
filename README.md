# NYC Yellow Taxi Analytics

This repository contains data cleaning notebooks, analysis notebooks, processed data outputs and models for NYC Yellow Taxi analytics.

Contents:
- `notebooks/` - Jupyter notebooks for cleaning, analysis, and ML experiments
- `data/raw/` - Raw input files (excluded from git)
- `data/processed/` - Cleaned/processed parquet files (excluded from git)
- `outputs/` - Generated reports and visualizations (excluded from git)

Quick start
1. Install dependencies (example):

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

2. Open notebooks in `notebooks/Data Cleaning/data_cleaning.ipynb` to run cleaning pipeline. The cleaning notebook writes cleaned parquet files to `data/processed/`.

Notes
- Large parquet files are excluded via `.gitignore`. If you need to store large files with GitHub, consider using Git LFS.
- Remote repository: https://github.com/YashvardhanPawar20/NYC_Yellow_Taxi_Analysis.git
