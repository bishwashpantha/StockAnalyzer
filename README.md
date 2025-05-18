# Stock Analyzer Project 

A Python script/notebook that fetches historical stock data using the yfinance library, performs basic analysis including daily returns and moving averages with Pandas, and visualizes key metrics using Matplotlib.

## Features
- Fetches historical stock price data (Open, High, Low, Close, Volume) for a given ticker.
- Calculates daily percentage returns.
- Calculates Simple Moving Averages (SMAs) for 20-day and 50-day periods.
- Visualizes:
    - Closing price over time along with SMAs.
    - Histogram of daily returns to show distribution.

## Technologies Used
- Python 3
- Jupyter Notebook
- yfinance
- Pandas
- NumPy
- Matplotlib

## Setup & How to Run

1.  **Clone the repository (if you haven't already):**
    ```bash
    git clone https://github.com/bishwashpantha/StockAnalyzer.git
    cd StockAnalyzer
    ```

2.  **Ensure you have Python installed.**

3.  **Install necessary dependencies:**
    Create a virtual environment (recommended):
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    # source venv/bin/activate
    ```
    Then install packages:
    ```bash
    pip install yfinance pandas matplotlib jupyter
    ```

4.  **Run Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Then open the `stock_analyzer.ipynb` file from the Jupyter interface in your browser.

## Example Output
*(Optional: If you have screenshots of your plots, you can add them here. You'd upload the image to your repository and then link it like: `![Plot Description](path/to/your/image.png)`)*
Example:
![AAPL Closing Price](example_plot.png) *(You would need to create and add an `example_plot.png` to your repo)*

## Future Enhancements
- [ ] Add more technical indicators (e.g., RSI, MACD).
- [ ] Implement a simple backtesting framework for a trading strategy.
- [ ] Allow user input for ticker symbol and date range.
- [ ] Create a more interactive dashboard (e.g., using Plotly Dash or Streamlit).