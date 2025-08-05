

# NSE-Stock-Monitoring-Prediction-using-Robotic-Process-Automation


This project automates the monitoring and prediction of stocks listed on the **National Stock Exchange (NSE) of India** using **Robotic Process Automation (RPA)** and **Machine Learning (ML)**. It streamlines the collection of live stock data, visualizes trends, and uses predictive models to assist in decision-making.

---

## Features

* Automated fetching of stock data using RPA
* Organized storage of historical stock data
* Real-time data visualization and plotting
* Machine learning-based prediction of stock prices
* Scalable and modular project structure

---

## Technologies Used

* **Python**
* **Pandas**, **NumPy**, **Matplotlib**
* **Scikit-learn** (for predictive modeling)
* **NSEpy** / **yfinance** (for stock data collection)
* **RPA tools** (e.g., Python automation, Selenium)

---

## Project Structure

* `README.md` – Project documentation
* `Stock Market/` – Main project directory

  * `data/` – Collected stock data
  * `models/` – Trained ML models
  * `scripts/` – Automation and scraping scripts
  * `visualizations/` – Plots and prediction graphs

---

## How It Works

1. **Automated Data Collection**
   The RPA script fetches stock data from NSE or external APIs automatically at defined intervals.

2. **Data Processing**
   The data is cleaned and formatted using Python libraries like Pandas.

3. **Prediction Engine**
   A machine learning model is trained on historical data to predict future stock prices.

4. **Visualization**
   Charts are generated to show both actual trends and predicted prices for better understanding.

---

## Setup Instructions

1. Clone the repository:

   ```
   git clone https://github.com/Abhiram0110/NSE-Stock-Monitoring-Prediction-using-Robotic-Process-Automation
   cd NSE-Stock-Monitoring-Prediction-using-Robotic-Process-Automation
   ```

2. (Optional) Create a virtual environment:

   ```
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. Install required libraries:

   ```
   pip install -r requirements.txt
   ```

---

## Future Enhancements

* Use advanced ML models like LSTM for better accuracy
* Add support for technical indicators (SMA, EMA, RSI)
* Schedule the automation using cron or Task Scheduler
* Send stock updates via email or messaging platforms

---

## Author

**Abhiram0110**
GitHub: [https://github.com/Abhiram0110](https://github.com/Abhiram0110)

---


