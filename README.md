# Californa housing
This project is a school assignment containing a predictive modelling solution using Python's Scikit-learn machine learning modules to make predictions from the California housing-datset. 

## Classification Assignment
### Background: 
The client needs a tool to quickly assess new or "un-analyzed" areas. They have access to area features (geography, household composition, income levels, etc.) but not housing values. The goal is to rapidly answer: “Is this likely a high-value area?”

### Task:
1. Create a binary target high_value in historical data:
-  high_value = 1 if median_house_value is in the top 20%
-  high_value = 0 otherwise
2. Train a model to predict high_value using only the X variables (e.g., median_income, geography, household features, ocean_proximity)
3. Exclude median_house_value and high_value from the input features

### Purpose: 
Enable prioritization of areas and assessment of critical error types (e.g., missing a high-value area vs. false positives). The goal is not to predict exact prices, but to quickly flag areas likely to be high-value for resource allocation.

## Project structure
- `housing.csv` - dataset with historical housing data
- `housing_report.ipynb` - code, figures and result
- `Decision brief.pdf` - summary of goal, method, result, recommendations and risks

## Python version
- Python 3.13.7 (recommended)
- Important libraries: `numpy`, `pandas`, `matplotlib`, `scipy`, `sklearn`

## How to run the project
1. Clone repository: 
    ```bash
    git clone https://github.com/belson-h/PythonMLProject---California-Housing.git
2. Install necessary Python libraries: `pip install -r requirements.txt`
3. Open `housing_report.ipynb` i Jupyter Notebook.
4. Run all cells to reproduce analysis and visualisations. 