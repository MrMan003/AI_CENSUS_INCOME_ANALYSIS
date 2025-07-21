# AI Census Income Analysis

A machine learning project that analyzes and predicts income levels based on U.S. Census demographic data. This project uses supervised learning models to classify whether an individual's income is above or below $50K/year.

## Objective

To build an AI system that:
- Analyzes demographic attributes from census data
- Predicts income category using classification models
- Helps understand income distribution patterns

##  Dataset

- **Source:** UCI Machine Learning Repository – Census Income (Adult) dataset
- **Attributes:** Age, education, occupation, race, sex, hours worked per week, etc.
- **Target:** Income (`<=50K` or `>50K`)

## Features

- Data cleaning, handling missing values
- EDA: Distribution plots, correlation heatmaps
- Feature encoding and normalization
- Machine learning models: Logistic Regression, Decision Tree, Random Forest, SVM
- Model evaluation: Accuracy, precision, recall, F1-score

##  Tech Stack

- **Language:** Python
- **Libraries:**
  - `pandas` for data manipulation
  - `matplotlib` & `seaborn` for data visualization
  - `scikit-learn` for ML models and evaluation
  - `numpy` for numerical computations

## Project Structure

```

├── ai\_census\_income\_analysis.py
├── README.md
├── data/
│   └── adult.csv
└── models/
└── trained\_model.pkl

```

## Usage

1. Clone the repo  
   `git clone https://github.com/yourusername/AI_Census_Income_Analysis.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the script  
   `python ai_census_income_analysis.py`

## Sample Output

- Accuracy: 85%+ on test data
- Feature importance plots
- Confusion matrix visualization

## Future Improvements

- Add web UI using Streamlit or Flask
- Deploy model via API
- Hyperparameter tuning with GridSearchCV

---

> Developed by Mitul Pabri  
>  Thapar Institute of Engineering & Technology  
> Semester: Jan – May 2025
```
