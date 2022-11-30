#WEATHER FORECASTING USING MACHINE LEARNING

## PROJECT DESCRIPTION

The main objective of this project is to predict the weather based on a daily basis using various models

>the primary variables used are  precipitation ,temp_min, temp_max and wind

>the accuracy of our models :
KNN:77%
SVM:78%
Gradient Boosting:81%
XGboosting:83%


## Requirements

We have used a Jupyter notebook to run our project and we can run it on google collab or kaggle
libraries used:
 matplotlib.pyplot 
 seaborn 
 scipy
 re
 missingno 
 stats
from scipy.stats import ttest_ind
from scipy.stats import pearsonr
from sklearn.preprocessing import StandardScaler,LabelEncoder
from sklearn.model_selection import train_test_split 
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
from sklearn.ensemble import GradientBoostingClassifier
from xgboost import XGBClassifier
from sklearn.metrics import accuracy_score,confusion_matrix,classification_report

Data set used :seattle-weather.csv from kaggle




