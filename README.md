![Screenshot 2024-10-25 100847](https://github.com/user-attachments/assets/fc55344c-57d8-459a-b0e5-10044defe697)

# House Price Prediction using Linear Regression

## Project Overview
This project aims to build a predictive model using linear regression to estimate house prices based on various features. The goal is to provide hands-on experience in developing, evaluating, and interpreting a predictive model in Python.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Dataset
The dataset used for this project can be found [here](https://www.kaggle.com/code/ashydv/housing-price-prediction-linear-regression).

### Sample Data
Here are the first five rows of the dataset:

|    price |   area |   bedrooms |   bathrooms |   stories | mainroad   | guestroom | basement | hotwaterheating | airconditioning |   parking | prefarea   | furnishingstatus |
|----------|--------|------------|-------------|-----------|------------|-----------|----------|------------------|------------------|-----------|------------|------------------|
| 13300000 |   7420 |          4 |           2 |         3 | yes        | no        | no       | no               | yes              |         2 | yes        | furnished        |
| 12250000 |   8960 |          4 |           4 |         4 | yes        | no        | no       | no               | yes              |         3 | no         | furnished        |
| 12250000 |   9960 |          3 |           2 |         2 | yes        | no        | yes      | no               | no               |         2 | yes        | semi-furnished    |
| 12215000 |   7500 |          4 |           2 |         2 | yes        | no        | yes      | no               | yes              |         3 | yes        | furnished        |
| 11410000 |   7420 |          4 |           1 |         2 | yes        | yes       | yes      | no               | yes              |         2 | no         | furnished        |

## Key Steps
1. **Import Libraries**: Load necessary libraries for data manipulation and visualization.
2. **Load Dataset**: Import the dataset from a CSV file.
3. **Explore the Data**: Analyze the data structure and summary statistics.
4. **Data Cleaning**: Handle missing values and ensure data quality.
5. **Feature Selection**: Analyze and select relevant features for the model.
6. **Split the Data**: Divide the dataset into training and testing sets.
7. **Train the Model**: Implement linear regression using the training data.
8. **Make Predictions**: Predict house prices using the test data.
9. **Evaluate the Model**: Assess model performance using metrics like MSE and R-squared.
10. **Visualize Results**: Create plots to illustrate model performance.

## Key Insights
1. **Mean Squared Error (MSE)**: The high MSE (2,292,721,545,725.36) suggests that the model's predictions have large errors when compared to actual house prices. This could be due to the large scale of price values.

2. **R-squared Value (0.546)**: The model explains about 54.6% of the variation in house prices based on the selected features. While it's capturing some relationships, nearly half of the variance remains unexplained.

3. **Improvement Needed**: The model could be improved by trying additional features, refining the current ones, or exploring different modeling techniques to increase accuracy and reduce errors.

