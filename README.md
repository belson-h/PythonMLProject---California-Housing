# Californa housing - Classification Project
This project is a school assignment focused on predictive modeling using Python's scikit-learn library. The goal is to build a classification model using the California Housing dataset to identify high-value areas for decision support.

## Project Overviervie
In this assignment, I act as a data analyst at a consulting firm supporting municipalities and real estate stakeholders in making data-driven decisions. The task is to develop a machine learning solution using the California Housing dataset to identify “high-value areas”, regions where housing prices are in the top 20%.

The work includes preparing the dataset, performing exploratory data analysis, engineering relevant features, and building reproducible classification pipelines using scikit-learn. Models are evaluated with cross-validation, optimized using GridSearchCV, and compared to select the best-performing solution.

The final deliverables are a runnable Jupyter Notebook containing the full analysis and a concise report summarizing methodology, results, recommendations, and potential risks. The goal is not to predict exact housing values but to provide a reliable tool for flagging likely high-value areas based on available area-level characteristics, such as income, household structure, geography, and proximity to the ocean.

## Project structure
- `housing.csv` - dataset containing historical housing data
- `housing_report.ipynb` - Jupyter Notebook with all code, figures, and results
- `report_summary.pdf` - concise report summarizing goal, methods, results, recommendations, and risks

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