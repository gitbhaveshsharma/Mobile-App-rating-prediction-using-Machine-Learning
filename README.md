# Mobile-App-rating-prediction-using-Machine-Learning

# App Rating Prediction :rocket:

Welcome to the Mobile App Rating Prediction project! This project aims to build machine learning models to predict the rating of an app based on its features.

## Project Overview :memo:

This project utilizes a dataset containing information about various apps available on the Google Play Store. The goal is to develop machine learning models that can accurately predict the rating of an app using its features.

## Dataset :bar_chart:

The dataset used in this project is the "googleplaystore.csv" file. It contains the following columns:

- `App`: Name of the app
- `Category`: Category of the app
- `Rating`: Rating of the app (target variable)
- `Reviews`: Number of user reviews
- `Size`: Size of the app
- `Installs`: Number of app installs
- `Type`: Paid or free app
- `Price`: Price of the app
- `Content Rating`: Content rating of the app
- `Genres`: Genres of the app
- `Last Updated`: Last update date of the app
- `Current Ver`: Current version of the app
- `Android Ver`: Minimum Android version required by the app

## Project Workflow :gear:

1. Data Preprocessing:
   - Handle missing values
   - Convert categorical variables to numerical representations
   - Convert string-based numerical features to appropriate formats

2. Feature Engineering:
   - Extract meaningful features from the available data
   - Create additional features based on domain knowledge or insights from the dataset

3. Model Training and Evaluation:
   - Split the dataset into training and testing sets
   - Train machine learning models using algorithms like Random Forest and XGBoost
   - Evaluate model performance using Root Mean Squared Error (RMSE)

4. Predictions:
   - Use the trained models to make predictions on new data or the test set

## Model Performance :chart_with_upwards_trend:

The models' performance on the test set is as follows:

- Random Forest: RMSE = 0.489
- XGBoost: RMSE = 0.488

## Project Structure :file_folder:

The project structure is organized as follows:

- `data`: Folder containing the dataset file
- `notebooks`: Jupyter notebooks with the data preprocessing, feature engineering, and model training code
- `README.md`: This file providing an overview of the project

## Contributing :raising_hand:

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License :page_with_curl:

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

