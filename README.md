# Heart Disease Prediction Project

This project aims to predict the presence of heart disease in individuals based on various health and lifestyle factors using machine learning techniques.

## Project Overview

The project follows a standard machine learning workflow:

1.  **Data Collection:** The heart disease dataset is downloaded from Kaggle.
2.  **Data Preprocessing:** The raw data is cleaned, missing values are handled (imputed with the mean), and categorical features are one-hot encoded.
3.  **Exploratory Data Analysis (EDA):** The data is explored through visualizations (histograms and heatmaps) to understand the distributions of features and their correlations.
4.  **Model Training:** Logistic Regression and Random Forest classifiers are trained on the preprocessed data.
5.  **Model Evaluation:** The performance of the models is evaluated using metrics like accuracy score and confusion matrix.
6.  **Feature Importance:** Feature importance is analyzed for the Random Forest model to identify the most influential features in predicting heart disease.
7.  **Model Saving:** The trained Random Forest model and the scaler used for data preprocessing are saved for future use.
8.  **Prediction on New Data:** A template CSV file is created to demonstrate how to format new data for prediction, and the saved model is used to predict heart disease on a sample dataset.

## Dataset

The dataset used in this project is the "Heart Disease Data" from Kaggle, available [here](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).

## Dependencies

The following libraries are required to run this project:

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   sklearn
-   joblib

## Usage

1.  Clone the repository.
2.  Install the required dependencies using pip: `pip install pandas numpy matplotlib seaborn scikit-learn joblib kaggle`
3.  Download the Kaggle dataset by following the instructions in the notebook.
4.  Run the Jupyter Notebook or Python script containing the code.

## File Descriptions

-   `heart_disease_uci.csv`: The raw dataset downloaded from Kaggle.
-   `heart_rf_model.pkl`: The saved trained Random Forest model.
-   `heart_scaler.pkl`: The saved StandardScaler object used for data scaling.
-   `Heart_user_template.csv`: A template CSV file for new user data prediction.
-   `heart_dataset.csv`: A sample dataset for predicting heart disease.

## Results

-   The accuracy of the Logistic Regression model is calculated and printed.
-   A confusion matrix for the Logistic Regression model is displayed.
-   The accuracy of the Random Forest model is calculated and printed.
-   A bar plot showing the feature importance from the Random Forest model is displayed.
-   The predictions on the sample user data (`heart_dataset.csv`) are added as a new column to the dataframe and printed.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

[Specify your license here, e.g., MIT License]
