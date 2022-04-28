### **Intro to Machine Learning for Residential Appraisers, Part 2**
&nbsp;  

In Part 1 **[Intro to Machine Learning for Residential Appraisers, Part 1](https://github.com/AngeloDSML/Home_Valuation_Part_1)**, we covered data collection, data wrangling/cleaning, visualizations, and data modeling. Then we ran predictions using two regression techniques, Linear Regression and Decision Tree Regression.
&nbsp;

Since we already covered the data pre-processing steps in Part 1, we will not cover those steps again in Part 2. Instead, we will jump right into data modeling and predictions, but this time we will work with **Extreme Gradient Boosting (XGBoost)** and **Random Forest**. 


[Here](https://github.com/AngeloDSML/Home_Valuation_Part_2/blob/main/HomeValuationPart2.ipynb) is the link to the notebook.


### Quick Tutorial - Machine Learning Models for Residential Appraisers, Part 2 (Extreme Gradient Boosting and Random Forest)

*Important Note: There are plenty of free machine learning tutorials and courses online. Anyone can access them, learn, and run predictive models for home values. However, this tutorial has been designed specifically for residential appraisers, and some of the material will be irrelevant or less important for other industries. If you are not a residential appraiser, and/or you are looking to learn about machine learning as a broader field, this tutorial may not be adequate for you.*

The purpose of this tutorial is for residential appraisers interested in machine learning to get their toes wet. This is **not** a comprehensive machine learning tutorial and it does **not** cover everything there is to know about the topic. 


&nbsp;  
**Prerequisites:**
1.	Some understanding of Python programming.
2.	Access and familiarity with Jupyter notebook.
3.	If you want to use your own data you will need access to home sales data and custom exports from your local MLS.

&nbsp;  
**Obtain the data:**
We will be using a dataset of home sales that includes sales prices and several predicting features, in csv format ***(Already pre-processed from Part 1 of the tutorial)***. 

The easiest way to obtain a dataset for your specific market area is by creating a custom csv export from your local MLS system. If you don’t know how to create it you should get technical support from your MLS provider.

The sales dataset  contains the following features:
Lot size, Water View, Year Built, Bedrooms, Bathrooms, GLA, Garage, Carport, Fireplace, Pool, and Sales Price.
Note: These features are based on the subject’s market area. You should export a dataset that includes all of the value-affecting features you consider relevant for your specific market area. 

&nbsp;  
**Assumptions:**
We will make the following assumptions for the purpose of this tutorial. 
1.	Stable market condition. In rapidly increasing or decreasing markets you will likely need to add a “sales date” column/feature.
2.	Accurate data sources. MLS data is considered to be good and reliable.
3.	Relevant predicting features. Make sure you include all of the appropriate value-affecting features for the subject’s market area.



