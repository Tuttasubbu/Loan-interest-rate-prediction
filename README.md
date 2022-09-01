## Risk based prediction of interest for loan
## Business objective
A company is in the financial lending business and provides loans to retail customers. It currently uses a process of first collecting certain customer information (attributes), analyzing it manually to decide whether the customer is eligible for a loan or not, and if eligible, telling the customer at what rate of interest rates it can avail the requested loan. Going forward the company wants to employ an automated process which is based upon a Machine Learning model. Not only is this model expected to make the decisioning process faster, but also keep it free from human error and biases.

## Approach
- Data collection
- Data wrangling
- Exploratory Data Analysis
- Feature engineering
- Feature scaling
- Choose the model
- Model Evaluation
- Parameter tuning
- Prediction
## Analysis/ Modeling Methodology
## Data Preparation & EDA
- Sub-setting is done by removing Loan_ID.
- All the missing values have been replaced with corresponding mean or mode.
- Extensive bi-variate analysis conducted on all meaningful variables.
## Variable Creation and Selection
- 20+ new variables created as a part of feature engineering.
- Used label encoding to create dummy variables.
- Used mapping techniques to map the object variables to numerical variables.
## Model Development
- Decision tree classifier chosen as the preferred modeling technique since the target variable is multiclass and data is complex.
- Developed 5+ candidate models.
- Highest Model accuracy observed of 74%.
## Model performance testing
- Conducted k-cross validation for k=5,10,15.
- Model performance also assessed on a hold-out sample of size 20% of the original dataset.
- Performed all the required metrics precision ,recall, confusion matrix ,roc_auc curve.
