# ✈️ Airline Delay Prediction

A machine learning project that predicts airline arrival delays using regression models.

## 📁 Project Structure
airline-delay-prediction/
│
├── airline_delay_regression.ipynb   # Main analysis notebook
├── airline_delay_data.csv           # Dataset
├── requirements.txt                 # Python dependencies
└── README.md                        # Project documentation

## 📊 Dataset
The dataset contains flight records with features like departure delay,
weather conditions, distance, and load factor to predict arrival delay (in minutes).

## 🔧 Features Used
- `dep_delay_min` — Departure delay in minutes
- `weather_origin` / `weather_dest` — Weather severity at origin/destination
- `distance_km` — Flight distance
- `load_factor_pct` — Aircraft load factor

## 🧠 Methods
- Exploratory Data Analysis (EDA)
- Data Cleaning (duplicates, missing values, outlier removal via IQR)
- Min-Max Normalization
- Linear Regression model

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/YOUR_USERNAME/airline-delay-prediction.git
   cd airline-delay-prediction
```

2. Install dependencies:
```bash
   pip install -r requirements.txt
```

3. Open the notebook:
```bash
   jupyter notebook airline_delay_regression.ipynb
```

## 🛠️ Requirements
See `requirements.txt` for the full list of dependencies.

## 📬 Author
Your Name — [github.com/mokshaggarwal12]