# House Rent Prediction with Machine Learning and Power BI

## 1. Introduction:
Renting a house is a tough decision for both tenants and landlords. Tenants need to ensure
they are paying a fair price for the property they are interested in, while landlords need to
set rents that reflect the value of their properties accurately. In this project, my aim is to
develop a machine learning model that can predict house rents accurately based on various
features such as city, locality, number of bedrooms, furnishing, and other relevant factors.
This predictive model will serve as a valuable tool for both tenants and landlords in
negotiating rental agreements and making informed decisions.

## 2. Data Collection and Preprocessing:
I have obtained a dataset with details on rental houses in India, including furnishing, city,
number of bedrooms, locality, rent costs etc.. I have sorted missing data during
preprocessing by deleting incomplete information, null values, or missing values. I have
included various visualizations to learn more about the distribution of attributes and how
they relate to rent pricing, data exploration and visualization approaches.

## 3. Feature Engineering:
To enhance the prediction model's performance, feature engineering and modification
was used for better understanding. When adding new features or changing old ones, I
considered variables like the property's condition, the neighborhood's demographics, and
how close facilities were.

## 4. Machine Learning Model Selection and Training:
After exploring several machine learning algorithms, I have decided regression model
would work well for predicting continuous rent values. The selected model was trained
with the dataset, and its performance was improved by optimizing its hyperparameters
through cross-validation.

## 5. Model Evaluation:
A trained model is used on existing to generalize to new data. To evaluate the model's
accuracy and pinpoint any areas that needed work and plotted the expected rentals versus
the actual rents. Furthermore, sensitivity analysis was performed to bring out the
influence of various variables on rent projections example BHK, area type, furnishing
status, size , number of houses available for rent, and types of tenants existing in a region.

## 6. Integration with Power BI:
I have implemented an interactive dashboard for rent prediction and integration of the
predictive algorithm with Power BI. Users can quickly get an estimate of rent pricing by
entering property parameters like location, size, and amenities into the dashboard. Maps,
histograms, and scatter plots are examples of visualizations that offer a clear
understanding of rent distribution and trends across various geographies. This gives a
view on price variations as per choices.

## 7. Neural Network Architecture for Rent Prediction:
Using the Keras toolkit, created a neural network architecture with two Long Short-Term
Memory (LSTM) layers and two Dense layers in order of precedence. While the second
LSTM layer has 64 units and does not return sequences, the first LSTM layer has 128
units and does. There are 25 and 1 unit(s) in the Dense layers, respectively. Tasks
involving sequence prediction, such time series forecasting, are the focus of this
architecture.

## 8. Deployment and Future Improvements:
The generated prediction model can be widely utilized by integrating it into current real
estate platforms or releasing it as a web application. To increase the model's accuracy and
usability, future updates can include adding more information like property age, rental
market trends, and user comments.

## 9. Conclusion:
In conclusion, this research shows how machine learning can be used to accurately predict
housing rents based on a variety of factors. Renters and landlords can now make educated
decisions about rental agreements with ease and model's integration with Power BI and an
intuitive user interface. This approach makes the rental market more transparent and
efficient by providing precise rent pricing estimates.
