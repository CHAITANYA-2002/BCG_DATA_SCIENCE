# BCG Data Science: Customer Churn Analysis

Data science case study focused on understanding customer churn drivers for an energy provider scenario. The notebooks walk through exploratory analysis, price-sensitivity investigation, feature engineering, and prediction outputs.

## Project Highlights

- Explores customer, pricing, and churn datasets with pandas-based analysis.
- Investigates whether price changes are related to churn behavior.
- Builds customer-level features such as tenure, off-peak price differences, and categorical encodings.
- Produces an out-of-sample prediction file for downstream review.

## Repository Structure

```text
BCG_DATA_SCIENCE/
|-- Exploratory_Data_Analysis_BCG.ipynb
|-- Feature_engineering_BCG.ipynb
|-- client_data.csv
|-- price_data.csv
|-- churn_data_modeling.csv
|-- out_of_sample_data_with_predictions.csv
```

## Workflow

1. Load `client_data.csv` and `price_data.csv`.
2. Review missing values, column types, churn distribution, and consumption patterns.
3. Analyze price sensitivity using off-peak price changes across time windows.
4. Engineer tenure, date, boolean, categorical, and numerical features.
5. Prepare the modeled churn dataset and out-of-sample predictions.

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Analysis | pandas, NumPy |
| Visualization | matplotlib, seaborn |
| Modeling | scikit-learn |
| Environment | Jupyter Notebook |

## Getting Started

```bash
git clone https://github.com/CHAITANYA-2002/BCG_DATA_SCIENCE.git
cd BCG_DATA_SCIENCE
python -m venv .venv
.venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Open the notebooks in this order:

1. `Exploratory_Data_Analysis_BCG.ipynb`
2. `Feature_engineering_BCG.ipynb`

## Notes

This repository is best read as a data science workflow: hypothesis, exploration, feature design, model-ready data, and prediction output.
