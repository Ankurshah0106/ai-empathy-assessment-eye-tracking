# AI System to Assess Empathy from Eye-Tracking Data

This repository contains EyeT eye-tracking datasets and preprocessing resources for empathy-focused analysis and model development.

## Key Highlights

- Large-scale eye-tracking CSV datasets across participants and trials
- Preprocessing notebook for data cleaning and feature preparation
- Supporting documentation for schema and coordinate system
- Ready foundation for downstream empathy prediction experiments

## Repository Contents

- `Pre-Processing.ipynb` - Data cleaning and preprocessing notebook
- `columns_explained.pdf` - Column-level documentation
- `coordinate_system.pdf` - Coordinate reference documentation
- `EyeT_group_dataset_*.csv` - Raw eye-tracking trial data files

## Suggested Workflow

1. Open `Pre-Processing.ipynb` in Jupyter or Google Colab.
2. Point notebook paths to CSV files in this repository.
3. Run preprocessing steps to generate cleaned/model-ready data.
4. Use processed outputs for empathy assessment models.

## Notes

- Large CSV files are included directly in this repository.
- Processing time depends on your system memory and CPU.
- For collaboration, consider Git LFS if repository size grows further.
