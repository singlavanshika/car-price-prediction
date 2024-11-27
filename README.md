# Predicting Used Car Prices Using Machine Learning

This project leverages machine learning to predict the resale value of used cars based on various features, such as age, mileage, fuel type, and more. By building a Linear Regression model, the project aims to help buyers and sellers make informed decisions with accurate price estimates.

## Dataset

- **Size**: 205 rows × 26 columns
- **Features:**
  - `Fuel_Type`
  - `Transmission`
  - `Engine Size`
  - `Curb Weight`
  - `No of Doors`
  - `Horse Power`
  - `Make`
  - `Price`
- **Missing Values**: Data was cleaned to handle missing and inconsistent values.

## Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Model

### Algorithm Used
- **Linear Regression**: Chosen for its simplicity and interpretability.

### Evaluation Metrics
| **Metric**                | **Value**    |
|---------------------------|--------------|
| R² (Coefficient of Determination) |0.83|
| Root Mean Squared Error (RMSE)    |19044.6|


## Results

The Linear Regression model demonstrates an R² score of **0.83**, indicating that it can explain 83% of the variance in car prices. The model's average error is approximately Rs. 19044.6, which is acceptable for the dataset's price range.
