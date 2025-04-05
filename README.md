# EDA-Projects---April
Student's EDA Project works
# **Wine Quality**



## 1. Goal of the Dataset

 To analyze wine ratings, price variations, and customer preferences based on wine attributes like body, acidity, and type.

## 2. Description of Dataset

 This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression tasks. The classes are ordered and not balanced (i.e. the quality goes from almost 5 to 4 points). The task is to predict either the quality of wine or the prices using the given data.

## 3. About the Dataset

 The dataset contains 7500 different types of red wines from Spain with 11 features that describe their price, rating, and even some flavor description. This was collected using web scraping from different sources (from wine specialized pages to supermarkets).


![image](https://github.com/user-attachments/assets/6eddf5b9-f235-40c6-a344-e3c01f07f24f)

## **Final Report**

> - Outliers are removed using IQR method
> - Scaled (standard scaler)
> - Skeweness handled





* The LGBM Regressor demonstrated the best performance across all metrics, with the lowest MSE (0.2332), lowest MAE (0.3574), and highest R² score (0.7717). This indicates that it makes the most accurate predictions among the models tested.
* LGBM Regressor is the best choice for this dataset as it outperforms all other models in accuracy and error minimization.
