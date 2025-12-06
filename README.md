# US Bank Failures Analysis (2000 - 2025)
## Project Overview
This Power BI project analyzes 25 years of US banking history to identify trends, volatility, and economic recovery periods. It compares major financial events, specifically contrasting the **2008 Financial Crisis** with the recent **COVID-19 Pandemic era**.

## Key Technical Features
*   **Real-Time Data (Direct Query):** Connected directly to the live FDIC government database instead of using static Excel/CSV files.
*   **Star Schema Modeling:** Optimized data model with a custom Date Table for precise analysis (Quarter/Year/Decade).
*   **Time Travel Animation:** Integrated a "Play Axis" to visualize the history of bank failures year-by-year automatically.
*   **Scenario Switching:** Used advanced bookmarks to instantly toggle between "Pre-2008 Crisis," "Post-2008 Recovery," and "COVID Years."

## Key Insights
*   **The "Aftershock" (2010):** While the crisis started in 2008, the peak volatility hit in **2010**, resulting in **157 bank failures** in a single year.
*   **Pandemic Resilience (2020-2023):** The banking sector was much better prepared for COVID-19.
    *   Total failures (2020-2023): Only **9**.
    *   Failures in 2021 & 2022: **0**.
 
## How to View
1.  Open the `.pbix` file in **Microsoft Power BI Desktop**.
2.  Click the **"Play"** button on the timeline to watch trends evolve.
3.  Use the navigation buttons to filter by specific historical eras.
