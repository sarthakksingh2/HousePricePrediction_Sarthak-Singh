# HousePricePrediction_Sarthak-Singh

This project aimed to predict house prices using machine learning techniques and propertyrelated features from the Housing dataset. After cleaning the data, handling categorical 
variables, and removing duplicates, two regression models—Linear Regression and Random 
Forest —were trained and evaluated. The dataset was explored, cleaned, and preprocessed by 
handling missing values, removing duplicate records, and converting categorical variables 
into numerical format using one-hot encoding.
Two regression models, Linear Regression and Random Forest Regressor, were trained and 
evaluated using an 80:20 train-test split. Model performance was measured using Mean 
Absolute Error (MAE), Root Mean Squared Error (RMSE), and the R² Score.
In accuracy among the models tested, the Linear Regression provided better performance, 
achieving a higher R2 Score of 0.653 which means it was able to explain about 65% of the 
variation in house prices. It also produced lower prediction errors (MAE ≈ 970,000 and 
RMSE ≈ 1,324,000) compared to the Random Forest model. Key factors influencing house 
prices included area, number of bathrooms, furnishing status, air conditioning, and preferred 
location. It was also observed that houses with premium amenities tended to have higher 
prices, even when their sizes were similar.
Visualizations such as a price distribution histogram, correlation heatmap, and actual vs. 
predicted scatter plot provided useful insights into the dataset.
Based on these findings, real estate businesses can benefit from using data-driven pricing 
models to estimate property values more accurately and support informed decision-making.
Such approaches can help buyers, sellers, and agents make informed decisions, improve 
pricing strategies, and enhance overall market efficiency
