## For April Seminar

## This consists of the code and dataset

## About this project

Malware is a serious threat to the security of computer systems, and traditional signature-based methods are ineffective in detecting new and unknown malware samples.  As a result, there is a pressing need for effective malware detection systems that can identify and prevent malware from infecting systems. In this paper, we propose a malware detection system using deep learning. The proposed system uses a deep neural network to learn the features of malware samples and classify them into different categories. We evaluate the performance of the proposed system on a dataset of real-world malware samples and show that it achieves high accuracy in detecting malware.

The rapid increase in the use of computer systems and the internet has led to a rise in the number of malware attacks. Malware refers to malicious software that is designed to harm computer systems or steal sensitive information from them. Malware can be spread through various means, such as email attachments, downloads from the internet, or through vulnerabilities in software. In recent years, machine learning has shown great promise in various fields, including malware detection. Machine learning models can learn the features of malware samples and classify them into different categories.

# Packages used

// For pre-processing
from sklearn.preprocessing import OneHotEncoder, StandardScaler
from sklearn.compose import ColumnTransformer

// For splitting data into training and testing
from sklearn.model_selection import train_test_split

// metrics for calculations
from sklearn.metrics import mean_squared_error, r2_score,mean_absolute_error

// various machine learning models
from sklearn.neighbors import KNeighborsRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.ensemble import RandomForestRegressor,AdaBoostRegressor
from sklearn.svm import SVR
from sklearn.linear_model import LinearRegression, Ridge,Lasso
from catboost import CatBoostRegressor
from xgboost import XGBRegressor

// for data visualization 
import matplotlib.pyplot as plt
import seaborn as sns

// for hyperParameterTuning
from sklearn.model_selection import RandomizedSearchCV
from sklearn.model_selection import GridSearchCV
