# AI-ML-Project---inventory-forecast:


Objective: Develop an AI/ML system to forecast inventory demand using historical sales, pricing, and external factors, optimizing stock levels and reducing costs.

Models Used: XGBoost, Random Forest, Prophet, ARIMA, and deep learning (LSTM, transfer learning with TensorFlow/Keras).

Data Inputs: Sales history, inventory levels, product details, seasonality, promotions, and supplier lead times.

Key Features:

1.Demand forecasting with MAPE-based accuracy evaluation

2.Safety stock and reorder point (ROP) calculation

3.Real-time dashboard (Streamlit/Flask) for visualization

4.Automated alerts for low stock and reordering

Project Structure:

data/: Raw and processed datasets

notebooks/: EDA and model prototyping

src/: Preprocessing, modeling, and forecasting scripts

models/: Saved model checkpoints

outputs/: Reports, visualizations, predictions

Tech Stack: Python, pandas, scikit-learn, statsmodels, Prophet, TensorFlow, Streamlit

Installation: pip install -r requirements.txt

Usage:

1.Run full pipeline: python run_analysis.py

2.Launch dashboard: python run_analysis.py --dashboard

3.Evaluation Metrics: RMSE, MAE, MAPE

4.Deployment: API or interactive dashboard for business integration
