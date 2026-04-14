# Telco-Customer-Churn Data-Analysis

This project was created as part of a university course. The goal is to perform descriptive data analysis on a telecommunications dataset and explore patterns related to customer churn in R.


##  Authors

- [Justyna Dudek](https://github.com/Justa555)
- [Aleksandra Tylman](https://github.com/AleksandraTylman)


## Data Overview

- **Source:** WA Fn-UseC -Telco-Customer-Churn.csv [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Content:**  21 features and 7043 records  

##  Project Highlights

###  Data Preparation

- Correcting data types (`factor`, `numeric`)  
- Removing identifier column (`customerID`)  
- Handling missing values (`NA`)  
- Replacing non-standard missing values:
  - `"No internet service"`  
  - `"No phone service"`  

### Analysis

#### Quantitative variables

- Measures of central tendency and dispersion  
- Histograms and density plots  
- Boxplots and violin plots  
- Scatter plots and 3D visualization  

#### Categorical variables

- Frequency tables and proportions  
- Bar charts and pie charts  
- Analysis of services, contracts, and payment methods  

### Churn Analysis

Comparison between:

- **Churn = Yes** (customers who left)  
- **Churn = No** (loyal customers)  

Includes:

- Statistical comparison  
- Distribution analysis  
- Visualization of differences between groups  

### Conclusions 

- Summary of performed analysis, including insights and recommendations for business decision-making based on customer behaviour patterns and churn characteristics.

## Tools

- **R Markdown** – combining analysis, code, and results in one report  
- **R** with libraries: `knitr`, `dplyr`, `ggplot2` , `kableExtra`, `xtable` , `patchwork`, `gridExtra` ,`e1071`, `modeest`  


## Note

Since this project was created as part of a university course, report is written in Polish.
