# 🏡 Housing Price Prediction

This project predicts house prices using Machine Learning models, specifically utilizing **XGBoost** for optimal performance. The dataset includes various features such as location, number of rooms, population, and income levels.

## 📌 Features
- **Data Preprocessing**: Handling missing values, feature engineering, and scaling.
- **Model Training**: Implementing and tuning XGBoost for accurate predictions.
- **Evaluation**: Measuring performance using Mean Absolute Error (MAE).
- **Hyperparameter Optimization**: Using GridSearchCV to find the best parameters.

## 📂 Dataset
The dataset contains housing-related attributes such as:
- `longitude` & `latitude` - Geographical location
- `housing_median_age` - Age of the house
- `total_rooms` & `total_bedrooms` - Number of rooms
- `population` - Total population in the area
- `median_income` - Average income of the residents
- `ocean_proximity` - Categorical feature indicating the proximity to the ocean

## 🛠 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/housing-price-prediction.git
   cd housing-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model:
   ```bash
   python train_model.py
   ```

## 📊 Model Performance
- **Baseline MAE**: 89,210
- **Improved MAE (XGBoost)**: 32,640 (≈ 63% improvement)

## 🚀 Next Steps
- Further hyperparameter tuning.
- Trying different models like LightGBM.
- Deploying the model as an API using Flask or FastAPI.

## 🤝 Contributing
Feel free to open issues or submit pull requests to improve the project!

## 📜 License
This project is open for your use.

