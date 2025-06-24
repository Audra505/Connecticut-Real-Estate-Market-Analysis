## Connecticut Real Estate Market Analysis (2012–2022)

## 1.Project Overview
This project explores Connecticut’s real estate market from 2012 to 2022 through an interactive Power BI dashboard. With over 500,000 records, the report analyzes town-level sales trends, seasonal patterns, and pricing behavior to uncover how the market responded to economic booms, busts, and structural challenges.
Built to support analysts, investors, and policymakers, the dashboard answers key questions:
Which towns led the boom years, and when did slowdowns emerge?
How did seasonality impact pricing and transaction volume?
What patterns defined resilient or vulnerable towns over time?

**What I Did**:
Cleaned and transformed a large dataset into usable insights
Created dynamic DAX measures and visuals
Designed responsive visuals with drilldowns, filters, tooltips, and storytelling elements
Balanced technical complexity with accessibility for broad audiences

**Outcome**:
A clean, actionable dashboard that helps users navigate local housing trends, uncover hidden patterns, and make informed decisions.

![image](https://github.com/user-attachments/assets/33bdbc95-ff62-4e4a-80e1-0f22413f5a24)


## 2. Key Insights & Visuals
Below are screenshots from my presentation to provide insights on the project:


**Boom Years: Surging Demand & Buyer Confidence**
![image](https://github.com/user-attachments/assets/ea3b8527-b4c3-4c8a-af55-000edc376ded)

![image](https://github.com/user-attachments/assets/7b19d7cd-577a-48e7-a191-b726b7da1b82)

![image](https://github.com/user-attachments/assets/891f79da-50df-4c27-bfec-dc0276e36ae1)
Connecticut’s boom years 2013, 2015, 2020, and 2021 were marked by strong buyer confidence, low interest rates, and a drive for space and stability. From post-recession rebounds to the pandemic surge, suburban towns like Stamford, Greenwich, and Danbury consistently led the charge. Sales and transactions spiked, with single-family homes remaining the preferred choice. Together, these years revealed the market’s capacity for rapid growth when economic conditions align with evolving lifestyle needs.



**Bust Years: Corrections & Economic Pressure**
![image](https://github.com/user-attachments/assets/94e4ea4d-bc46-4434-b70f-fabef99f78c4)

![image](https://github.com/user-attachments/assets/549b09ea-975b-4925-bc8a-49a28af665f8)

![image](https://github.com/user-attachments/assets/5e32353f-483a-4b77-9296-d404546399b3)
Connecticut’s bust years 2016, 2018, and 2022 exposed the market’s limits amid economic pressure, rising rates, and affordability challenges. Each downturn revealed how even resilient towns falter when price growth outpaces income and inventory shrinks. Smaller towns like Plainville and Union were hit hardest, with months of little to no activity, exposing their fragility in a shifting market. While demand for housing remained, it couldn’t overcome structural constraints and shifting policies.These years show that sustained real estate growth depends not just on demand, but on access, affordability, and balanced supply.


**Seasonality & Pricing Trends**

![image](https://github.com/user-attachments/assets/b68433af-257f-473e-a562-d096bbe23128)

![image](https://github.com/user-attachments/assets/ae8f2639-fb39-4033-af23-0244eb1bd72e)

![image](https://github.com/user-attachments/assets/448d3d82-cbfc-473f-b2db-f0dc13ecb4a1)
Connecticut’s real estate market followed a strong seasonal pattern—surging in summer and slowing in winter with nearly one-third of sales occurring between May-August. Pandemic years amplified this trend, with towns like Stamford even recording December highs tied to luxury and relocation activity. By 2022, that momentum weakened summer peaks softened and smaller towns like Plainville and Union saw erratic or no activity. These shifts revealed how buyer behavior, affordability, and local market strength shape and disrupt seasonality over time.

## 3. Recommendations & Next Steps
After analyzing the dataset and creating the dashboard these are the following recommendations I would offer to help stakeholders, investors, and policymakers navigate changing conditions and support sustainable housing growth:
-1.Align Listings with Market Timing
Maximize exposure during peak summer months (May–August), while also leveraging strong December momentum in towns like Stamford and Greenwich to target luxury and year-end buyers.
-2.Prioritize Resilient Markets
Towns like Stamford and Waterbury thrived in both boom and bust periods. Focus investment, development, and retention efforts on these adaptable markets, and use them as models for identifying future high-performing areas.
-3.Track Buyer Shifts & Affordability Pressures
Post-2022 trends revealed more cautious and price-sensitive buyer behavior. Monitor affordability constraints, especially in towns with stagnating sales, and support access through programs like down payment assistance, zoning reform, and smart-density initiatives.
-4.Address Inventory Shortages Through Policy Innovation
Encourage supply growth through targeted zoning adjustments and public-private partnerships particularly for first-time buyers and the middle-market segment to prevent long-term affordability erosion.
-5.Leverage Real-Time Monitoring for Market Agility
Interactive dashboards like this project can help track key metrics such as transaction velocity, seasonal shifts, and luxury market trends equipping decision-makers with timely, actionable insights during both stable and uncertain periods.

![image](https://github.com/user-attachments/assets/3db1ac70-ed54-4402-87bb-78216708b1ab)
*screenshot from presentation*

## 4. Metrics, Modeling and Challenges
Several key components were developed to transform the real estate dataset into an interactive and insightful dashboard. This section outlines the core performance metrics, data modeling choices, and the challenges tackled along the way.

**Key Metrics & KPIs**
I used custom DAX measures to track performance across time and town, including:
Total Sales
Total Transactions
% Year-over-Year (YoY) Sales
% Month-over-Month (MoM) Transactions
Average Sale Price
Average Sales Ratio

Each metric was designed to update dynamically based on filters, allowing users to explore trends by town, year, or property type, etc.

![image](https://github.com/user-attachments/assets/2da51a49-72f0-4bb6-bba3-ebc3bcee7187)

**Data Model Overview &  Data Dictionary**
A star schema was designed to improve report performance and flexibility. Key relationships were built between calendar(look up table), and cleaned dataset(fact table) to allow time intelligence and spatial filtering. Field Parameter and Measure tables were created as will to uncover more insights and allow toggling field features for viewers. Data Dictionary can also be accessed within the report, through specific measures seen in the screenshot as well 
![image](https://github.com/user-attachments/assets/a9a77447-472d-4097-9aeb-b5c006ecd4f1)











