# Stock Prediction

A project focused on building machine learning models to predict stock market trends and prices using historical data. The project includes data preprocessing, visualization, and the implementation of predictive algorithms.

---

## Google Stock Analysis and Prediction

### Overview
This project analyzes and predicts Google stock prices using a combination of data analysis, machine learning, and deep learning techniques. It processes historical stock data, performs exploratory data analysis (EDA), visualizes key trends, and implements predictive models such as Random Forest Regression and Long Short-Term Memory (LSTM) networks.

---

### Features
- **Data Cleaning**: Handles missing values, removes duplicates, and drops irrelevant columns.
- **Exploratory Data Analysis (EDA)**: Computes statistics such as:
  - Average daily price change
  - Closing prices
  - Trading volume
  - Moving averages (7-day and 30-day)
- **Visualizations**:
  - Stock price trends
  - 7-day and 30-day moving averages
  - Volume bars
  - Subplots for multiple features
- **Machine Learning**:
  - Implements Random Forest Regression to identify feature importance.
- **Deep Learning**:
  - Uses an LSTM model to predict future stock prices.

---

### Requirements
To run this project, you need:
- **Python 3.x**
- Libraries:
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `numpy`
  - `tensorflow`
  - `keras`

---

### Installation
1. Clone this repository:
   ```bash
   git clone [<repository_url>](https://github.com/AREEB-0928/stock_prediction)
   cd stock_prediction
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure to include a `requirements.txt` file in the repository with all dependencies.)*

3. Place the `Data_Set.csv` dataset in the project directory.

---

### Usage
Run the script to analyze and visualize the data:
```bash
python stock_analysis.py
```
The script will:
- Clean and prepare the data.
- Perform statistical analysis and generate visualizations.
- Train and evaluate machine learning and deep learning models.

#### Outputs include:
- Visualizations of stock trends and moving averages.
- Key metrics and statistics displayed in the console.
- Predictions of stock prices visualized against actual data.

---

### File Structure
- **`stock_analysis.py`**: The main script for data analysis and prediction.
- **`Data_Set.csv`**: Historical Google stock price data.
- **`README.md`**: Project documentation.

---

### Key Insights
- Average daily price change and trading volume.
- Trends in closing prices and moving averages.
- Predicted stock prices compared with actual prices.

---

### Results
The LSTM model produces a graph comparing predicted stock prices with actual values, demonstrating its ability to capture trends and patterns in stock prices.

