# US Bank Failures Analysis (2000 - 2025)
## Project Overview
This Power BI project analyzes 25 years of US banking history to identify trends, volatility, and economic recovery periods. It compares major financial events, specifically contrasting the **2008 Financial Crisis** with the recent **COVID-19 Pandemic era**.

## Power BI Report
#Clicking on the below report redirects you to Power BI Service
[![Power BI Report](https://github.com/user-attachments/assets/bccec3fc-b809-4c64-a1f4-1faf8ee27939)](https://app.powerbi.com/groups/me/reports/cd1f31a3-369c-41e6-b04d-0e2b2d931b6f/f1af04d677b60ec3de73?bookmarkGuid=d4475d55-f912-4587-b16d-a70c28e72674&bookmarkUsage=1&ctid=2daf3b8a-0cf2-4e49-890d-89086138c28f&portalSessionId=827fbf38-6eff-40f8-918d-141d300cc063&fromEntryPoint=export)

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
