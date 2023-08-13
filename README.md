# Wine_Quality_Prediction

Using Machine Learning Algorithms for Regression Analysis, Data Visualization, and Data Analysis to Predict Red Wine Quality.

## Description

### Context

The two datasets contain physicochemical and sensory data for red and white variant wines from the Portuguese Vinho Verde region. As referenced in Cortez et al., 2009, due to privacy and logistical considerations, information beyond physicochemical inputs and sensory outputs was not available (e.g., grape varietals, brands, prices). 

The datasets can be modeled as either classification tasks predicting quality scores or regression tasks predicting continuous quality ratings. The classification labels represent ordered imbalanced classes, with many more normal wines than excellent or poor ones. 

The data is also hosted on the UCI machine learning repository for public access (https://archive.ics.uci.edu/ml/datasets/wine+quality), though it has been shared here to provide more accessible options for experimentation. This is believed to comply with license terms, but the datasets will be removed if unauthorized based on rights holder requests.

### Tips
In addition to regression modeling, an interesting analysis would be to establish a binary cutoff for wine quality, such as classifying wines with a score of 7 or higher as 'good' (1) and lower scores as 'not good' (0). This formulation as a classification task enables hyperparameter tuning and evaluation of algorithms like decision trees based on performance metrics including ROC curves and AUC value. Without extensive feature engineering or overfitting, baseline decision tree models can achieve an AUC of approximately 0.95 on this dataset. To further improve performance, techniques like random forest ensembles were explored. Setting an arbitrary quality threshold facilitates practicing binary classification techniques, parameter tuning, and performance measurement using ROC and AUC - valuable skills in applied machine learning.
