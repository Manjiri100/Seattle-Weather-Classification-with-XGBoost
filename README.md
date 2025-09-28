🌦️ Seattle Weather Classification with XGBoost
Project Description

Predict Seattle weather conditions using XGBoost! This project classifies daily weather as sunny, rainy, or cloudy using historical weather data.

💡 Features:

Data preprocessing 🧹

Label encoding & normalization 🔢

XGBoost model training 🚀

Hyperparameter tuning with GridSearchCV ⚙️

Accuracy & classification evaluation 📊

📂 Dataset

File: seattle-weather.csv

Columns:

date – Date of observation 📅

precipitation – Rainfall amount 🌧️

temp_max – Maximum temperature 🌡️

temp_min – Minimum temperature 🌡️

wind – Wind speed 🌬️

weather – Weather condition (target variable) 🌤️

Example Snapshot:


🛠️ Data Preprocessing

Label Encoding 🔢

Converts categorical weather column into numerical labels.

Example: 'rain' → 0, 'sun' → 1.

Normalization ⚖️

Scales numerical features (precipitation, temp_max, temp_min, wind) between 0 and 1.

Feature Selection ✂️

Drops the date column.

Separates features (X) and target (y).

Preprocessing Screenshot:


📊 Model Training

Algorithm: XGBClassifier 🚀

Train-Test Split: 80% training, 20% testing 🧪

Evaluation Metrics: Accuracy ✅, Precision 🎯, Recall 🔄, F1-score 🏆

Training Screenshot:


⚙️ Hyperparameter Tuning

Used GridSearchCV to find the best combination of:

max_depth – Depth of trees 🌲

n_estimators – Number of boosting rounds 🔢

learning_rate – Step size for weight updates ⚡

Cross-validation ensures the model generalizes well 🔍

Hyperparameter Tuning Screenshot:


📈 Results

Achieved high classification accuracy on the test set 🏅

Detailed classification report shows precision, recall, and F1-score for each weather category

Results Screenshot:


🚀 How to Run
# Clone the repository
git clone <your-repo-url>

# Install dependencies
pip install pandas xgboost scikit-learn

# Run the Python script or Jupyter notebook
python seattle_weather_xgb.py

📌 Highlights

Easy-to-follow preprocessing and training pipeline 🧩

Optimized XGBoost classifier with hyperparameter tuning ⚡

Clear evaluation metrics for performance assessment 📊


<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/6a2983a1-ea85-4f39-a56d-d5a25de994a5" />




















