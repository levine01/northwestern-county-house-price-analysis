
# House Sales Analysis in NorthWestern county
 
 ![photo](https://images.pexels.com/photos/12379756/pexels-photo-12379756.jpeg?auto=compress&cs=tinysrgb&w=600&lazy=load)
    
### Overview

Our goal is to analyze house sales data in a northwestern county and develop a predictive model to estimate house prices. We will be using multiple linear regression modeling techniques to gain insights into the factors that influence house prices and provide recommendations to stakeholders in the real estate industry.

### Business Understanding

House sales began in 1890s in the United States and since then its been growing all over the world and agencies started to form to enhance and ease the house selling process.Last year the revenue was estimated to be $4.25M with prospects of growth as time goes by. House sales are mainly influenced by the number of bedrooms, bathrooms, the year built, square footage and whether renovations are done or not among other factors.

In this case the Northwest agencies aim to address the need of providing homeowners with accurate and actionable advice on how home renovations can potentially increase the estimated value of their properties and by what amount. By understanding the relationship between various renovation factors and house prices, the agencies can be able to guide homeowners in making informed decisions about renovations, which will ultimately lead to maximization of return on their investment which will enable them sell their homes at optimal prices.

###  Data Understanding

We will be utilizing the King County House Sales datasets which contains information on house sales, including features such as price, number of bedrooms and bathrooms, square footage, and year built. By thoroughly understanding and analyzing the dataset and its column descriptions, we can identify the relevant features to include in our analysis and modeling process

### Modelling

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