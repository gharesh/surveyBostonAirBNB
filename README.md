# Udacity – AirBNB data investigation

## Pick a dataset.
Dataset chosen - Boston AirBNB Data

## Pose at least three questions related to business or real-world applications of how the data could be used.
How AirBNB host set up rental price for their apartment/house?
What are the most important features to estimate AirBNB rental price?
What are the topmost amenities opted by customers wanting to book through AirBNB?

## Create a Jupyter Notebook, using any associated packages you'd like, to
As 99% of the listing price are below 500, so I drop the rows above 500 to get a more stable prediction by eliminating outliers. Missing values were filled by median value or most frequent value by grouping based on other related features.
GradientBoostingRegressor was used as classifier for this and a five-fold GridSearchCV was applied to find the best hyperparameter for the classifier.
On the other hand, 1/5 of the preprocessed dataset was used as test data and the remaining 4/5 are used to train machine learning model.

## File Description
Listings_Boston_Project.ipynb is the python notebook holding the code

Unable to upload the dataset but its been downloaded from https://www.kaggle.com/airbnb/boston
## Results of the analysis
Results and discussion were published on https://datascience954723067.wordpress.com/2019/01/22/udacity-airbnb-data-investigation/ 

## Conclusion
We established a machine learning model to predict the rental price for Boston AirBNB data set
We took a look at the feature importance of the trained model and check if they make sense.
We list all the important amenities to get a better feeling how host can make more money by providing better services to meet customers’ need.
