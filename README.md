# Red-Wine-Quality-Prediction-Using-Regression-Modeling-and-Machine-Learning
This project was a part of the Data Science course at Duke Fuqua School of Business - MQM Business Analytics Program - Class of 2021

1. Dataset Source: Wine Quality Data Set. This dataset is also available from the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/wine+quality)
- Dataset Background: Two datasets are included, related to red and white wine samples from the north of Portugal. The goal is to use the red wine samples to model red wine quality based on physicochemical tests.

- Input variables (based on physicochemical tests):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)

2. Problem Definition & Target Variable: 
This project aims to determine which chemical features are the best quality red wine indicators. To be more specific, we define below problems
for this analysis:
1. Show the contribution of each factor to the wine quality in our model
2. Show which features are more important in determining the wine quality
3. Show which features are less important in determining the wine quality

As mentioned earlier, our target variable will be wine quality, which is scored between 0 and 10.

3. Use Scenario: 
The wine industry shows a recent growth spurt as social drinking is on the rise. The price of wine depends on a rather abstract concept of wine appreciation by wine tasters,
opinion among whom may have a high degree of variability. Pricing of wine depends on such a volatile factor to some extent. Another critical factor in wine certification and quality assessment is physicochemical tests, which are laboratory-based and consider factors like acidity, pH level, sugar, and other chemical properties. The wine market would be of interest if human quality of tasting can be related to wine's chemical properties so that certification and quality assessment and assurance processes are more controlled. 

4. Proposed Data Techniques: Our first step of the process will be converting the dataset into a readable CSV and cleaning to cut down the number of columns to ones necessary and without any null values. Our exploratory data analysis will likely involve looking at distributions of individual variables via histograms and box plots, running correlation tests/matrices, and creating clustering plots. These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g., there are many more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines. Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

5. Files included
- Data set: winequality-red.csv
- List of R-codes: Indv_Proj.Rmd
- Report document: Individual Project - Dexter Nguyen - Red Wine Quality Prediction
Or: https://towardsdatascience.com/red-wine-quality-prediction-using-regression-modeling-and-machine-learning-7a3e2c3e1f46?source=post_stats_page-------------------------------------

6. Others
N/A
