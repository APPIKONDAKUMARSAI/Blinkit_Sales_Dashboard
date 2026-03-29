# Blinkit Sales Dashboard 

1. Project Title:
     Blinkit Sales Dashboard
  
2. Short Description
This project analyzes Blinkit’s retail performance data to uncover insights about sales trends, outlet performance, product categories, and customer preferences. The interactive dashboard provides a 360° view of business health, helping stakeholders make smarter, data-driven decisions.
From total sales and ratings to outlet tiers and fat content preferences, this dashboard transforms raw retail data into actionable business intelligence.

3. Tech Stack<br>
Power BI – Data visualization and reporting<br>
DAX – For calculated columns and measures<br>
Power Query  – Data transformation<br>
Excel/CSV  – Data source files

4. Data Source
<br>Source : https://www.kaggle.com/datasets/arunkumaroraon/blinkit-grocery-dataset
<br>Data categories likely include:
<br>Item Fat Content,	Item Identifier,	Item Type,	Outlet Establishment Year,	Outlet Identifier,	Outlet Location Type,	Outlet Size,	Outlet Type,	Item Visibility,	Item Weight,	Total Sales, Rating



5.   Features / Highlights<br>
KPI cards showcasing Total Sales, Revenue, and Growth
<br>Trend analysis over time (monthly/quarterly sales)
<br>Product-wise and region-wise performance comparison
<br>Interactive slicers and filters (e.g., outlet size, outlet type, outlet location type)
<br>Visual breakdowns like bar charts, line charts, and pie charts
<br>Clean, user-friendly interface for stakeholder presentations

6. Screenshot:<br>
Here's how the dashboard looks: https://github.com/APPIKONDAKUMARSAI/Blinkit_Sales_Dashboard/blob/main/blink.png
--------------------------------------------------------------------------------------------------------------------------
Insights from Blinkit Data Analysis using python
1. Data Overview
Dataset contains product, outlet, pricing, and sales-related features.
No duplicate records found.
Missing values were identified in columns like item weight and outlet size and handled appropriately.
2. Missing Value Handling
Missing values were cleaned to ensure consistency.
This step improved reliability of further analysis.

Clean data ensured accurate aggregation and comparison across products and outlets.

3. Fat Content Analysis
Low-fat products generated higher overall sales compared to regular items.

Customers show stronger preference toward low-fat products → demand is health-influenced.

4. Outlet Establishment Year Analysis
Highest sales observed for outlets established in 1998.
Followed by 2017 and 2010.
Lowest sales observed in 2011.


Older outlets tend to perform better → likely due to brand trust and customer base.

5. Product Performance (Business Requirement 1)
Identified high-sales vs low-sales items.
Dead inventory detected (low sales despite availability).



High-performing items → should be promoted
Low-performing items → reposition or reduce stock
Dead inventory → inefficient resource usage
6. Dead Inventory Analysis
Products with low sales despite visibility identified.


Stock is not aligned with demand → leads to wastage and reduced efficiency.

7. Low-Sales Item Detection
Certain products consistently show low sales.


These items may require:

pricing changes
better placement
or removal
8. Outlet Performance (Business Requirement 2)
Sales compared across outlet types, sizes, and location tiers.



Not all outlets perform equally
Performance depends more on location and demand than size
9. Fat Content vs Outlet Sales
Sales distribution varies across outlet types based on fat content.


Certain outlets perform better with specific product types → demand segmentation exists

   


