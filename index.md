---
title       : Coronary Heart Disease Prediction Algorithm
subtitle    : 
author      : Bhaskar Bhattacharya
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction to Coronary Heart Disease Prediction
  
    
### Background
- Data was obtained from previous scientific studies on patients with coronary heart disease
- This Data was used to create a prediction algorithm to use Age and Body Mass Index (Obesity) to predict the likelihood of the person having coronary heart disease
- The User needs to only enter his/her age and Body Mass Index in order for the algorithm to predict the chances of his/her having heart disease.

--- .class #id 

## User Instructions for the Prediction Application
  
    
### Step 1 - Go to this URL - http://bhaskarb.shinyapps.io/DataProducts
#### 
  
### Step 2 - Enter the Age of the person in the left side panel
#### 
  
  
### Step 3 - Enter the Body Mass Index of the person in the left side panel
####  
  
  
### Step 4 - Press Submit button to get results in % likelihood of having Coronary Heart Disease
#### 

---

## Why is this app helpful?
  
####   
#### Data obtained from a scientific study has been used to prepare the algorithm and hence the results may serve as a guide to planning a person's medical treatment/check-ups.  

---

## Points to Note
  


1. There are multiple predictors for predicting Heart Disease likelihood. This algorithm only considers 2 of them. Total number of predictors are: 

```r
predictors
```

```
## [1] 9
```
  
  
2. The study was done for only one country (South Africa) and results may not apply in the same manner to other countries
3. The results should only be used as a guide


