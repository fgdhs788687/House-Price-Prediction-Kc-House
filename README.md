# House-Price-Prediction-Kc-House
This project focuses on building a robust machine learning model to accurately predict house prices in King County, USA. Using a detailed real-world dataset, I applied a complete data science workflow, from data preprocessing to advanced model evaluation, to develop a reliable predictive system.

# Methodology and Key Features
1. Exploratory Data Analysis (EDA) & Data Cleaning: The raw dataset (kc_house_data.csv) was meticulously cleaned by handling missing values and outliers. I performed extensive EDA to understand feature relationships and prepare the data for modeling, resulting in a refined dataset (Cleaned_data_for_training_house_price_predictions.csv).

2. Feature Engineering: To improve the model's predictive power, a new feature, zipcode-based average pricing, was created. This method effectively incorporates location, a highly influential factor, into the model.

3. Model Building & Evaluation: I trained and compared two distinct regression models to determine the optimal approach:

- Linear Regression (Baseline): A foundational model was built to establish a performance benchmark, achieving an R² score of 0.78.

- Polynomial Regression (Advanced): A second-degree polynomial model was developed to capture the non-linear relationships in the data. This model demonstrated superior performance with an R² score of 0.878, showing a significant improvement in accuracy, especially for higher-priced homes.

4. Model Validation: The final model's performance was validated using key metrics and diagnostic plots, such as residual plots, to ensure its reliability and confirm that it was a better fit for the data.

# Technologies and Libraries
- Python: The core programming language used for the project.

- Pandas & NumPy: For efficient data manipulation and numerical operations.

- Scikit-learn: For building and evaluating machine learning models.

- Matplotlib & Seaborn: For creating insightful data visualizations.
