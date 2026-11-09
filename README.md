# Project Case Study: Amina Boutique Sales Performance Dashboard

## Executive Summary
This project delivers an end-to-end data solution for Amina Boutique, a premium retail fashion business specializing in traditional and contemporary African apparel, accessories, and footwear. The primary purpose of this project is to bridge the gap between raw, daily transaction logs and strategic business growth. By transforming unorganized sales data into an interactive dashboard, this analysis uncovers critical operational patterns such as a steep mid-year revenue drop and a high reliance on anonymous shoppers. Ultimately, this dashboard provides the boutique owner with the exact visual insights needed to optimize inventory, run targeted marketing campaigns, and reverse seasonal sales slumps.

## Problem Statement
*   **Situation:** Amina Boutique tracks daily transactions including product names (Ankara Skirts, Blazers, Jumpsuits), unit prices, payment types, and customer profiles.
*   **Complication:** Sales figures are kept in unorganized logs, making it hard to see macro trends. The boutique owner cannot easily identify who their highest value customers are, which products drive volume versus revenue, or when seasonal slumps happen.
*   **Question:** How can the boutique establish a reliable, systematic process to accurately track daily sales, monitor varied payment methods, capture anonymous customer profiles, and turn raw boutique logs into long-term business intelligence?

## Tools Used
This project was built 100% end-to-end using Microsoft Power BI:
*   **Power Query:** Used to import transaction logs, clean up column types, remove duplicates and ensure data consistency across multiple retail product categories.
*   **DAX (Data Analysis Expressions):** Wrote custom formulas to calculate core business metrics shown in the top KPI cards, including Total Sales (₦4M), Units Sold (312), Number of Customers (11), Total Orders (8), and Average Order Value (₦558K).
*   **Data Visualization & UI Design:** Designed a cohesive, boutique-themed user interface featuring interactive bar charts, line graphs, donut charts, and an incorporated product image. Added global category buttons at the top right to filter the entire report with one click.

## How the Dashboard Works
1.  **KPI Cards:** Gives the boutique owner an instant snapshot of overall business health.
2.  **Product Slicers:** Allows users to filter the charts dynamically by specific items like Ankara Skirts, Heels, or Kaftans.
3.  **Visualization:** Breaks down sales volume by product, revenue by category, payment types, and top buyers to give a complete 360-degree view of retail performance.
   <img width="1256" height="765" alt="Screenshot 2026-11-09 120923" src="https://github.com/user-attachments/assets/ac16db60-1681-4abd-bb12-e1f8a7b4dc36" />

## Key Findings
*  Ankara Skirts and Headwraps drive the highest unit sales volumes (quantity sold). However, higher-priced premium items like Jumpsuits, Heels, and Blazers generate the core revenue for the business.
* The single largest customer segment driving revenue is anonymous Walk-In buyers, outperforming named loyal customers like Fatima B. and Grace T.
*  Customers use a relatively even mix of payment channels, split between Cash (35%), POS (36%), and Bank Transfers (30%).
*  Sales climb steadily through the first half of the year, peaking dramatically in June, before experiencing a massive crash throughout July and August.

##  Recommendations
1.  **Launch a Customer Loyalty Program:** Create targeted perks and rewards for top-listed buyers (Fatima B., Grace T.) to secure and protect core recurring revenue.
2.  **Capture Walk-In Data:** Mandate retail staff to collect basic contact details (phone/email) from anonymous Walk-In customers to turn random shoppers into trackable digital profiles for marketing.
3.  **Bridge the Seasonal Revenue Gap:** Launch a dedicated end-of-season clearance sale or mid-year promotion in July and August to combat the steep seasonal revenue crash.
