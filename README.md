# Prediction-of-Product-Sales
## Introduction
- sales prediction for food items sold at various stores
--------
- Author: Hisham Jarrar
### Description
- sales prediction for food items sold at various stores. The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales.

## Data Scorce:
- (https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=drive_link)

## Data Dictionary
<img width="786" alt="Data Dictionary" src="https://github.com/user-attachments/assets/b8c7a379-8192-48df-9f03-87048781c6be" />

----

***After preparing and cleaning the data, we created visualizations to understand and analyze it.***

# Exploratory Data Analysis

### In this project, we used four types of plots, each serving a specific purpose for displaying and understanding the data.

  - *Histograms to view the distributions of numerical features.*
    
  - *Boxplots to view statistical summaries of numerical features.*
    
  - *Countplots to view the frequency of each class of categorial features.*
    
  - *Heatmap to view the correlation between features.*


## Histograms Plots
- Histograms to view the distributions of numerical features.
  ![Product Sales Prediction Image](https://github.com/user-attachments/assets/de325cdd-bf90-4e79-86f6-cce087ee4ee5)




## Box plots
- Boxplots to view statistical summaries of numerical features.
![Statistical Analysis](https://github.com/user-attachments/assets/1ce13a45-e2a5-4b51-b85e-3e2ba82c332f)

***By observing the chart and the statistical summaries for “Item_Visibility,” we can notice that the vast majority of values fall below 0.20. This suggests that most items are not highly visible, and the presence of some higher values warrants further exploration to understand the potential reasons behind these outlier values. As for the median, which is approximately 0.06, this indicates that half of the values are below this number.***



## Count plots
- Countplots to view the frequency of each class of categorial features.![Frequency (1)](https://github.com/user-attachments/assets/37f21f17-d94a-4dad-ab8b-e65bedb97695)

***As we can see in the chart for the frequency of outlet_location_type, Tier 3 dominates, indicating a larger number of stores in small towns or rural areas compared to stores in medium-sized cities and urban areas (Tier 2 & Tier 1).***


## Heatmap 
- Heatmap to view the correlation between features.

![Product Sales Heatmap](https://github.com/user-attachments/assets/ddd93a7f-3318-45bb-b587-2ccb629e7807)

***As we can see in the heatmap, we have two positive correlations:***
- ***Between Item_MRP and Item_Outlet_Sales, where the correlation is 0.54.***
- ***Between Item_Weight and Outlet_Establishment_Year, where the correlation is  0.54.***

----
# Modeling

> - During the modeling process, we used the following models:

	•	Linear Regression Model

	•	Random Forest Model
 
	•	Tuned Random Forest Model

 ## Models Evaluated & Results
 
- Linear Regression Model Results :
  - (Training Data):
    - MAE = 847.129
    - MSE = 1,297,558.136
    - RMSE = 1,139.104
    - R^2 = 0.562
  - (Test Data):
    - MAE = 804.120
    - MSE = 1,194,349.715
    - RMSE = 1,092.863
    - R^2 = 0.567

- Random Forest Model Results :
  - (Training Data):
    - MAE = 296.383
    - MSE = 182,992.934
    - RMSE = 427.777
    - R^2 = 0.938
  - (Test Data):
    - MAE = 767.103
    - MSE = 1,215,476.625
    - RMSE = 1,102.487
    - R^2 = 0.559

- Tuned Random Forest Model Results:
  - (Training data):
    - MAE = 756.226
    - MSE = 1,154,413.205
    - RMSE = 1,074.436
    - R^2 = 0.610
  - (Test Data):
    - MAE = 730.396
    - MSE = 1,103,475.652
    - RMSE = 1,050.464
    - R^2 = 0.600
   
  ----
## Recommendation for the Tuned Random Forest Model
- After evaluating multiple models and analyzing performance results on both the training and testing datasets, I recommend using the Tuned Random Forest Model. It offers the best balance and consistency between training and testing results, and also demonstrates the highest overall performance.

- R-squared (R²) Metric
  - We use this metric to understand how well the model makes predictions.
    
  - The R² value for the testing data is 0.60, which means the model is able to explain 60% of the changes in sales.

- RMSE Metric
  - We use this metric to express the accuracy of the predictions, as it represents the average amount of error between the actual values and the predicted values made by the model.
    
  - The RMSE for the testing data is $1050.46, which means the model makes an average error of about $1050.
    
  - I chose this metric because it is easy to interpret and also penalizes large prediction errors more heavily.




