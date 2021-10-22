In this exercise, we will use some of the methods we have learned:

- Imputing missing values
- Encoding
- Scaling
- Regularization

Use melb_data.csv (Melbourne House Data) with:
- Features: 'Suburb', 'Rooms', 'Type', 'Method', 'Distance', 'Bedroom2', 'Bathroom', 'Car', 'Landsize', 'BuildingArea', 'YearBuilt', 'CouncilArea' , 'Regionname'
- Target: 'Price'

What is done in preprocessing and modeling:
- Perform simple EDA for dataset exploration.
- Use ColumnTransformer for missing value imputation and encoding.
- There are 4 features that contain missing values. Fill in the missing value with an imputer that matches the character of each feature.
- There are 5 categorical features. Perform encoding on these features according to the character of each feature.
- Scaling numerical features. Choose the scaler that you think is most suitable based on the characteristics of the data.
- Make predictions using the Lasso method on preprocessed data with a proportion of 80:20 and random_state = 42. Interpret the results!
