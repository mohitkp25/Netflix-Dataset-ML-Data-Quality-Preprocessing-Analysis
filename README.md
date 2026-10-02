# Netflix Data Quality and ML Readiness

A project exploring data quality, preprocessing, visualization, and machine-learning readiness using a Netflix titles dataset. The analysis covers missing values, inconsistent formats, feature encoding and scaling, exploratory visualizations, and a comparison of model performance before and after preprocessing.

# TASKS 

PART 1: Data Understanding & Quality Issues 
- Load the dataset and inspect the shape, data types, and missing values. 
- Identify at least five data quality issues and explain them briefly. 

PART 2: Data Cleaning & Preprocessing 
- Handle missing values with justification.
- Explain why a particular technique(dropping,filling with mean/median) was chosen and its impact on data quality 
- Convert data into correct formats (dates, duration). 
- Encode categorical variables. 
- Normalize or standardize numerical features. 

PART 3: Data Visualization 
- One distribution plot.
- One categorical count plot.
- One numerical comparison plot.
- Provide interpretation for each plot.

PART 4: ML Readiness Check 
- Select a target variable.
- Train Logistic Regression or Decision Tree.
- Compare performance before and after preprocessing.

## Project Contents

- `Netflix_ML_Assignment_With_Markdown.ipynb` - Notebook walkthrough of the assignment using the included Netflix titles CSV.
- `netflix_titles.csv` - Dataset loaded by the notebook.

## Requirements

Python 3 and pip are required. Install the packages used by the notebook and standalone script:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

## Run the Notebook

From this directory, start Jupyter:

```bash
jupyter notebook Netflix_ML_Assignment_With_Markdown.ipynb
```

Run the cells in order. The notebook reads `netflix_titles.csv` from the project directory.

## Run the Standalone Script

From this directory, run:

```bash
python netflix_complete_source.py
```

The script creates a synthetic dataset named `netflix_data.csv` and saves the analysis figures in the current working directory. This generated dataset is separate from `netflix_titles.csv`, which is used by the notebook.

## Notes

- Run commands from the project directory so relative dataset and output paths resolve as expected.
- Generated CSV and image files are created when the standalone script runs; they are not required to launch the notebook.
