### **Intro to Machine Learning for Residential Appraisers, Part 2**
&nbsp;  
***“Every company has big data in its future, and every company will eventually be in the data business.”*** - Thomas H. Davenport 

&nbsp;  
It is no secret that Machine Learning is being applied everywhere. In today’s data-rich environment every industry can benefit from data analysis, data insights, forecasting, and automation of processes.
From actuarial models of insurance companies to the next show/movie recommendation from your favorite streaming platform, machine learning has become essential to provide a better customer experience as well as maximize profits for businesses.

Of course, the Real Estate Valuation industry is not an exception to this reality. It seems like every other day there is a new Real Estate tech company promising the best, fastest, and most accurate home valuations. These companies rely heavily (if not, entirely) on machine learning to create their valuation models. The most common of the products offered by these companies is the AVM (Automated Valuation Model).

Real Estate appraisers are very familiar with AVMs and the impact they have on the public’s perception of home values. 
It is now common (and somewhat expected) for home owners, buyers, and even real estate agents to utilize these AVMs as a factor to make decisions relating to listing prices and purchase offers.

It is worth mention that most AVMs are developed for marketing and informational purposes only. They are not intended to be appraisals and, due to USPAP requirements, they couldn’t be appraisals even if they wanted to (for now). However, that doesn’t stop the public from treating AVMs as reliable appraisals.

Is that a problem? Maybe. If the AVM produces grossly inaccurate results, then of course, it is a problem. This may result in over/under priced listings and angry real estate transaction participants. But the truth is that for the most part these AVMs are actually pretty good at providing a “ball park” value. We are very far from the clunky unreliable machine learning models from a decade ago. Advances in Artificial Neural Networks and the availability of Big Data has completely changed the performance of AVMs. There are some obvious exceptions, like custom properties, unique locations, and some rural areas. But this is not necessarily a problem with the machine learning model, it is a problem with the availability and/or quality of the data.

Now, why is any of this relevant to appraisers? Simple, because everything is moving towards artificial intelligence and machine learning, and whether we like it or not, the appraisal industry will not be spared. It's just a matter of time. And if you are not convinced ask taxi drivers about Uber or ask cable companies about Netflix.

But this is all a good thing. Appraisers are uniquely positioned to level up the valuation industry. Machine learning performance can be improved with the domain expertise of appraisers. And appraisers can take advantage of the computational power and automation of machine learning. It is the perfect match. We can have the best of both worlds.

#### ***The future of the appraisal/valuation industry lies in the intersection of advanced computational power (big data and machine learning) and domain expertise (appraiser).***
&nbsp;  

[Here](https://github.com/AngeloDSML/Home_Valuation/blob/main/HomeValuation.ipynb) is a quick tutorial to show how to explore a homes sales dataset and run a couple of simple Machine Learning Models for Home Valuations.



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



