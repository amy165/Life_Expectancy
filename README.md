# Life Expectancy — Exploratory Analysis & Prediction

## Project overview
This project explores a  the **life expectancy** datasets provided by the course and builds a simple
predictive model to understand which factors have the strongest impact on
life expectancy across countries.

The goal was not only to train a model, but mainly to:
- clean and prepare the data properly
- explore relationships between variables
- visualize insights clearly
- evaluate model performance in a simple and transparent way

This project was developed as part of my learning path toward
Data Analytics / Data Science.

Course: https://www.udemy.com/course/ciencia-de-datos-en-python-en-7-dias/

---

## Dataset
The dataset includes country-level indicators such as:

- Life expectancy
- GDP
- Health expenditure
- Education indicators
- Population metrics
- Mortality and disease-related variables

- Due to license restrictions, the dataset is not included in this repository.
Please download it from the course platform and place it inside the folder:

/data/Life_Expectancy.csv

---

## Data cleaning
Main steps included:

✔ handling missing values  
✔ checking distributions and outliers  
✔ renaming columns for clarity  
✔ converting data types  
✔ selecting relevant features for modeling  

I documented each step inside the notebook to keep the analysis reproducible.

---

##  Exploratory Data Analysis (EDA)

I explored:

- correlations between features and life expectancy
- relationships through scatter plots and pair plots
- differences across countries and regions
- impact of healthcare and economic indicators

Tools used for visualization:

- `Matplotlib`
- `Seaborn`

The EDA helped identify patterns and select useful variables for modeling.

---

##  Modeling

A simple regression pipeline was implemented using **scikit-learn**.

Models explored included:

- Linear Regression
- (optionally) Regularized models / tree-based models, depending on tests

Evaluation metrics:

- **R²**
- **MAE**
- **RMSE**

The objective was interpretability rather than maximizing performance at all cost.

---

##  Key insights
Some examples of insights obtained:

- countries with higher investment in healthcare tend to show higher life expectancy
- economic indicators correlate, but not always linearly
- some variables appear redundant and required feature selection
- cleaning and preprocessing had a strong effect on model stability

More details and visualizations are available inside the notebook.

---

##  Tech stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  How to run

1. Clone the repository
2. Install requirements (if needed)
