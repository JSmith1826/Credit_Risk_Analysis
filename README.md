# Credit_Risk_Analysis

## Overview

In this project we used Python and the Pandas library to prepare a dataset for a number of machine learning processes made possible by the imbalanced-learn and scikit-learn python packages. This is an example of supervised machine learning as we had a specific question we were looking to answer. In this case we using machine learning to predict credit risk. The dataset we utilized contained loan information from quarter 1 of 2019.

We ran six different machine learning processes once the data was in proper shape. The machine learning methods we used were:
- Naive Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

#### Resources
Data Source: LoanStats_2019Q1.csv
Software: Python 3.9.12, Conda 4.13.0, Jupyter Notebook 6.4.8




## Results
### Naive Random Oversampling
![N Random Oversample 1](/images/RandomOS_1.png)
![N Random Oversample 2](/images/RandomOS_2.png)
![N Random Oversample 3](/images/RandomOS_3.png)

**Balanced Accuracy Score: 66.6%**

Precision Score

    - High Risk: 1%
    - Low Risk: 100%

Recall

    - High Risk: 64%
    - Low Risk: 69%


### SMOTE Model
![SMOTE 1](/images/SMOTE_1.png)
![SMOTE 2](/images/SMOTE_2.png)
![SMOTE 3](/images/SMOTE_3.png)

**Balanced Accuracy Score: 62.5%**

Precision Score

    - High Risk: 1%
    - Low Risk: 100%

Recall

    - High Risk: 69%
    - Low Risk: 55%


### Cluster Cewntroid Undersampling
![Undersample 1](/images/Under_1.png)
![Undersample 2](/images/Under_2.png)
![Undersample 3](/images/Under_3.png)

**Balanced Accuracy Score: 62.5%**

Precision Score

    - High Risk: 1%
    - Low Risk: 100%

Recall

    - High Risk: 61%
    - Low Risk: 64%


### SMOTEENN Model (Combination Sampling)
![SMOTEENN 1](/images/Combo_1.png)
![SMOTEENN 2](/images/Combo_2.png)
![SMOTEENN 3](/images/Combo_3.png)

**Balanced Accuracy Score: 61.9%**

Precision Score

    - High Risk: 1%
    - Low Risk: 100%
Recall

    - High Risk: 69%
    - Low Risk: 55%

### Balanced Random Forest Classifier Model
![BRFC 1](/images/brfc_1.png)
![BRFC 2](/images/brfc_2.png)
![BRFC 3](/images/brfc_3.png)

**Balanced Accuracy Score: 78.7%**

Precision Score

    - High Risk: 4%
    - Low Risk: 100%

Recall

    - High Risk: 67%
    - Low Risk: 91%



### Easy Ensemble Classifying
![EEC 1](/images/eec_1.png)
![EEC 2](/images/eec_2.png)
![EEC 3](/images/eec_3.png)

**Balanced Accuracy Score: 92.5%**

Precision Score

    - High Risk: 7%
    - Low Risk: 100%

Recall

    - High Risk: 91%
    - Low Risk: 94%





## Summary

When comparing which model to recommend going forward for this particular lender there are a few factors we must consider. If the ultimate goal is to minimize borrower defaults by implementing a very tight approval process that will be more likely to reject worthy applications. Having a very tight lending policy laser focused on minimizing risk could ultimately become a competitive disadvantage and lead to a reduction of revenue.

There is also of course the other side of the coin if we don't have a sufficiently strict model that is more apt to pass through more applications that should have been flagged 'high risk' for additional scrutiny. The lender would surely appreciate the uptick in volume but with that the additional risk down the line must be considered. 

Ultimately the decision about the risk-tolerance of the company must be made at the executive level and shareholder level. The data collected as part of this study should be invaluable to all stakeholders.


Best Balanced Accuracy Score - Best Overall Performance
1. 1. Easy Ensemble Classifying: 92.5%
2. Balanced Random Forrest Classifier: 78.7%
3. Naive Random Oversampling: 66.6%


Ranked by Best Recall Rate (What percentage of high-risk loans were correctly flagged in testing)
1. Easy Ensemble Classifying: 91%
2a. SMOTEENN: 69%
2b. SMOTE: 69%


### Cluster Cewntroid Undersampling
![Undersample 1](/images/Under_1.png)
![Undersample 2](/images/Under_2.png)
![Undersample 3](/images/Under_3.png)
Balanced Accuracy Score: 62.5%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 61%
    - Low Risk: 64%

### SMOTEENN Model (Combination Sampling)
![SMOTEENN 1](/images/Combo_1.png)
![SMOTEENN 2](/images/Combo_2.png)
![SMOTEENN 3](/images/Combo_3.png)
Balanced Accuracy Score: 61.9%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 69%
    - Low Risk: 55%

### Balanced Random Forest Classifier Model
![BRFC 1](/images/brfc_1.png)
![BRFC 2](/images/brfc_2.png)
![BRFC 3](/images/brfc_3.png)

Balanced Accuracy Score: 78.7%
Precision Score:
    - High Risk: 4%
    - Low Risk: 100%
Recall
    - High Risk: 67%
    - Low Risk: 91%



### Easy Ensamble Classifying
![EEC 1](/images/eec_1.png)
![EEC 2](/images/eec_2.png)
![EEC 3](/images/eec_3.png)
Balanced Accuracy Score: 92.5%
Precision Score:
    - High Risk: 7%
    - Low Risk: 100%
Recall
    - High Risk: 91%
    - Low Risk: 94%




## Summary

When compairing which model to reccomend going forward for this particular lender there are a few ffactors we must consider. If the ultimate goal is to minimize borrrower defaults by inplimenting a very tight approval process that will be more likely to reject worthy applications. Having a very tight lending policy laser focused on minimizing risk could ultimately become a competative disagvantage and lead to a reduction of revenue.

There is also of course the other side of the coin if we don't have a sufishently scrict model that is more apt to pass through more applications that should have been flagged 'high risk' for additional scruteny. The lender would surely apprichiate the uptick in volumn but with that the additional risk down the line must be considered. 

Ultimately the decision about the risk-tolerance of the company must be made at the execuitive level and shareholder level. The data collected as part of this study should be invaluable to all stakeholders.


Best Balanaced Accuracy Score - Best Overall Profomance
1. 1. Easy Ensemble Classifying: 92.5%
2. Balanced Random Forrect Classifier: 78.7%
3. Naive Random Oversampling: 66.6%


Ranked by Best Recall Rate (What percentage of high-risk loans were correctly flagged in testing)
1. Easy Ensemble Classifying: 91%
2a. SMOTEENN Combination: 69%
2b. SMOTE: 69%
