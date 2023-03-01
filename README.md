# House Price Prediction with Advanced Regression Techniques

This project aims to train a regression model to predict house prices using advanced techniques. We will be using a dataset that includes various features of houses such as the number of bedrooms, bathrooms, square footage, and the age of the house.

## Dataset

The dataset used for this project is the [House Sales in King County, USA](https://www.kaggle.com/harlfoxem/housesalesprediction) dataset, obtained from Kaggle. The dataset contains 21,613 observations with 19 features. We will use the following features for our analysis:

- `bedrooms`: Number of bedrooms in the house
- `bathrooms`: Number of bathrooms in the house
- `sqft_living`: Square footage of the living area
- `sqft_lot`: Square footage of the lot
- `floors`: Number of floors in the house
- `waterfront`: Whether the house has a view to the waterfront or not
- `view`: An index from 0 to 4 of how good the view of the property was
- `condition`: Overall condition of the house
- `grade`: Overall grade given to the housing unit, based on King County grading system
- `sqft_above`: Square footage of house apart from basement
- `sqft_basement`: Square footage of the basement
- `yr_built`: Year the house was built
- `yr_renovated`: Year the house was renovated (if it was)
- `zipcode`: Zip code of the house
- `lat`: Latitude coordinate of the house
- `long`: Longitude coordinate of the house
- `sqft_living15`: The average square footage of interior housing living space for the nearest 15 neighbors
- `sqft_lot15`: The average square footage of the land lots of the nearest 15 neighbors

## Regression Techniques

We will be using the following advanced regression techniques for our analysis:

- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

We will compare the performance of each model using various evaluation metrics such as Mean Squared Error (MSE) and R-squared.

## Conclusion

By training and evaluating the regression models on the King County housing dataset, we hope to gain insights into which features have the most significant impact on house prices and which regression technique performs the best for this prediction task.
