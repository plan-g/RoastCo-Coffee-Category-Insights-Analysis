# RoastCo Coffee Category Insights Analysis

RoastCo, a prominent Canadian coffee company, presents a practical business intelligence challenge centered on point-of-sale data analysis. Working within the Brand Insights team, I investigate the key factors behind coffee category expansion and examine how pricing strategies, promotional campaigns, shelf positioning, and product variety work together to influence overall market performance

## Business Context

RoastCo competes in both premium and mainstream formats across major retailers. With promotional pressure, changing consumer habits, and growing competition from pods and private label, understanding sales levers at the SKU level is essential.

## Key Questions
- Which coffee formats and price bands drive consistent revenue?
- What promotion types deliver the highest ROI?
- How does shelf share affect performance across regions and retailers?
- Which SKUs should be prioritised, watched, or dropped?
- Can we predict future demand for better promo planning?

## Dataset Overview
- Synthetic weekly POS data (2022–2024), ~65,000 rows
- Retailers: Loblaws, Sobeys, Metro, Walmart, Costco
- Regions: All major Canadian zones
- Fields: base_price, promo_type, shelf_share, comp_price_index, revenue, units_sold, category, format

## Analytical Methods
- Cleaning and feature engineering in Python
- Clustering for SKU segmentation
- Classification model to identify high-performing SKUs
- Regression to forecast sales volume
- SQL logic to mirror validation steps
- Excel workbook with MoM and YoY checks

## Key Insights (Expected)
- Pods show high price sensitivity above $14.99
- Display and BOGO promos deliver >35% unit lift
- SKUs with shelf share <20% underperform across all formats
- Regression and clustering identify optimisable subsegments

## Files Included
- `coffee_roastco_dataset_2022_2024.csv` – raw dataset
- `coffee_roastco_insights_notebook.ipynb` – modelling + visualisation
- `coffee_roastco_validation.xlsx` – validation workbook
- `coffee_roastco_insights.sql` – SQL query companion

## Tools Used
Python, pandas, scikit-learn, SQL, Excel
