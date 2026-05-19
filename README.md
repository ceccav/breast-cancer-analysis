# Breast Cancer Analysis (KK1)

This repository contains my KK1 exploratory data analysis notebook.
The project analyzes breast cancer measurement data using pandas, NumPy, matplotlib, and seaborn.

## Dataset

- Name: Breast Cancer Prediction Dataset
- Source: Kaggle
- Link: https://www.kaggle.com/datasets/merishnasuwal/breast-cancer-prediction-dataset
- Local file: data/Breast_cancer_data.csv

One row represents one patient, with five measurements and a diagnosis label:
- 0 = benign
- 1 = malignant

## Notebook

- Main file: notebook.ipynb
- Analysis flow:
1. Context and research questions
2. Loading and mechanical inspection
3. Motivated data cleaning pipeline
4. Visual exploration (boxplot, histogram, heatmap, correlation bar chart, scatterplot)
5. Final reflection and limits of the data

## How to run

1. Create and activate environment (already configured here with uv/.venv).
2. Open notebook.ipynb in Jupyter.
3. Run all cells from top to bottom.

## Plot conventions used

- Titles are written as claims, not only labels.
- Axis labels are written for the viewer and include units where possible.
- For this dataset, the source does not provide physical measurement units in the file; I label these as relative units.
- Important findings are annotated directly in charts (for example overlap zone and strongest feature).

## Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook
- uv