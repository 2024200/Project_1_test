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

[Tableau Link](<div class='tableauPlaceholder' id='viz1723827753910' style='position: relative'><noscript><a href='#'><img alt='Seattle ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;P1&#47;P1_House_Price_Prediction_Dashboard&#47;Seattle&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='P1_House_Price_Prediction_Dashboard&#47;Seattle' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;P1&#47;P1_House_Price_Prediction_Dashboard&#47;Seattle&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1723827753910');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='1366px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='795px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='1366px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='795px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='2077px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>)
