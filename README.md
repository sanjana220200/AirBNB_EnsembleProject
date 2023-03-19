# Hyperparameter tunning v1

This branch is built upon @TheoDeann's data preprocessing of Airbnb New York City Airbnb data (https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)


# What has been done
For feature engineering, removed the combination column neighbourhood_group and neighbourhood since this could cause loss of information. Redo the missing value and correlation map

the feature selected for hyperparameter:
selected_feature = ['neighbourhood_group','neighbourhood','latitude','longitude','number_of_reviews','room_type','minimum_nights', 'reviews_per_month','calculated_host_listings_count','availability_365','host_id']

For tunning, Grid Search are used to tune results for XGboost, Random Forest and Adaboost

# Files
Airbnb_Ensemble_Project.ipynb


# conclussion
This tunning provide 0.5736171592187363 from XGboost. tbc with feature engineering.
