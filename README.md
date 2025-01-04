# stock_prediction
A project focused on building machine learning models to predict stock market trends and prices using historical data. Includes data preprocessing, visualization, and algorithm implementation.

**Google Stock Analysis and Prediction**

**Overview**
This project focuses on analyzing and predicting Google stock prices using a combination of data analysis, machine learning, and deep learning techniques. The script processes historical stock data, performs exploratory data analysis, visualizes key trends, and implements predictive models using Random Forest and LSTM.
Features
  •	Data Cleaning: Handles missing values, removes duplicates, and drops irrelevant columns.
  •	Exploratory Data Analysis (EDA): Computes statistics like average daily price change, closing prices, and volume, along with moving averages.
  •	Visualizations:
  o	Stock price trends
  o	7-day and 30-day moving averages
  o	Volume bars
  o	Subplots for various features
  •	Machine Learning: Implements Random Forest Regression to identify feature importance.
  •	Deep Learning: Uses an LSTM model to predict future stock prices.
**Requirements**
To run this project, you need:
  •	Python 3.x
  •	Libraries:
  o	pandas
  o	matplotlib
  o	scikit-learn
  o	numpy
  o	tensorflow
  o	keras
**Installation**
**  Clone this repository:**
    bash
    Copy code
    git clone <repository_url>
    cd <repository_folder>
  **Install required Python libraries:**
    bash
    Copy code
    pip install -r requirements.txt
    (Ensure to include a requirements.txt in the repository with all dependencies.)
  Place the GOOG.csv dataset in the project directory.
    Usage
  Run the script to analyze and visualize the data:
    bash
    Copy code
    python stock_analysis.py
	  **The script will:**
      o	Clean and prepare the data.
      o	Perform statistical analysis and generate visualizations.
      o	Train and evaluate machine learning and deep learning models.
  	**Outputs include:**
      o	Visualizations of stock trends and moving averages.
      o	Key metrics and statistics displayed in the console.
      o	Predictions of stock prices visualized against actual data.
**File Structure**
      •	stock_analysis.py: The main script for data analysis and prediction.
      •	GOOG.csv: Historical Google stock price data.
      •	README.md: Project documentation.
**Key Insights**
      •	Average daily price change and trading volume.
      •	Trends in closing prices and moving averages.
      •	Predicted stock prices compared with actual prices.
**Results**
The LSTM model produces a graph comparing predicted stock prices with actual values, demonstrating the model's ability to capture trends in stock prices.

