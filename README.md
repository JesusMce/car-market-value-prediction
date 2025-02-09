# Car Market Value Prediction 🚗💰

## Project Overview  
This project focuses on predicting the market value of used cars using machine learning models. The dataset contains various features related to the vehicles, such as registration year, mileage, power, fuel type, and more. We trained and compared several models to identify the best-performing one.

## Objectives  
- Optimize prediction accuracy.  
- Ensure efficient model training and inference speed.  
- Compare multiple models and choose the best.  

## Dataset Description 📊  
The dataset includes information on:  
- `VehicleType`: Type of vehicle body.  
- `RegistrationYear`: Year of vehicle registration.  
- `Power`: Engine power in horsepower (HP).  
- `Mileage`: Total kilometers driven by the vehicle.  
- `Brand`: Car manufacturer.  
- `FuelType`: Type of fuel used.  
- Target variable: `Price` (in euros).

## Models Used ⚙️  
We compared the following models:  
1. **Linear Regression** - To establish a baseline.  
2. **Random Forest** - A tree-based ensemble model.  
3. **LightGBM** - Gradient boosting optimized for performance.

## Evaluation Metrics 📏  
We used **Root Mean Squared Error (RMSE)** as the evaluation metric.  
The RMSE values for each model were:  

| Model              | RMSE (lower is better) |  
|--------------------|------------------------|  
| Linear Regression  | 3267.05                |  
| Random Forest      | 2054.48                |  
| LightGBM           | 1955.09                |  

## Project Steps  
1. **Data Exploration:** Initial exploration using `head()`, `info()`, and `describe()`.  
2. **Data Cleaning:** Handling missing values and converting categorical variables.  
3. **Preprocessing:** Using pipelines for scaling and encoding variables.  
4. **Model Training:** Training and evaluating the models.  
5. **Model Comparison:** Comparing RMSE to select the best-performing model.

## Future Improvements 🚀  
- Perform hyperparameter tuning using GridSearch or RandomizedSearch.  
- Perform feature selection to improve model performance.  
- Explore external data, such as geographical data, to improve predictions.

---

## How to Run the Project 🖥️  
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/car-market-value-prediction.git
   cd car-market-value-prediction
