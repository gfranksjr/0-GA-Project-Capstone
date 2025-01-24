# Capstone Project 6: - Ghost Kitchen Marketing

---

## Problem Statement
>As a data scientist at a startup ghost kitchen company in Alabama, I have been tasked with market research that includes analyzing data on food value, food keywords, nutrition habits, physical activity levels, and obesity rates, and other factors, to identify distinct market segments across the state and determine top menu items to deliver. The goal is to develop models that will enable targeted marketing campaigns and tailored menu offerings, presenting the top locations with recommendations for top menu items and keywords to use for paid search advertisement.

---

## Data Dictionary

Four data sets are included in this project:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**budgetfood.csv**|*dtypes: float64(1), object(3)*|Reddit|Dataset pulled using PRAW from subreddit /budgetfood|
|**finedining.csv**|*dtypes: float64(1), object(3)*|Reddit|Dataset pulled using PRAW from subreddit /finedining|
|**cdc_npao.csv**|*dtypes: float64(6), int64(3), object(24)*|Data.world|Dataset from Data.world: CDC Nutrition, Physical Activity, and Obesity by State|
|**food-deserts-data-for-the-usa_csv-1.csv**|*dtypes: float64(1), object(3)*|CDC|Dataset from Data.world: Food Deserts data for the United States|

---

## Data Description for Audience

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

## Executive Summary

- This analysis utilized machine learning models to determine optimal business strategies for a new food service venture in Alabama, focusing on location selection and menu development.

- Location Analysis
  
Two clustering models, K-means and DBSCAN, were employed to identify ideal locations for business establishment:

* K-means (Silhouette Score: 0.288, Inertia: 2645004622287.102)
* DBSCAN (Silhouette Score: 0.566, Inertia: 2544347384021.328)
* Mobile, Baldwin, and Elmore counties are prime areaa for initial investment.

These locations offer a balance of population density and income levels, avoiding oversaturated markets while ensuring sufficient customer base, and should both be tested.

- Menu and Marketing Strategy
  
Two classification models, Logistic Regression and Random Forest, were used to determine optimal menu items and advertising focus:

* Logistic Regression (Accuracy: 0.9045, Precision: 0.9094, Recall: 0.9045, F1 Score: 0.9038)
* Random Forest (Accuracy: 0.8886, Precision: 0.8964, Recall: 0.8886, F1 Score: 0.8874)
* Key findings include: Focus items: Chicken, Potatoes, Beans; Items to avoid: Sushi, Caviar, Crab

These results align with the goal of targeting cost-effective, popular items among lower-income groups while avoiding high-cost ingredients.

---

### Recommendations

- Establish initial operations and test in Baldwin, Elmore and Mobile counties
- Develop a menu centered around chicken, potatoes, and beans, etc.
- Concentrate paid search advertising on keywords related to these core ingredients
- Use high-cost items like sushi, caviar, and crab, etc. as negative keywords in advertising campaigns

This data-driven approach positions the business for success by targeting the right location and customer base while optimizing menu offerings and marketing strategies.

---

### **Future Improvements:**

- Feature Engineering: Experiment with different combinations of features or derived metrics
- Hyperparameter Tuning: For K-means: Try different values of k; For DBSCAN: Experiment with eps and min_samples parameters
- Dimensionality Reduction: Apply PCA before clustering to potentially improve results
- Ensemble Methods: Combine results from multiple models for more robust results
- Geospatial Considerations: Incorporate geographical coordinates, expand search for new locations outside Alabama
- Improve Data Acquisition: Obtain additional food preference information unique to the specific area where the food is going to be sold

By considering these factors and potential improvements, this venture can refine clustering approaches and gain more meaningful insights.

---

## Sources

* Google
* W3schools
* StackOverflow
* Geeksforgeeks
* GA Team Members including Intructors and TAs
* GA/GF Class Materials including Projects, Lessons, and Labs

---

## Contact
**LinkedIn**[: Greg Franks, Jr.](https://www.linkedin.com/in/gregoryfranksjriii/)




