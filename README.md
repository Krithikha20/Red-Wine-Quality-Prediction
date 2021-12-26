# Red-Wine-Quality-Prediction
## Business Understanding
The red wine industry shows a recent exponential growth as social drinking is on the rise. Nowadays, industry players are using product quality certifications to promote their products. This is a time-consuming process and requires the assessment given by human experts, which makes this process very expensive. Also, the price of red wine depends on a rather abstract concept of wine appreciation by wine tasters, opinion among whom may have a high degree of variability. Another vital factor in red wine certification and quality assessment is physicochemical tests, which are laboratory-based and consider factors like acidity, pH level, sugar, and other chemical properties. The red wine market would be of interest if the human quality of tasting can be related to wine’s chemical properties so that certification and quality assessment and assurance processes are more controlled. This project aims to determine which features are the best quality red wine indicators and generate insights into each of these factors to our model’s red wine quality.

Analytic Approach
- What is the analytical approach that you would take for this project? Why do you think its the right approach?
  - The analytical approach for the Wine quality project is Predictive and Descriptive approach

Data Requirements
- What kind of data do we require for predicting the red wine quality and for determining the features that are the best quality red wine indicators?
  - We require data which has the right composition of contents in the red wine to predict a wine quality and show the relationship between them.

Data Collection
- From where do we get our data?
  - We can get our data from quality surveys conducted in the wine manufacturing/research units and quantitative laboratory data obtained from a wine.

Data Understanding
Link for the dataset https://archive.ics.uci.edu/ml/datasets/wine+quality for context
- From where are red wine samples obtained?
  - The dataset used for prediction are obtained from the variants of Portuguese "Vinho Verde" wine.
  
- How can knowing the impact of each variable on the red wine quality help businesses(producers, distributors, etc) ?
  - Understand the grades better.
  - Enrich the quality of wine.
  - Produce and promote more specialized wine grades.
  - Research purposes to understand the nutrition facts of wine.
  - Advertise for selling
  - Health benefits can be protrayed for better selling and transparency along with identifying allergic reaction/target customers that avoid wine due to particular content of wine. eg., Bread that comes gluten free for special category.
  - Explore usage of wine in various other departments such as cosmetic industry, medicinal purposes.

<b>STEPS:</b>
1. Importing the libraries 
2. Exploring the 'Wine' Dataset 
3. Data Preparation
4. Check for null values 
5. Check for outliers
6. Correlation heatmap 
7. Target variable distribution
8. Check the distribution of data using histograms
9. Mutiple linear Regression Assumptions
  - All variables are continuous numeric and free from outliers
  - Linear realtionship between the predictors and predictant
  - Multivariate Normality–residuals are normally distributed
  - All predictors are independent of each other(multicollinearity)
  - Homoscadecity
10. Data Modelling
  - Train_test_split
  - Standardizing the features
  - Cross Validation
  - Implementing the Linear Models
11. Model Evaluation
  - Evaluating Model performance
  - Feature Importance
  - Visualizing features based on Feature Importance
Conclusion 
11. Overall Observation
