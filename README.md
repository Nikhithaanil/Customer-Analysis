# Customer-Analysis
Final Project
Customer Analysis for Entri Software Pvt Limited
Overview:
Aims to analyze customer behavior and classify them based on their likelihood of accepting campaigns. Additionally, the company seeks to segment customers for targeted marketing efforts. The analysis will be conducted using historical customer data.

Goals:
The primary objectives of this exercise are:

Build a model using historical data, focusing on all steps of the data science process (EDA, data processing, modeling, evaluation, and visualization).
Highlight trends, deep insights, and novel approaches taken during the analysis.
Apply classification and clustering machine learning algorithms and evaluate their performance.
Data Dictionary:
People:

ID: Customer's unique identifier
Year_Birth: Customer's birth year
Education: Customer's education level
Marital_Status: Customer's marital status
Income: Customer's yearly household income
Kidhome: Number of children in customer's household
Teenhome: Number of teenagers in customer's household
Dt_Customer: Date of customer's enrollment with the company
Recency: Number of days since customer's last purchase
Complain: 1 if the customer complained in the last 2 years, 0 otherwise
Products:

MntWines: Amount spent on wine in last 2 years
MntFruits: Amount spent on fruits in last 2 years
MntMeatProducts: Amount spent on meat in last 2 years
MntFishProducts: Amount spent on fish in last 2 years
MntSweetProducts: Amount spent on sweets in last 2 years
MntGoldProds: Amount spent on gold in last 2 years
Promotion:

NumDealsPurchases: Number of purchases made with a discount
AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
Response: 1 if customer accepted the offer in the last campaign, 0 otherwise
Place:

NumWebPurchases: Number of purchases made through the company’s website
NumCatalogPurchases: Number of purchases made using a catalogue
NumStorePurchases: Number of purchases made directly in stores
NumWebVisitsMonth: Number of visits to company’s website in the last month
Approach:
Exploratory Data Analysis (EDA):

Analyze trends in customer demographics, such as age, education, and income.
Explore relationships between customer characteristics and purchase behavior.
Identify patterns in campaign acceptance and customer complaints.
Data Preprocessing:

Handle missing values and outliers.
Encode categorical variables and standardize numerical features.
Feature Engineering:

Create new features if necessary.
Select relevant features for modeling.
Modeling:

Apply classification algorithms to predict campaign acceptance.
Utilize clustering algorithms to segment customers based on behavior.
Evaluation:

Assess model performance using appropriate metrics such as accuracy, precision, recall, and F1-score.
Validate clustering results using silhouette score or other clustering metrics.
Visualization:

Create visualizations to communicate key findings and insights effectively.
Present charts and graphs to illustrate trends, patterns, and model results.
Next Steps and Improvements:
Conduct further analysis to understand customer segments and their preferences.
Refine models with additional data and feature engineering techniques.
Implement personalized marketing strategies based on customer segments.
Conclusion:
In conclusion, this analysis provides valuable insights into customer behavior. By leveraging machine learning techniques, the company can optimize campaign targeting and improve customer engagement. Future efforts will focus on refining models and implementing data-driven marketing strategies for sustainable growth.
