# Flight Prices Prediction

This project predicts flight ticket prices using machine learning and provides an interactive web interface built with Streamlit. The solution includes data preprocessing, feature engineering, model training, and deployment-ready code.

## Features

- **Data Preprocessing:** Advanced pipelines using scikit-learn and feature-engine for handling categorical, datetime, and numerical features.
- **Modeling:** Uses RandomForestRegressor and XGBoost for price prediction.
- **Web App:** User-friendly Streamlit interface for making predictions.
- **Web App link:** https://flightpriceprediction-fbstakmfumqitdj8vrevyx.streamlit.app

## Project Structure

```
sagemaker-flight-prices-prediction-master/
│
├── app.py                  # Main Streamlit app
├── train.csv               # Training data (required)
├── preprocessor.joblib     # Saved preprocessing pipeline
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd sagemaker-flight-prices-prediction-master
   ```

2. **Create and activate a virtual environment:**
   ```
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

4. **Add your training data:**
   - Place your `train.csv` file in the project directory.

5. **Run the Streamlit app:**
   ```
   streamlit run app.py
   ```

6. **Access the app:**
   - Open the provided local URL in your browser.

## Usage

- Select airline, date of journey, source, destination, departure/arrival times, duration, stops, and additional info.
- The app predicts the flight price based on your input.

## Requirements

- Python 3.7+
- See `requirements.txt` for all dependencies.

## Notes

- Ensure `train.csv` is present for the app to work.
- The preprocessing pipeline and model can be retrained or updated as needed.

## License

This project is for
