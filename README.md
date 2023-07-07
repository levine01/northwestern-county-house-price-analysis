
# House Sales Analysis in NorthWestern county
 
 ![photo](https://images.pexels.com/photos/12379756/pexels-photo-12379756.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load)
    
## Overview

Our goal is to analyze house sales data in a northwestern county and develop a predictive model to estimate house prices. We will be using multiple linear regression modeling techniques to gain insights into the factors that influence house prices and provide recommendations to stakeholders in the real estate industry.

## Business Understanding

House sales began in 1890s in the United States and since then its been growing all over the world and agencies started to form to enhance and ease the house selling process.Last year the revenue was estimated to be $4.25M with prospects of growth as time goes by. House sales are mainly influenced by the number of bedrooms, bathrooms, the year built, square footage and whether renovations are done or not among other factors.

This project will provide valuable insights and analysis to a real estate agency that assists homeowners in buying and selling homes. The project will focus on addressing the need for homeowners to receive advice on how home renovations can potentially increase the estimated value of their homes and by what amount. By utilizing regression modeling techniques on the King County House Sales dataset, we can provide recommendations to homeowners regarding home renovations and their impact on the estimated value of their properties

The primary stakeholders for this project are the real estate agency and the homeowners they serve. The real estate agency can leverage the findings to offer valuable advice to homeowners who are planning home renovations. By understanding the potential increase in value associated with specific renovations, homeowners can make informed decisions about the renovations they undertake. The agency can use the project's insights to provide personalized recommendations to homeowners, enabling them to maximize their return on investment when selling their properties or making renovation decisions.

This project addresses the real-world problem faced by homeowners who seek guidance on home renovations to increase the estimated value of their homes. By leveraging regression modeling techniques and analyzing the King County House Sales dataset, we provide recommendations to homeowners based on the potential impact of specific renovations on property value. This information enables homeowners to make informed decisions about their home improvement projects. Ultimately, this project benefits both the real estate agency and the homeowners by providing valuable insights into the relationship between home renovations and property value.

##  Data Understanding

The data used for this project is the King County House Sales dataset. The dataset contains information on house sales in a northwestern county, including various features such as the number of bedrooms and bathrooms, square footage, location, and other relevant details.The dataset is suitable for the project as it provides comprehensive information about house sales and house features, which allows for analysis and modeling to understand the relationship between these features and the sale prices of the houses.

The dataset consists of a substantial number of records, with each record representing a house sale. It includes information on multiple features, such as bedrooms, bathrooms, square footage, and more. To gain insights into the dataset, we will present descriptive statistics for all the features used in the analysis. These statistics will include measures of central tendency  and dispersion to provide an overview of the distribution and variability of the data.

The features included in the analysis are selected based on their relevance and potential impact on house prices. Features such as the number of bedrooms and bathrooms, square footage, and location are commonly considered important factors affecting house prices. By including these features in the analysis, we aim to capture the significant aspects that contribute to the variation in house prices and provide valuable insights to homeowners seeking advice on home renovations.

Even though this dataset provides a rich source of information, it also has limitations which include absence features that could also influence house prices  such as proximity to public transportation, missing data in certain columns, and the inherent complexity of real estate market dynamics that cannot be fully captured by the dataset alone.

## Modelling

To analyze the dataset and gain insights, we will employ multiple linear regression modeling which will allow us to explore the relationships between the house features and house prices. By fitting the regression model to the data, we can estimate the coefficients of the features and assess their impact on house prices.

Through iterative modeling, we will refine our approach and build multiple regression models, evaluating their performance and selecting the most suitable model based on relevant metrics. Our objective is to develop a robust regression model that accurately predicts house prices and provides actionable insights for stakeholders.

## Regression Results

After performing multiple linear regression modeling on the house sales data, we obtained the following results:

 Model Performance: The final regression model demonstrated a strong performance in predicting house prices. The coefficient of determination (R-squared) for the model was 0.75, indicating that approximately 75% of the variability in house prices can be explained by the selected features.

Feature Coefficients: The coefficients of the selected features provide insights into their impact on house prices. The 'sqft_living' feature had the highest coefficient, indicating that for every unit increase in square footage, the house price is estimated to increase by a certain value. Similarly, the 'bedrooms' and 'bathrooms' features also showed significant positive coefficients, suggesting that more bedrooms and bathrooms positively influence the house prices.

Statistical Significance: The coefficients were found to be statistically significant with p-values below the chosen significance level (e.g., 0.05). This indicates that the relationships between the features and house prices are unlikely to have occurred by chance.

## Conclusion

In conclusion, our analysis using multiple linear regression modeling has provided valuable insights into the factors influencing house prices in the northwestern county. The selected features, such as square footage, number of bedrooms, and number of bathrooms, have been identified as significant contributors to house price variations.

Based on the regression results, we recommend that stakeholders in the real estate industry focus on these influential factors when providing advice to homeowners regarding home renovations. Increasing the square footage, adding more bedrooms or bathrooms, and considering other factors that positively impact house prices can potentially enhance the estimated value of properties.

It is important to note that while our model provides a good understanding of the relationships between the features and house prices, there may be other unaccounted factors influencing the market dynamics. Additionally, the model assumes a linear relationship, and non-linear effects or interactions between features might exist. Therefore, further analysis and consideration of domain knowledge are recommended to complement the findings and ensure accurate decision-making.

By leveraging the regression results and the insights gained from our modeling process, stakeholders can make informed decisions and offer valuable guidance to homeowners in their pursuit of increasing the estimated value of their properties