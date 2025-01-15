# Capstone Project 6: - Ghost Kitchen Marketing

---

## Background Statement
>TBD
# Article - "Rising food insecurity in Alabama reflects national trends"
# Source: https://www.alreporter.com/2024/09/11/report-rising-food-insecurity-in-alabama-reflects-national-trends/
# "In Alabama, food insecurity rates mirror national averages, with an estimated 14 percent of households facing food insecurity."
# Essentially, Alabama is a microcosm of america in terms of food insecurity
---

## Problem Statement
>FINAL TBD
>DRAFT: As a data scientist at a leading food delivery/ghost kitchen company in Alabama, you've been tasked with market research that includes analyzing data on food value, food keywords, nutrition habits, physical activity levels, and obesity rates, and other factors, to identify distinct market segments across states and determine top menu items to deliver. Your goal is to develop at least one model that will enable targeted marketing campaigns and tailored menu offerings, presenting the top state clusters or groups with recommendations for top menu items.

---

## Data Dictionary

Four data sets are included in this project:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**budgetfood.csv**|*dtypes: float64(1), object(3)*|Reddit|Dataset pulled using PRAW from subreddit /budgetfood|
|**finedining.csv**|*dtypes: float64(1), object(3)*|Reddit|Dataset pulled using PRAW from subreddit /finedining|
|**cdc_npao.csv**|*dtypes: float64(6), int64(3), object(24)*|Data.world|Dataset from Data.world: CDC Nutrition, Physical Activity, and Obesity by State|
|**food-deserts-data-for-the-usa_csv-1.csv**|*dtypes: float64(1), object(3)*|CDC|Dataset from Data.world: Food Deserts data for the United States|

## Data Description for Audience - Food Delivery Company

CDC_NPAO will be used for a analysis that can provide background information on prime target marketing demographics.

Food-Deserts... will be used for a kmeans model that can inform location decisions that take into consideration Population and Median Income, and possibly other factors, that make up prime marketing demographcs.

BudgetFood and FineDining datasets will be used to create 2 classification models that will help quickly distinguish optimal high volume paid and organic search keyword terms and high net revenue menu item selection, with classification that optimizes cheap foods over expensive foods that are popular, without the need to derive each of its ingredients values individually.  

These models can also be used on a future survey of the customers top favorite menu items or other data obtained in the future in whatever areas eating habit data can be obtained, which will help to start food delivery decision making to decide on what to sell first, in a way that reduces costs, and improves likelihood of sales.

These models all combine to enhance the market research and product development for this new venture.

---

## Table of Contents
1. [Code](#code)
2. [Data](#data)
3. [Presentation](#presentation)
4. [Scratch](#scratch)
5. [README.md](#readme)
   
---

# Executive Summary

TBD

---

### Methodology

Data Collection
- TBD

Preprocessing and Exploratory Data Analysis (EDA)
- TBD

Modeling
- TBD

### Conclusions and Recommendations

- Model Performance: 

- TBD

### **Next Steps:**

- Practical Application: TBD

- Scalability: TBD

- Customization Potential: TBD
  
---

## Sources

* Google
* W3schools
* StackOverflow
* Geeksforgeeks
* GA Team Members including Intructors and TAs
* GA/GF Class Materials including Projects, Lessons, and Labs

## Contact
**LinkedIn**[: Greg Franks, Jr.](https://www.linkedin.com/in/gregoryfranksjriii/)




