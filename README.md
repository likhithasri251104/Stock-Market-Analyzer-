# 📈 Stock Market Analyzer - Java Project

A Java-based application designed to analyze stock market data by fetching historical prices, performing technical analysis, and generating visual reports to assist investors in making informed decisions.

---

## 🚀 Project Overview

The Stock Market Analyzer is a Java application that allows users to:

- Retrieve historical stock price data from online sources or local files
- Calculate key technical indicators like Moving Averages (MA), Relative Strength Index (RSI), Bollinger Bands, etc.
- Visualize stock price trends and indicator graphs
- Generate summary reports with buy/sell signals
- Export analysis results for further review

This tool is ideal for beginner investors, students, or developers interested in stock market data processing using Java.

---

## 🛠️ Features

- Fetch historical stock data from APIs or CSV files
- Compute popular technical indicators
- Interactive charts using Java libraries (e.g., JFreeChart)
- Customizable date ranges and stock selection
- Export reports to PDF or CSV
- Command-line interface (CLI) or simple GUI (Swing/JavaFX)

---

## 🧱 Tech Stack

| Technology       | Description                          |
|------------------|------------------------------------|
| Java SE          | Core programming language           |
| JFreeChart       | Charting and visualization library |
| Apache Commons CSV | CSV parsing and exporting          |
| HttpClient (Java 11+) | Fetch data from online APIs       |
| Maven / Gradle   | Build automation and dependency management |

---

## 📁 Project Structure

stock-market-analyzer/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ ├── analyzer/
│ │ │ │ ├── StockDataFetcher.java
│ │ │ │ ├── TechnicalIndicators.java
│ │ │ │ ├── ReportGenerator.java
│ │ │ │ ├── ChartRenderer.java
│ │ │ │ └── Main.java
│ └── resources/
│ └── config.properties
├── data/
│ └── sample_stock_data.csv
├── pom.xml (or build.gradle)
└── README.md



---

## 🔧 Installation & Setup

### Prerequisites

- Java Development Kit (JDK) 11 or higher
- Maven or Gradle build tool
- Internet connection for API data fetching (optional)



🔍 Usage
Choose to fetch live stock data or load from a CSV file

Select the stock ticker symbol and desired date range

Run analysis to calculate technical indicators

View generated charts and signals

Export results to CSV or PDF for offline use

📈 Technical Indicators Implemented
Simple Moving Average (SMA)

Exponential Moving Average (EMA)

Relative Strength Index (RSI)

Bollinger Bands

Moving Average Convergence Divergence (MACD)

⚙️ Configuration
Edit the config.properties file to customize:

API endpoints and keys (if applicable)

Default stock symbols and date ranges

Output directories for reports and charts

🛡️ Security & Privacy
API keys (if any) should be stored securely and not hardcoded

Application does not store personal user data

Only public stock market data is accessed
