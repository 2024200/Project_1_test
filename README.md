### Description

There are two goals with this project;

1 ) To develop a robust machine learning model that accurately predicts house prices based on the features given. 

2 ) To create an interactive dashboard that allows stakeholders explore and visualise house price data.

### Dataset

The full dataset is linked here [Link](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

The cleaned dataset I used in the project (*Upload to Github and link*)

21060 entries, total 15 columns - Memory Usage: 2.4+ MB

### Notebook

Models used 

- Linear Regression
- Polynomial Regression
- Ridge
- Lasso
- Elastic Net
- XGB

Final model

- XGBoost - {'learning_rate': 0.1, 'max_depth': 5, 'n_estimators': 300}

### Tech-stack + Libraries

- **Python version**: 3.10.12
- **Packages**: pandas, numpy, matplotlib, seaborn, sklearn, xgboost
- **Visualization Tool**: Tableau

### **Results**

| Metric | Value |
| --- | --- |
| R² Test Score | 0.87 |
| R² Train Score | 0.91 |
| Test Root Mean Squared Error | 81951.69 |
| Train Root Mean Squared Error | 71595.41 |
| Mean Absolute Error | 6716080061.49 |

![Screenshot 2024-08-13 at 22.00.28.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/c303fd20-d8be-482e-9e21-9dcd5c5d2b0d/bb1f17e2-6c46-42d7-9674-d41300e51999/Screenshot_2024-08-13_at_22.00.28.png)

### Visualisation

[(*Embed Tableau Dashboard*)](https://github.com/dinkwiz/tableau_embed?tab=readme-ov-file)
