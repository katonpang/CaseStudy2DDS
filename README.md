# Frito Lay Attrition Study

## Overview

DDSAnalytics is an analytics company specializing in talent management solutions for Fortune 100 companies. Talent management encompasses various aspects, such as workforce planning, employee training programs, identifying high-potential employees, and minimizing voluntary employee turnover (attrition). The analysis and study conducted by DDSAnalytics specifically focused on the employee attrition component, aiming to identify influential factors. This information allows Frito Lay to take targeted actions to improve employee retention.

#### Presentation
The presentation of this study:   
https://youtu.be/MTaajBOWc4o   

#### Shiny App
The link below allows you to explore ratings from the employee dataset.  
https://katonp.shinyapps.io/Attrition/  

## How to Use

1. Clone this repository to your local machine.  
2. Open and run the R Markdown file (DDSAnalytics_Attrition_Study.Rmd) in R or RStudio to reproduce the analysis.  

## Introduction

Our team was provided with a dataset comprising existing employees of Frito Lay, to identify factors contributing to attrition. The dataset includes information on employees, such as attrition status, monthly salary, satisfaction ratings, job roles, departments, etc. The objective of this study is threefold: first, to identify the top three factors contributing to attrition; second, to develop models predicting both attrition and monthly income; and third, to uncover job role-specific trends and other insightful information.  

## Data

The analysis involved a dataset of 870 employees. After removing employee identification information, there were 31 variables, with 'Attrition' serving as the response variable and the rest as explanatory variables. Of these, 17 were categorical variables, with 8 of them being non-numeric, and 14 were continuous variables. The dataset had no missing values.  

Additionally, there were two test datasets. One of them did not include the attrition status of the employees, which was predicted by our attrition model developed during this study. The other test set lacked monthly income information for the employees, and it was predicted by our monthly income model created during this study. The prediction results can be found under the 'Prediction' folder in this repository.  

All datasets were sourced from a dedicated AWS S3 storage.  

For a detailed walkthrough of the analysis and conclusions, please refer to the R Markdown document.  

---  
Author: Katon Pang  
Date: [12/9/2023]  
