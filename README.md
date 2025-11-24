📊 Tesla Stock Analysis (2010–2025) — Power BI Dashboard

This project provides a beginner-friendly analysis of Tesla (TSLA) stock performance using Power BI.
It highlights long-term price trends, volatility patterns, and trading activity from 2010 to 2025.

🖼️ Dashboard Preview

![Dashboard](tesla_dashboard.png)

✨ Key Features

📈 Closing Price Trend (Area Chart)

📉 Daily % Change / Volatility

📊 Trading Volume Over Time

🗓️ Monthly Performance Chart

🎯 KPI Cards

Latest Close Price

Latest Daily % Change

All-Time High

Total Trading Volume

🔍 Interactive Slicers — Year, Month, Day

📂 Dataset Description

Columns used in this analysis:

Date

Open

High

Low

Close

Adj Close

Daily Change

Daily % Change

Volume

Year

Month

Month Name

🧮 DAX Measures Used
Latest Close Price =
VAR d = MAX(tsla_2025[Date])
RETURN CALCULATE(MAX(tsla_2025[Close]), tsla_2025[Date] = d)

All-Time High =
MAX(tsla_2025[Close])

Total Trading Volume =
SUM(tsla_2025[Volume])

📌 Key Insights

2025 shows strong closing price trends compared to previous years.

2020 recorded the highest trading volume, indicating strong market activity.

Tesla displays high day-to-day volatility, reflecting rapid price fluctuations.

🛠️ Tools Used

Power BI Desktop

Power Query

DAX
