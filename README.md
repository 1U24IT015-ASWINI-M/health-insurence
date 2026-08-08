
#HEALTH INSURANCE PREMIUM PREDICTION
Project Overview

Health Insurance Premium Prediction is a Machine Learning project that predicts an individual's health insurance charges based on personal, demographic, and health-related factors.

The project uses a dataset containing 1,338 records and 7 features: Age, Sex, BMI, Children, Smoker, Region, and Charges. The main objective is to understand the factors that influence insurance pricing and build a model that can estimate insurance charges accurately.

The project follows a complete Machine Learning workflow, including data loading, data exploration, preprocessing, feature selection, train-test splitting, model building, prediction, and model evaluation. Categorical features such as sex, smoker, and region are prepared for Machine Learning using encoding techniques, and the data is divided into training and testing sets.

Three Linear Regression models are developed and compared:

Model 1: Uses Age only.
Model 2: Uses Age and BMI.
Model 3: Uses all available features, including categorical features.

The models are evaluated using Mean Squared Error (MSE) and R-squared (R²). The first two models show underfitting because they use limited features, while the final model using all features achieves better performance, with training and testing R² values of 0.736 and 0.772, respectively. This indicates good generalization on unseen data.

Technologies Used

Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Linear Regression

Key Outcome

The project demonstrates how Machine Learning can be used to estimate health insurance charges and identify important factors affecting insurance pricing, helping insurance companies make more informed and data-driven decisions.
