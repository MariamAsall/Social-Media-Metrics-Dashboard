# Social Media Metrics Dashboard in Excel

## Overview

This repository contains a dynamic and comprehensive Social Media Metrics Dashboard built entirely within Microsoft Excel[1][2]. It's designed to track and analyze key performance indicators (KPIs) across multiple social platforms—Facebook, Instagram, LinkedIn, and X (Twitter)—providing a centralized view of marketing performance[4][3]. The dashboard visualizes weekly trends and aggregates key metrics to help marketing teams make informed, data-driven decisions[5].

---

## Dashboard Preview

![final](https://github.com/user-attachments/assets/e4e9375f-d3fe-4edb-939d-bdb2a2ce3e70)


---

## Key Features & KPIs Tracked

This dashboard provides a holistic view of social media activity, focusing on industry-standard metrics[5][6]:

-   **Cross-Platform Tracking:** Monitors performance across Facebook, Instagram, LinkedIn, and X, with a combined total impressions count of **2.34 million**.
-   **Time-Series Analysis:** A primary line chart visualizes weekly impressions for all platforms over a 52-week period, making it easy to spot trends and compare channel performance.
-   **Platform-Specific KPI Cards:** Each platform has a dedicated card summarizing key metrics, including:
    -   **Impressions:** Total times content is displayed.
    -   **Fans & Audience Growth:** Tracks follower count and the rate of new fans.
    -   **Post Reach:** The number of unique users who saw the content.
    -   **Likes:** A primary measure of content approval.
    -   **Average Engagement Rate:** The percentage of the audience interacting with content.
    -   **Average Response Rate:** The efficiency in responding to audience interactions.
-   **Weekly Audience Growth Visuals:** Individual bar charts for each platform show the week-over-week growth in audience size, helping to identify successful campaigns or content.

---

## Technical Workflow

This dashboard was built entirely in Microsoft Excel, leveraging its powerful data analysis features without the need for external tools.

1.  **Data Source:** The analysis is based on the raw data in the `Data` sheet of the `Social-Media-Metrics-solved.xlsx` file, which contains weekly performance metrics for each social channel.
2.  **Data Aggregation with Pivot Tables:** The core of the analysis is driven by **Pivot Tables** (found in the `pivotT` sheet). These tables aggregate the raw weekly data to calculate summary statistics, such as total audience growth and weekly impressions per platform.
3.  **Dynamic Charting:** All charts on the main dashboard are dynamically linked to the Pivot Tables. This ensures that if the raw data is updated, the dashboard visualizations will refresh automatically.
4.  **Dashboard Design:** The final visuals are organized on a dedicated `DashBoard` sheet, creating a clean, user-friendly interface for stakeholders to easily interpret the data.

---

## Tools and Technologies

-   **Microsoft Excel:** Used for all stages of the project.
-   **Excel Features:**
    -   Pivot Tables
    -   Dynamic Charts
    -   Formulas for KPI calculations
    -   Dashboard design and layout

---
