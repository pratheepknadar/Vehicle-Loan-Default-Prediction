# Vehicle Loan Default Predictor

#### Project Status: [100%]

### Project Objective
- The Purpose of this project is to predict whether a vehicle loan borrower will default with the used of imbalanced historical data. 

### Insights gained from the Data
- 26 columns are present out of which 7 are categorical variables
- It is an Imbalanced data (i.e. majority class : miniority class =  8 : 2 ) which can be fixed using oversampling.
- Missing is about 8%
- Heatmap for the correlation
 ![](https://i.imgur.com/hDNyj1p.png)

### Evaluation Metric: 
- ROC -AUC will be used as an evaluation metric.
- The reason for choosing ROC-AUC here, is because in this case we are predicting the loan default, which needs the reduction of both False positives and False Negatives.

### Methods Used
- Data Visualization
- Data mining
- Heatmap for finding correlation between features (multicollinearity)
- Normalization for scaling the features
- Cross-Validation
- Machine Learning Models ([No Free Lunch Theorem](https://analyticsindiamag.com/what-are-the-no-free-lunch-theorems-in-data-science/))
- Hyperparameter Tuning

### Technologies used
- Python and it's ML related libraries
- Jupyter Notebook
- Microsoft Excel

### Python Libraries
- Scikit-Learn, Feature-engine, pandas, numpy, etc

### Results
![](https://i.imgur.com/CvXEtG3.png)
- Best Model: <b> Cost sensitive Logistic Regression </b>
- Best parameters: <b> 1  {'class_weight': {0: 1, 1: 10}} </b>
- Mean Cross validation score of Best model: <b> 0.74 </b>

- Train score of bestmodel:<b> 0.760831036650548</b>
- Test score of best model:<b> 0.7524967361739767</b>
