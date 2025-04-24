# stock_Market_Analysis

### Table of Contents:
- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [KPIs](#kpis)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis (Tableau Visuals)](#data-analysis-tableau-visuals)
- [Project Insights](#project-insights)
- [Recommendations](#recommendations)
- [How to Use This Report](#how-to-use-this-report)
- [Contact](#contact)

### Project Overview:
This project presents an interactive stock market analysis dashboard built in Tableau. It enables users to explore stock trends, volume changes, and volatility for top companies. Python was used for data processing and feature engineering.

### Business Objective:
Investors and analysts often struggle to identify real-time trends and volatility across multiple stocks. This dashboard solves that by providing a unified platform to compare price movements, volume shifts, and market sentiment indicators like z-score and Bollinger Bands, helping to make informed trading decisions.

### Data Source:
Format: CSV
Contains daily stock data for companies: Amazon, Apple, Facebook, Google, Microsoft, Nvidia, Netflix, Pepsi, Tesla, Twitter
Fields include: date, company, open, close, high, low, volume
[Amazon.csv](https://github.com/user-attachments/files/19888022/Amazon.csv), [Apple.csv](https://github.com/user-attachments/files/19888024/Apple.csv), [Facebook.csv](https://github.com/user-attachments/files/19888025/Facebook.csv), [Google.csv](https://github.com/user-attachments/files/19888015/Google.csv), [Microsoft.csv](https://github.com/user-attachments/files/19888016/Microsoft.csv), [Netflix.csv](https://github.com/user-attachments/files/19888019/Netflix.csv), [Nvidia.csv](https://github.com/user-attachments/files/19888023/Nvidia.csv), [Pepsi.csv](https://github.com/user-attachments/files/19888018/Pepsi.csv), [Tesla.csv](https://github.com/user-attachments/files/19888020/Tesla.csv), [Twitter.csv](https://github.com/user-attachments/files/19888021/Twitter.csv), 

### Tools Used:
  - Python: Data manipulation, feature creation (moving averages, z-score, volatility bands)
  - Tableau: Data visualization and dashboard creation

### Data Understanding:
  - **Daily Stock Metrics:** The dataset includes daily data points like Open, Close, High, Low, and Volume for each company.
  - **Multiple Companies:** Covers major stocks such as Amazon, Apple, Tesla, Microsoft, etc., enabling cross-company analysis.
  - **Date as Primary Dimension:** Time-series structure allows for trend and performance tracking over specific periods.
  - **Derived Fields:** Features like moving averages, price/volume changes, and z-score were computed to enhance insights.
  - **Focus Areas:** Emphasis on identifying patterns in price movement, volume fluctuations, and market volatility signals.

### KPIs:
  1. What was the closing price trend for each company?
  2. How did volume fluctuate over the selected time period?
  3. What was the highest and lowest price recorded?
  4. How does volume correlate with price movements?
  5. What was the total volume traded in the selected period?
  6. What’s the 20-day and 50-day moving average trend?
  7. Which companies are currently overbought or oversold?
  8. Are there sudden spikes or drops in z-score?
  9. What’s the comparison between actual price and Bollinger bands?
  10. Interactive Dashboard [View Dashboard](https://github.com/user-attachments/assets/b7586776-ae84-41c0-86d1-260a6c5fe91b)

### Data Cleaning:
Using Python:
  - Calculated 20-day & 50-day moving averages
  - Computed previous close, price change, % change
  - Added previous volume, volume change, and % volume change
  - Calculated z-score for overbought/oversold signals
  - Created upper and lower bands for volatility analysis
Exported final dataset to CSV for Tableau

### Exploratory Data Analysis:
  - Volume and Price Distribution: Analyzed how stock prices and trading volumes are distributed across time.
  - Company-Wise Analysis: Compared performance metrics such as average price and volume across different companies.
  - Outlier Detection: Identified abnormal values using z-score (>2 as overbought, <−2 as oversold).
  - Monthly Trends: Explored price and volume movements over each month to detect seasonal or cyclical patterns.
  - Volatility Patterns: Observed how certain stocks show consistent price swings, helping identify high-risk or high-reward opportunities.

### Data Analysis (Tableau Visuals):
  - Cards: Last day date, last volume, total volume, low, high
  - Filters: Start Date, End Date, Company
  - Table: Closing price, previous close, price change, % change, volume stats
  - Line Chart: Monthly trend with price (line) & volume (bar)
  - Line Chart: Volatility analysis with price, upper & lower bands
  - Line Chart: Z-score by month to identify market conditions

Snap of Stock Market Analysis

![Image](https://github.com/user-attachments/assets/b7586776-ae84-41c0-86d1-260a6c5fe91b)

### Project Insights:
  - **Z-Score for Market Sentiment:** Z-score visualization effectively identifies overbought and oversold conditions, aiding in the detection of potential reversal points.
  - **Volatility Tracking with Bollinger Bands:** Bollinger Bands provide a clear view of price volatility, helping users anticipate periods of expansion and contraction.
  - **Combined Signal Strength:** A z-score in the oversold range, coupled with the price touching the lower Bollinger Band, often indicates a potential upward movement.
  - **Volume as a Momentum Indicator:** Sudden spikes in trading volume typically signal strong market interest and can precede significant price actions.
  - **Bollinger Bands as Dynamic Support/Resistance:** The upper and lower bands frequently serve as dynamic support and resistance levels, assisting in trend reversal prediction and entry/exit decisions.

### Recommendations:
  - **Monitor High Z-Score Stocks:** Track companies with recurring z-scores above 2, as they may present short-term trading opportunities due to overbought conditions.
  - **Leverage Bollinger Band Breakouts:** Use price movements beyond the Bollinger Bands as potential signals for market entry or exit, especially when supported by volume trends.
  - **Analyze Volume Spikes for Market Moves:** Identify unusual volume increases, which can indicate institutional trading activity or upcoming market-moving events.
  - **Combine Technical Indicators:** Strengthen signal accuracy by integrating moving averages with z-score trends to confirm potential price reversals or continuations.
  - **Apply Support/Resistance Strategies:** Utilize Bollinger Bands and moving averages as dynamic support and resistance levels to improve trade timing and risk management.

### How to Use This Report:
  - **Launch the Tableau Dashboard:** Open the interactive dashboard to begin exploring stock market data and insights.
  - **Apply Filters for Custom Analysis:** Select your desired company and date range using the filter panel to tailor the visualizations to your needs.
  - **Review Summary Cards:** Quickly assess key metrics such as the latest trading date, last volume, total volume, high, and low prices.
  - **Examine Data Tables:** Analyze daily performance metrics including price change, % change, volume fluctuations, and their respective comparisons with previous values.
  - **Explore Interactive Charts:** Investigate trends in price and volume, track volatility through Bollinger Bands, and identify overbought/oversold zones using z-score analysis.
  - **Inform Strategic Decisions:** Use the insights gathered from the dashboard to support data-driven decisions in trading or investment strategies.

### Contact:
For further information or inquiries regarding this project, feel free to reach out:
  - Email     : pauljohnson2094@gmail.com
  - LinkedIn  : www.linkedin.com/in/pauljohnson2094
  - GitHub    : https://github.com/pauljohnson20
