# Car Price Predictor

A Flask-based web application that predicts the selling price of used cars based on company, model, year, fuel type, and kilometers driven.

## Features

- **Interactive Form**: Select car company, model, year, fuel type, and enter kilometers driven
- **ML-Powered**: Uses a trained Linear Regression model for price prediction
- **Web Interface**: Clean Bootstrap UI for easy user interaction

## Setup

1. **Install dependencies**
   ```
   pip install flask pandas numpy scikit-learn
   ```

2. **Run the application**
   ```
   python application.py
   ```

3. Open `http://127.0.0.1:5000` in your browser

## Project Structure

```
├── application.py          # Flask app & prediction logic
├── LinearRegressionModel.pkl  # Trained model
├── Cleaned_Car_data.csv    # Car dataset
├── templates/
│   └── index.html          # Main UI
└── static/css/
    └── style.css           # Styles
```

## Technologies

- **Backend**: Flask, Python
- **ML**: scikit-learn (Linear Regression)
- **Frontend**: HTML, Bootstrap, jQuery
