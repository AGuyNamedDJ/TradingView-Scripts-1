# TradingView Strategies and Indicators (Open Source)

This repository contains a collection of custom trading strategies and indicators for TradingView, developed using Pine Script. The aim of this collection is to provide traders and investors with a diverse set of tools for technical analysis and to assist them in making more informed trading decisions.

---

## Table of Contents <a name="table-of-contents"></a>

1. [Description](#description)
2. [Features](#features)
3. [Usage](#usage)
4. [File & Directory Structure](#file-directory-structure)
   - [Institutional Strategies/](#institutional)
   - [Retail Strategies/](#retail)
5. [Disclaimer](#disclaimer)
6. [Credits](#credits)
7. [Contact Information](#contact-information)

---

## Features <a name="features"></a>

- Custom trading strategies and indicators tailored for various financial instruments, such as stocks, forex, cryptocurrencies, and commodities.
- Strategies suitable for different timeframes, ranging from intraday trading to long-term investing.
- Indicators that cover various aspects of technical analysis, including trend-following, mean reversion, volume analysis, and oscillators.
- Easy-to-use scripts that can be added to TradingView charts for quick and efficient analysis.

---

## Usage <a name="usage"></a>

1. Browse the repository and select the strategy or indicator you want to use.
2. Open the corresponding Pine Script file and copy the code.
3. Log in to your TradingView account and open the chart of the financial instrument you want to analyze.
4. Click on the "Pine Editor" tab at the bottom of the page.
5. Paste the copied code into the Pine Editor and click on the "Add to Chart" button.

You can customize the input parameters, appearance, and other settings of each script in the Pine Editor to better suit your trading style and preferences.

---

## File & Directory Structure <a name="file-directory-structure"></a>

### Institutional Strategies <a name="institutional"></a>

    1. High Volume Bars Strategy
        - Description: The High Volume Bars Strategy is an institutional trading approach designed to identify and leverage potential indicators of institutional activity. By focusing on volume as the primary indicator, this strategy identifies bars with high trading volumes that close either upwards or downwards, indicative of bullish or bearish activity, respectively. Buy signals are generated when a high-volume bar closes higher, and sell signals are generated when it closes lower, providing users with an easy-to-understand interface. The script overlays on the price chart and includes input parameters for customization.

    2. VWAP Cross Strategy
        - Description: The VWAP Cross Strategy is an institutional trading technique that centers on the relationship between the price and the Volume Weighted Average Price (VWAP) line. The strategy signals a buy when the price crosses the VWAP line from below, and conversely, it indicates a sell when the price crosses from above, which is particularly relevant for intraday traders. The script overlays the VWAP line directly on the price chart, offering customization options for color and line width.

### Retail Strategies <a name="retail"></a>

    1. Daily High Low Strategy

        - Description: The Daily High Low Strategy is a retail trading approach that offers visual guidance for potential supply and demand zones in the market. By marking the highest and lowest price levels from the previous day on the chart, traders can identify possible order blocks based on historical price data. This straightforward approach helps traders anticipate potential reversals or breakouts.

    2. Intraday High & Low Strategy

        - Description: The Intraday High & Low Strategy aids traders in identifying and plotting the highest and lowest prices during a trading day as potential areas of supply and demand. Green and red lines represent these levels on the chart, adjusting in real-time as the trading day unfolds and new highs or lows are reached. This strategy gives traders an ongoing perspective on intraday price action and potential pivot points.

    3. RSI Divergence Strategy

        - Description: The RSI Divergence Strategy is a unique approach that detects and plots divergences between price and the Relative Strength Index (RSI), signaling potential trend reversals. It identifies when the price and RSI are out of sync – a key indication of a possible shift in market sentiment. The strategy offers adjustable parameters, allowing optimization for various instruments and timeframes, making it versatile across different trading scenarios.

    4. Simple Moving Average Crossover (SMAC)

        - Description: The Simple Moving Average Crossover (SMAC) is a strategy that leverages the relationship between a short-term and a long-term simple moving average (SMA) to generate trading signals. The strategy signals a buy when the short-term SMA crosses above the long-term SMA, and it signals a sell when the short-term SMA crosses below the long-term SMA. This trend-following approach is designed to capture significant market moves and to aid in filtering out market noise.

---

## Disclaimer <a name="disclaimer"></a>

Trading financial instruments carries inherent risks, and past performance is not indicative of future results. The strategies and indicators provided in this repository are for educational purposes only and should not be considered as financial advice. Always perform your own research and analysis, and consult a financial professional before making any trading decisions.

---

## Credits <a name="credits"></a>

Special thanks to the open-source community for providing the inspiration and resources that contributed to the creation of these scripts. The continuous exchange of knowledge and support is invaluable and greatly appreciated.

Additionally, the process of learning and implementing Pine Script for TradingView has been an enriching experience. Thank you to TradingView for the comprehensive documentation and user-friendly interface that made this project possible.

---

## Contact Information <a name="contact-information"></a>

For any questions or concerns, you can reach out to me through the following methods:

- Email: dalronj.robertson@gmail.com
- LinkedIn: [Dalron J. Robertson](https://www.linkedin.com/in/dalronjrobertson/)
- YouTube: [AGNDJ](https://youtube.com/@AGNDJ)
- Website: [dalronjrobertson.com](https://dalronjrobertson.com)

I'm always open to feedback, collaboration, or simply a chat. Feel free to get in touch!
