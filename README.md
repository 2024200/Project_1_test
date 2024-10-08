### Description

There are two goals with this project;

1 ) To develop a robust machine learning model that accurately predicts house prices based on the features given. 

2 ) To create an interactive dashboard that allows stakeholders explore and visualise house price data.

### Dataset

The full dataset is linked here [Link](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

The cleaned dataset I used in the project [Link](https://github.com/2024200/Project_1_test/tree/b2e9eedebbd93fbb3fe70d8ea044c407148304cb/Dataset)

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

Available at:

|  | Notebook |
| --- | --- |
| Collab | [Collab](https://colab.research.google.com/drive/1_S51DZZhKQ_NYgNKOzUrctJGFQyeCevk?usp=sharing) |
| Kaggle | [Kaggle](https://www.kaggle.com/code/jldoyle/house-price-prediction) |
| Github | [Github](https://github.com/2024200/Project_1_test/blob/1fbc27bbda987a672ad7677bedb53d00799bacda/.ipynb_checkpoints/House_Data_Predictor-checkpoint.ipynb) |
| Tableau | [Dashboard](https://public.tableau.com/app/profile/jason.doyle5808/viz/P1_House_Price_Prediction_Dashboard/Seattle) |

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

<img width="687" alt="Screenshot 2024-08-13 at 22 00 28 copy" src="https://github.com/user-attachments/assets/925e302b-af37-4ec2-9ee7-c19e82811075">

### Visualisation

### [Tableau Link](https://public.tableau.com/views/P1_House_Price_Prediction_Dashboard/Seattle?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1512" alt="Dashboard" src="https://github.com/user-attachments/assets/d57a097d-0ef3-4280-85eb-d118ee8563cc">
