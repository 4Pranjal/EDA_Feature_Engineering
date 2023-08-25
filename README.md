# Black Friday Dataset EDA and Feature Engineering

This repository contains a comprehensive analysis of the Black Friday dataset using Exploratory Data Analysis (EDA) techniques and feature engineering. The objective is to understand the dataset, handle missing values, preprocess categorical features, and prepare the data for model training.

## Dataset Overview

The Black Friday dataset used for this analysis is available [here](https://www.kaggle.com/sdolezel/black-friday?select=train.csv). It includes information about customer transactions during a Black Friday sale. The dataset has been divided into training and test subsets.

## Approach

1. **Data Cleaning and Merging:** The training and test datasets were imported and merged to create a single dataset for analysis.

2. **Basic Dataset Information:** The dataset's structure was examined using `info()` and `describe()` functions to understand data types, missing values, and basic statistics.

3. **Data Cleaning:** Irrelevant columns, such as 'User_ID', were dropped from the dataset. The 'Gender' feature was encoded using one-hot encoding and mapped to binary values.

4. **Handling Categorical Features:** 'Age' was categorized and encoded into numerical values. 'City_Category' was handled by generating dummy variables using one-hot encoding.

5. **Handling Missing Values:** Missing values in 'Product_Category_2' and 'Product_Category_3' were replaced with their respective modes.

6. **Data Visualization:** Visualizations were created to explore relationships between features and the target variable 'Purchase'. Bar plots depicted purchasing behavior across age groups, occupations, and product categories.

7. **Feature Scaling:** The dataset was split into training and testing subsets for model training. 'Product_ID' was dropped, and feature scaling was performed using `StandardScaler`.

## Results and Insights

- Purchasing by men during Black Friday is higher than purchasing by women.
- Occupation has a notable impact on purchasing behavior, with certain occupations spending more.
- Product categories 1, 2, and 3 have distinct purchasing patterns.
- Feature scaling ensures consistent scales for model training.

## Next Steps and Advice

- Proceed with predictive modeling: After EDA and feature engineering, the dataset is ready for predictive modeling. Techniques like regression or classification can be applied to predict purchasing behavior.
- Evaluate model performance: Train and evaluate different models to identify the most accurate one for predicting purchases.
- Iterative analysis: As new insights emerge, consider revisiting the dataset for further analysis and refinement of the model.
- Share findings: If these analyses lead to interesting insights, share them with others to contribute to the data science community.

## Repository Structure

- `blackFriday_train.csv` and `blackFriday_test.csv`: Dataset files used for analysis.
- `Black_Friday_EDA.ipynb`: Jupyter Notebook containing the code for EDA and feature engineering.
- `README.md`: The current file, providing an overview of the project.

## Acknowledgments

The dataset used in this analysis is available on Kaggle and was originally sourced from a Black Friday sales data collection.

## Contact Information

For any inquiries or suggestions, feel free to reach out to me on GitHub at [@4Pranjal](https://github.com/4Pranjal).

## Author

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).

Made with ❤️ by [Pranjal Jain](https://github.com/4Pranjal)
