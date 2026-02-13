# E-Commerce Sales Funnel & Conversion Optimization Analysis
A Data-Driven Optimization Project using MySQL

## 📖 Project Overview
This project focuses on analyzing the customer journey of an e-commerce platform using a dataset of 9K+ user events. The goal was to identify where users drop off in the sales funnel, evaluate the effectiveness of different marketing channels, and provide actionable recommendations to improve conversion rates and revenue.

## Visuals
<img width="850" height="400" alt="image" src="https://github.com/user-attachments/assets/1194f31f-8510-4ead-9366-e11555505030" />

## 🛠️ Data Schema
The analysis utilizes a single core table: user_events.
<img width="830" height="340" alt="image" src="https://github.com/user-attachments/assets/04f16363-5957-4ea2-a2a8-aac61be74293" />

## 🔬 Technical Insights (SQL Results)
Based on a 30-day analysis of the dataset, the following performance benchmarks were established:

* **Funnel Conversion**: The site attracted 2,904 unique visitors, resulting in 466 successful purchases, reflecting an overall conversion rate of 16%.

* **Checkout Efficiency**: Once a user starts the checkout process, there is a 73% conversion rate to final purchase (640 checkouts vs. 466 purchases).

* **Channel Performance**: Email is the most efficient channel with a 34% purchase conversion rate.

* Social Media drives high traffic (860 views) but converts at the lowest rate of 6%.

* **Customer Velocity**: Converted users complete their journey from initial view to purchase in an average of 24.42 minutes.

* **Financials**: The Average Order Value (AOV) is $106.05, with a Revenue Per Visitor (RPV) of $17.02.

## 💡 Strategic Recommendations
**1. UX & Website Optimization**
  - **Preserve the Checkout Flow**: The conversion rate from Checkout Start to Purchase is excellent at 73%. This indicates the technical payment flow is frictionless and highly optimized.

  - **Action**: Do not redesign the checkout or payment pages at this time. Focus resources on top-of-funnel engagement where the drop-off is highest (Page View to Cart).

**2. Marketing Strategy**
  - **Optimize Social Spend**: Social Media drives ~30% of traffic but suffers from the lowest efficiency (6% conversion). This suggests we are paying for "window shoppers" rather than high-intent buyers.

  - **Action**: Shift social budget from broad "Traffic" objectives to "Retargeting" campaigns. Implement email capture popups for social visitors to move them into the higher-converting Email channel.

  - **Double Down on Email**: With a 34% conversion rate, Email is the highest-performing channel.

  - **Action**: Prioritize list-building and automated "Abandoned Cart" email sequences to capitalize on this high-intent segment.

**3. Financial & Revenue Management**
  - **CAC Thresholds**: With an AOV of $106.05, the business has a clear benchmark for profitability.

  - **Action**: Set a strict Customer Acquisition Cost (CAC) limit of $30–$40. Any channel (like Social) exceeding this acquisition cost is likely resulting in a net loss per transaction.

## ⚙️ How to Reproduce
To run this analysis on your local machine:

- **Clone the Repo**: git clone https://github.com/Aiswarya196/ecommerce-sales-funnel-analysis.git

- **Setup Database**: Create a MySQL database and import the provided user_events.csv file using the MySQL Table Data Import Wizard.

- **Run Queries**:
    Open the /sql_queries folder and execute the scripts in order (Funnel Analysis → Source Analysis → Time Analysis).
