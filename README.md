# Marketing Funnel & Conversion Performance Analysis

## Project Overview
This project is part of my **Data Science & Analytics Internship** at **Future Interns**. The objective was to analyze the direct marketing campaign data of a banking institution to understand the customer journey from initial outbound contact to successful term deposit subscription. The analysis identifies key behavioral drivers, statistical significance of demographic features, and operational inefficiencies in the sales funnel.

## Key Insights
* **Conversion Rate:** The overall subscription rate is **11.7%**, reflecting a significant class imbalance that requires highly targeted marketing to maintain ROI.
* **Duration as a Proxy for Interest:** Call duration is the single strongest predictor of success; calls exceeding 5 minutes convert at **4–5x the baseline rate**, while calls over 10 minutes reach a **44% success rate**.
* **Diminishing Returns:** Marketing efficiency collapses after the **3rd or 4th contact attempt**. Over-contacting leads beyond this point results in increased operational costs with negligible conversion gains.
* **Segment Opportunities:** While the highest contact volume targets middle-aged professionals, the highest conversion rates are found in the **Student (28.7%)** and **Retired (22.8%)** demographics.
* **Seasonal Paradox:** High-conversion months like **March, September, and December** currently receive the lowest contact volumes, while the high-volume month of May shows the lowest efficiency.
* **The Engagement Threshold:** Only **30.2% of contacts** reach the "Engaged Lead" stage (>3 min duration). However, once engaged, the probability of subscription jumps to **38.8%**.

## Recommendations
* **Prioritize "Warm" Leads:** Automate priority routing for clients with a successful previous campaign history, as they exhibit a **64.7% re-subscription rate**.
* **Implement a "Three-Strike" Cap:** Limit campaign contacts to 4 attempts per lead to reduce fatigue and reallocate resources toward higher-quality initial outreach.
* **Optimize Seasonal Staffing:** Aggressively scale call volumes during **March, September, and October** to capitalize on naturally higher consumer intent during these periods.
* **Train for Engagement Duration:** Shift sales KPIs from "call volume" to "engagement time." Training agents to cross the **180-second threshold** is critical to moving leads into the high-conversion funnel stage.
* **Tailored Messaging for Niche Segments:** Develop bespoke financial products and scripts for **students and retirees**, the two most responsive demographics currently underserved by volume.
* **Balance-Based Segmentation:** Target clients with higher account balances (>2,000 EUR) for premium offers, as ANOVA testing confirms a statistically significant link between liquidity and subscription intent.

## Tools Used
* **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scipy.stats)
* **Jupyter Notebook** for end-to-end Exploratory Data Analysis (EDA)
* **Power BI** for dashboard visualisations

## Deliverables
* Cleaned and pre-processed marketing dataset (`bank-final.csv`).
* Comprehensive EDA notebook featuring distribution analysis, correlation matrices, and seasonality deep-dives.
* Actionable business recommendations for campaign optimization.

## Power BI Dashboard
Link to visualizations, funnel insights, and campaign performance dashboard: [https://app.powerbi.com/view?r=eyJrIjoiZWE3YjA4YmQtMWZhZC00OTdjLTllOTItNTg0NDZkOGI5YzQ3IiwidCI6IjRiMWI5MDhjLTU1ODItNDM3Ny1iYTA3LWEzNmQ2NWUzNDkzNCIsImMiOjh9]

## Visualizations & Analysis
The project includes deep-dives into:
1. **Marketing Funnel:** Tracking the transition from Total Contacts → Engaged Leads → Subscriptions.
2. **Feature Importance:** Using ANOVA and Chi-Square tests to validate drivers of conversion.
3. **Behavioral Trends:** Analyzing diminishing returns of call frequency and the impact of call duration.
