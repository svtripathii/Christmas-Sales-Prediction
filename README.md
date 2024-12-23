# Christmas Sales and Trends Prediction

This project aims to analyze Christmas sales and trends, focusing on predicting the total price of items based on various features such as customer demographics, product category, quantity, discount, and weather. The analysis is performed using machine learning models, and the results are visualized with various plots.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Analysis](#analysis)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The objective of this project is to predict total prices of items in the dataset using a machine learning model. We explore different sales trends based on customer demographics, weather conditions, promotion applications, and other factors. The project includes both exploratory data analysis (EDA) and predictive modeling.

## Dataset

The dataset used in this project is the **Christmas Sales and Trends** dataset, which includes the following columns:

- **Age**: Customer age
- **Gender**: Customer gender (Male/Female)
- **Category**: Product category (e.g., Electronics, Toys, etc.)
- **Quantity**: Number of items bought
- **UnitPrice**: Price per unit
- **DiscountAmount**: Discount applied to the item
- **CustomerSatisfaction**: Rating provided by the customer
- **OnlineOrderFlag**: Whether the order was placed online
- **PromotionApplied**: Whether a promotion was applied to the order
- **GiftWrap**: Whether the order includes gift wrapping
- **ShippingMethod**: Shipping method chosen by the customer (e.g., Standard, Express)
- **Weather**: Weather conditions at the time of the order (Sunny, Rainy, etc.)
- **TotalPrice**: The total price of the order (target variable)

## Installation

### Prerequisites
To run the project, you need to have Python 3.x installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries by running the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

Clone the Repository
Clone this repository to your local machine using the following command:
git clone https://github.com/svtripathii/Christmas-Sales-Prediction.git

Analysis
The data analysis consists of the following steps:

Data Preprocessing:

Load and inspect the dataset.
Handle missing values by filling numerical columns with the mean and categorical columns with "Unknown".
Feature selection and transformation.
Exploratory Data Analysis (EDA):

Visualize sales distribution, top categories, daily sales trends, and sales by day of the week.
Plot residuals and actual vs predicted total prices.
Modeling:

Use a Linear Regression model to predict the total price.
Evaluate the model's performance with metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.
Prediction:

Predict the total price for new customer data.
Model
The model used in this project is a Linear Regression model, which is trained on the processed dataset to predict the total price of items based on customer and order features. The model is evaluated using various metrics to ensure its accuracy and reliability.

Model Evaluation Metrics:
Mean Absolute Error (MAE): The average of the absolute errors between the actual and predicted values.
Mean Squared Error (MSE): The average of the squared differences between actual and predicted values.
R² Score: A measure of how well the model explains the variance in the target variable.
Results
The results of the analysis and model evaluation are stored in the results folder. It contains the following plots:

Total Price Distribution
Top 10 Product Categories by Total Price
Daily Sales Trend
Sales by Day of the Week
Residuals Distribution
Actual vs Predicted Total Price
These plots provide insights into the sales patterns and the model's performance.

Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Ensure that your code follows the project's style guide and passes all the tests.

License
This project is licensed under the MIT License - see the LICENSE file for details.
