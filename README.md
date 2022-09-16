# nyc_airbnb
This project is created to predict the competitive price at which an Airbnb host should list their New York property.
It contains three files: a Jupyter notebook for exploratory analysis on the data named “Airbnb_EDA”, a Jupyter notebook to carry out predictive modeling to estimate price for a listing named “AirBnb_Pricing_Predictive_Model_Final”, and a final report on the findings from the analysis and modeling named “AirBnb_NewYork_Price_Listing_Prediction_Report”.

The file used to create the data frame in this notebook, named “AB_NYC_2019.csv” was taken from Kaggle. It was last updated in 2019 and can be downloaded at this link:
https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data

This csv file contains 48,895 observations (or rows) and 16 features (or columns). The features included are ‘id’, ‘name’, ‘host_id’, ‘host_name’, ‘neighbourhood_group', 'neighbourhood', 'latitude', 'longitude' , 'room_type', ‘price’, 'minimum_nights' , 'number_of_reviews', ‘last_review”, 'reviews_per_month',
'calculated_host_listings_count', and 'availability_365’.
To predict the listing prices using machine learning, scikit learn library was employed. The models compared to reach the best performing model were kNN regression,
Decision Tree regression and Ridge regression.

This notebook is developed for Python 3.7+, and expects a standard Jupyter Hub or Jupyter notebook environment. Moreover, we also provide a Powerpoint presentation with 5 slides highlighting our key findings. This is a group project prepared in 2 steps (and 2 files accordingly: exploratory data analysis & prediction model).
