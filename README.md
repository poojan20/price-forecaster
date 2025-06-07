<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Price-Forecaster README</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      max-width: 800px;
      margin: 30px auto;
      padding: 0 20px;
      color: #2c3e50;
      background-color: #fdfdfd;
    }
    h1, h2, h3 {
      color: #34495e;
      margin-top: 1.5em;
    }
    h1 {
      font-size: 2.5em;
      border-bottom: 2px solid #2980b9;
      padding-bottom: 0.3em;
    }
    pre {
      background: #ecf0f1;
      padding: 15px;
      border-radius: 5px;
      overflow-x: auto;
      font-size: 0.95em;
      color: #2c3e50;
      box-shadow: inset 0 0 5px #bdc3c7;
    }
    code {
      font-family: Consolas, "Courier New", monospace;
      background: #ecf0f1;
      padding: 2px 5px;
      border-radius: 3px;
      font-size: 0.95em;
    }
    ul {
      margin-left: 1.2em;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    hr {
      border: none;
      border-top: 1px solid #bdc3c7;
      margin: 2em 0;
    }
    p {
      margin-top: 1em;
    }
  </style>
</head>
<body>

  <h1>Price-Forecaster</h1>

  <p><strong>Price-Forecaster</strong> is a machine learning project that predicts the next day's stock closing price using historical stock data and technical indicators. It uses a Random Forest Regressor to forecast prices.</p>

  <p>The project currently uses Apple Inc. (<code>AAPL</code>) stock data as an example, but can be adapted easily to any stock ticker supported by Yahoo Finance by changing the ticker symbol in the code.</p>

  <hr />

  <h2>Features</h2>
  <ul>
    <li>Predicts next-day stock closing price</li>
    <li>Uses historical price data: Open, High, Low, Volume</li>
    <li>Includes technical indicators: 20-day SMA and RSI</li>
    <li>Employs Random Forest Regressor for prediction</li>
    <li>Visualizes actual vs predicted stock prices</li>
    <li>Easily customizable for any stock ticker</li>
  </ul>

  <hr />

  <h2>Getting Started</h2>

  <h3>1. Clone the repository</h3>
  <pre><code>git clone https://github.com/yourusername/price-forecaster.git
cd price-forecaster
  </code></pre>

  <h3>2. Install dependencies</h3>
  <pre><code>pip install -r requirements.txt
  </code></pre>

  <p>Required libraries include:</p>
  <ul>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib</li>
    <li>seaborn</li>
    <li>scikit-learn</li>
    <li>yfinance</li>
  </ul>

  <hr />

  <h2>Usage</h2>

  <p>Open the Jupyter Notebook and set your desired stock ticker:</p>
  <pre><code>ticker = 'AAPL'  # Change to any valid ticker like 'TSLA', 'GOOGL', 'RELIANCE.NS'
  </code></pre>

  <p>Run the notebook to train the model, visualize predictions, and forecast the next day's closing price.</p>

  <hr />

  <h2>Output</h2>

  <p>The notebook generates plots comparing actual and predicted stock prices and displays evaluation metrics such as Mean Squared Error and R² score.</p>

  <hr />

  <h2>Future Improvements</h2>
  <ul>
    <li>Add more technical indicators (MACD, Bollinger Bands)</li>
    <li>Experiment with different models (XGBoost, LSTM)</li>
    <li>Deploy as a web app using Streamlit</li>
    <li>Include classification for price movement prediction (up/down)</li>
  </ul>

  <hr />

  <h2>License</h2>
  <p>This project is open source and free to use for educational and non-commercial purposes.</p>

  <hr />

  <h2>Author</h2>
  <p>Created by <strong>Poojan Trivedi</strong>.</p>
  <p>Feel free to fork, contribute, or raise issues.</p>

</body>
</html>
