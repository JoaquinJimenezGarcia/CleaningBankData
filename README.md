# CleaningBankData
### Project Overview

This repository contains a data cleaning and preprocessing project focused on banking and marketing datasets.
The main deliverable is a Jupyter Notebook that demonstrates cleaning, merging, and preparing data from several CSV sources (e.g., client.csv, campaign.csv, economics.csv, bank_marketing.csv) for further analysis or modeling.

### Repository Structure

├── bank_marketing.csv # Raw data related to bank marketing campaigns
├── campaign.csv # Campaign data
├── client.csv # Client or customer data
├── economics.csv # Macroeconomic indicators
├── notebook.ipynb # Main Jupyter notebook with all data cleaning steps
└── piggy_bank.jpg # Decorative image (optional)

### Key Goals & Scope

- Load and inspect raw CSV datasets

- Perform exploratory data analysis (EDA) to detect data quality issues (missing values, duplicates, inconsistent data types)

- Clean and preprocess each dataset: handle missing data, correct types, normalize, and merge datasets

- Produce a final cleaned dataset ready for modeling or further analysis

- Document the cleaning logic and rationale in the notebook

## Usage

- Clone this repository:
```
git clone https://github.com/JoaquinJimenezGarcia/CleaningBankData.git

cd CleaningBankData
```
- Ensure you have Python 3.x and dependencies installed:
```
pip install -r requirements.txt
```
(If requirements.txt doesn’t exist yet, see the suggested dependencies below.)

- Launch Jupyter Notebook:
```
jupyter notebook
```

- Open and run notebook.ipynb sequentially to reproduce all steps.

## Dependencies

Typical libraries required:

- pandas

- numpy

- matplotlib

- seaborn

- (optional) scikit-learn for scaling or encoding

- jupyter

### You can create a simple requirements.txt like this:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Design Decisions & Notes

The project is exploratory, designed to teach or demonstrate the main cleaning steps.

Each operation is explained inside the notebook for transparency.

The process is interactive; re-run all cells from top to bottom to ensure consistency.

The datasets are processed independently before merging, with clear handling for missing and inconsistent values.

Possible Improvements

Convert the notebook cleaning logic into reusable Python scripts or functions.

Add automated data validation (e.g., with pytest or great_expectations).

Export cleaned datasets automatically at the end of the pipeline.

Add dataset metadata or documentation.

Include Makefiles or orchestration tools for reproducibility.

License

Specify your license of choice (e.g., MIT or Apache 2.0).

Contact

For questions or collaboration, contact Joaquin Jimenez Garcia via GitHub:
https://github.com/JoaquinJimenezGarcia