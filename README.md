# Stock Price Prediction

This project aims to predict the stock prices using machine learning and deep learning techniques. The application provides various functionalities such as fetching stock data, analyzing historical trends, and predicting future prices using a trained model.

## Project Overview

The Stock Price Prediction project is designed to help users predict the future prices of stocks based on historical data. It leverages multiple machine learning and deep learning models to analyze and predict stock trends. The project includes a web application built with Flask, which provides an interactive user interface for users to input stock symbols and view predictions along with visualizations.

## Features

- Fetching real-time stock data from Yahoo Finance.
- Analyzing historical stock data with various technical indicators.
- Predicting future stock prices using a pre-trained LSTM model.
- Visualizing stock trends and prediction results.
- Displaying relevant news articles related to the stock.

## Setup and Installation

Follow these steps to set up and run the project on your local machine:

### Prerequisites

- Python 3.7 or higher
- Git
- Virtual environment (optional but recommended)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/prithvirajjadhav2266/Stock_Price_Prediction.git
   cd Stock_Price_Prediction
   ```

2. **Create and activate a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application:**

   ```bash
   flask run
   ```

5. **Access the application:**

   Open your web browser and go to `http://127.0.0.1:5000/` to access the application.

## Usage

1. **Enter the stock symbol:**
   - On the home page, enter the stock symbol you wish to analyze and predict.

2. **View stock data and predictions:**
   - The application will fetch the historical stock data, analyze it, and display various charts including Exponential Moving Averages (EMA) and prediction results.

3. **Download dataset:**
   - You can download the analyzed dataset as a CSV file.

4. **View relevant news articles:**
   - The application also displays news articles related to the stock to provide context and additional information.

## Results and Visualizations

Below are some example images showing how the application looks after setup and running:

### Example 1: Home Page

![Home Page](static/images/home_page.png)

### Example 2: Stock Analysis

![Stock Analysis](static/images/stock_analysis.png)

### Example 3: Prediction Results

![Prediction Results](static/images/prediction_results.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please contact prj09977@gmail.com.
