Solar Energy Generation Forecasting with Explainable AI
 Project Overview
This project develops an accurate, robust, and explainable forecasting framework for daily solar energy generation using machine learning techniques and weather sensor data.
It evaluates and compares ARIMA, Linear Regression, XGBoost, and LightGBM models, integrating SHAP and LIME for enhanced model interpretability and transparency.

By balancing predictive performance with explainability, the project promotes responsible and ethical adoption of AI within the renewable energy sector.

 Methods and Models Used
Data Preprocessing:

Merging solar generation and weather sensor data.

Handling missing values and duplicates.

Feature engineering (e.g., cyclic time encoding using sine and cosine transforms).

Models:

Time Series: ARIMA (as a benchmark).

Machine Learning: Linear Regression, XGBoost, LightGBM.

Explainability:

SHAP: For global feature importance analysis.

LIME: For local explanation of individual predictions.

Evaluation Metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

 Dataset
Historical solar energy generation and weather sensor readings from two solar plants.

Key Features:

Solar Irradiance

Ambient Temperature

Module Temperature

Wind Speed

Hour of the Day (transformed cyclically)

(Note: Please ensure you have the right permissions to use and share the dataset.)

 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/solar-energy-forecasting.git
cd solar-energy-forecasting
Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the main script:

bash
Copy
Edit
python main.py
Generate SHAP and LIME explanations:

bash
Copy
Edit
python explainability.py
 Requirements
Python 3.8+

pandas

numpy

scikit-learn

statsmodels

xgboost

lightgbm

shap

lime

matplotlib

seaborn

(You can generate a requirements.txt using pip freeze > requirements.txt.)

 Key Findings
Machine learning models outperformed ARIMA on dynamic and non-linear solar energy patterns.

LightGBM achieved the highest accuracy based on MAE and RMSE scores.

SHAP identified solar irradiance and temperature as the most influential features.

LIME provided clear local interpretability for individual energy predictions.

 References
Floridi & Cowls (2019). A unified framework of five principles for AI in society.

Rizk-Allah et al. (2024). Explainable AI and optimized solar forecasting model.

Zhang et al. (2023). Explainable AI for smart city solar generation.

Kuzlu et al. (2020, 2024). Explainable ML for PV forecasting.

Bhatnagar et al. (2023). ARIMA performance for solar forecasting.

(Full references listed inside the project report.)

 Author
Ravindra Chunduru — MSc Data Science and Analytics — University of Hertfordshire.

 License
This project is licensed under the MIT License — see the LICENSE file for details.
