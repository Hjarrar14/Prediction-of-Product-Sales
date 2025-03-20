# Prediction-of-Product-Sales
- Hisham Jarrar
## Introduction
- sales prediction for food items sold at various stores
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




