# Stock Data Visualization with Bokeh

This README provides an overview of the stock data visualization application built using Bokeh, Python, and Yahoo Finance. This application allows users to compare two stocks and visualize their data with various indicators.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Features](#features)
6. [Configuration](#configuration)
7. [License](#license)

## Introduction

This project is a stock data visualization tool that uses Bokeh to create interactive charts. Users can input stock tickers, select a date range, and choose from various technical indicators to visualize the stock data.

## Requirements

To run this application, you need:

- Python 3.x
- Bokeh
- NumPy
- yfinance

You can install the required Python packages using pip:

```bash
pip install bokeh numpy yfinance
```

## Setup

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies:**

   Install the necessary Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Bokeh Server:**

   Navigate to the directory containing your `app.py` file and run the Bokeh server with:

   ```bash
   bokeh serve --show app.py
   ```

   This command will start a Bokeh server and open the application in your default web browser.

## Usage

1. **Open the Application:**

   The Bokeh server should open your default web browser and navigate to the application. If not, you can manually go to `http://localhost:5006/app`.

2. **Input Stock Data:**

   - Enter the ticker symbol for the main stock in the "Main Stock" field.
   - Enter the ticker symbol for the comparison stock in the "Comparison Stock" field.
   - Select the start and end dates using the date pickers.
   - Choose the indicators you want to display from the multi-choice dropdown.

3. **Load Data:**

   Click the "Load Data" button to fetch the stock data and update the charts.

## Features

- **Stock Data Comparison:** Compare two stocks side by side.
- **Technical Indicators:**
  - 30 Day Simple Moving Average (SMA)
  - 100 Day Simple Moving Average (SMA)
  - Linear Regression Line
- **Interactive Plots:** Zoom, pan, and save the plots.
- **Date Range Selection:** Choose custom start and end dates for the data.

## Configuration

- **Technical Indicators:** You can select from "100 Day SMA", "30 Day SMA", and "Linear Regression Line" for visualization.
- **Date Range:** The date pickers allow for custom date range selection. The default range is from January 1, 2020, to February 1, 2020.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to extend or modify this application to better suit your needs. Enjoy exploring stock data with Bokeh!
