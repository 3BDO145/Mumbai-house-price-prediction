# Mumbai-house-price-prediction
Dataset:
I started by exploring a comprehensive dataset from Mumbai, containing valuable information about various real estate listings.

Data Preprocessing:

Removed unnecessary columns to focus on relevant features.
Handled missing values, ensuring data completeness.
Applied outlier removal using the Interquartile Range (IQR) method to enhance model robustness.
Label Encoding:
Utilized Label Encoding for categorical variables like 'Status', 'Furnished_status', 'neworold', and 'type_of_building'. This step is crucial for the machine learning models to process categorical data.

Model Selection:

Linear Regression:

Trained a Linear Regression model to understand the linear relationships between features and prices.
Achieved a Mean Squared Error (MSE) of [your MSE score] and an R-squared of [your R-squared score].
K-Nearest Neighbors (KNN):

Employed KNN regression for a more localized approach to predicting prices.
Tuned the model for optimal performance, achieving an MSE of [your MSE score] and an R-squared of [your R-squared score].
