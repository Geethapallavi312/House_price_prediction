# House Price Prediction
Predicting house prices involves analyzing multiple factors beyond just the size of the house. Various attributes significantly influence the price of a house, making the task complex. This dataset, collected from various property aggregators across India, includes comprehensive information with 13 columns:

Price: The price of the house.

Area: The total area of the house in square feet.

Bedrooms: The number of bedrooms.

Bathrooms: The number of bathrooms.

Stories: The number of stories.

Mainroad: Whether the house is connected to the main road (Yes/No).

Guestroom: Whether the house has a guest room (Yes/No).

Basement: Whether the house has a basement (Yes/No).

Hot water heating: Whether the house has a hot water heating system (Yes/No).

Airconditioning: Whether the house has an air conditioning system (Yes/No).

Parking: The number of parking spaces available.

Prefarea: Whether the house is located in a preferred area (Yes/No).

Furnishing status: The furnishing status of the house (Fully Furnished, Semi-Furnished, Unfurnished).

## Data Overview:

The dataset contains 545 entries and 13 columns.
All columns are complete with no missing values.

## Data Visualization:

A correlation matrix is used to identify relationships between variables.
Heatmaps and bar plots are used for visualizing correlations and distributions.
Pair plots provide an overall view of interactions between variables.
## Outlier Detection and Removal:

Outliers in the 'area' column are detected using the Interquartile Range (IQR) method and removed to improve model performance.
## Data Preparation:

The data is split into dependent (price) and independent variables (other attributes).
Categorical variables are encoded using Label Encoding.
Feature scaling is applied using MinMaxScaler to normalize the data.

## Model Building and Evaluation:

The dataset is split into training and testing sets with an 80-20 ratio.
A Linear Regression model is built and trained on the training data.
The model's performance is evaluated on the test data, comparing actual and predicted house prices.
## Results:

The model provides predictions for house prices, which are compared with actual prices to evaluate accuracy.
Predicted prices are visualized to assess the model's performance.
