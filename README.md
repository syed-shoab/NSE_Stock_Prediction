# NSE Stock Monitoring & Prediction using Robotic Process Automation

A Python-based desktop application that uses machine learning and Robotic Process Automation (RPA) to download, analyze, and predict stock prices for NSE-listed companies.  
It provides an interactive interface for users to monitor stock data, perform correlation analysis, run KNN-based predictive models, and visualize prediction results.

---

## 🚀 Features

- Download historical stock data from Yahoo Finance  
- Data preprocessing with feature engineering  
- Perform correlation analysis on stock data  
- KNN Regression model for stock price prediction (Uniform & Distance Weighted)  
- Visualize prediction results and model accuracy with interactive graphs  
- Simple GUI built using Tkinter

---

## 📁 Folder Structure

NSE-Stock-Monitoring-Prediction/
│
├── Code/
│ ├── app.py # Streamlit app for web deployment
│ ├── stockpredictfinal.py # Core application logic
│ ├── tempcoderunner.py # GUI setup
│ ├── requirements.txt # Python dependencies
│ └── Yahoo-Finance-Dataset/
│ ├── pred.csv # Test dataset for predictions
│ ├── competitor_YahooDataSet.csv
│ └── Apple_YahooDataSet.csv
│
├── knnDistPredGraph.png # Generated accuracy graph
├── knnUniformPredGraph.png
└── README.md


---

## ⚙️ How to Run Locally

### 1️⃣ Install Python (version 3.8 or higher)  
Download from [python.org](https://www.python.org/downloads/)

### 2️⃣ Clone the repository

bash
git clone https://github.com/yourusername/NSE-Stock-Monitoring-Prediction.git
cd NSE-Stock-Monitoring-Prediction/Code 

### 3️⃣ Install dependencies
pip install -r requirements.txt


4️⃣ Run the Application Locally
Option 1: Tkinter GUI (Desktop App)
python stockpredictfinal.py


The GUI will open, allowing you to:
Download dataset
Perform data preprocessing
Run KNN model
Predict stock prices
Visualize graphs

Option 2: Streamlit Web App (Optional)
streamlit run app.py

Access the app in your browser at http://localhost:8501


### 🎯 Future Scope

Extend the system into full-fledged automated trading or portfolio management platforms
Integrate real-time stock data streaming for live monitoring
Use advanced models like LSTM for improved prediction accuracy

###⚡ Technologies Used

Python
Tkinter (GUI)
Streamlit (Web App)
yfinance (Stock Data API)
Pandas, NumPy (Data Manipulation)
scikit-learn (KNN Regression)
Matplotlib, Seaborn (Data Visualization)

### 📚 License

This project is for academic purposes and personal use.
