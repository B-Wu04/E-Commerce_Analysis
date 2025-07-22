# E-Commerce_Analysis

## Project Background

An online retailer has been operating at a loss over the last year since their restructing their supply chain. The business is struggling to keep up with the incosistent pricing due to old promotions, coupons and online deals. I have been tasked to extract insights on revenue as well as provide recommendations on how to help linearise and consolidate their pricing to generate profits.

## Executive Summary

The business generated $42,495,704.81 in revenue between October 2023 and October 2024, however the total value of the goods sold was $47,229,907.98 resulting in a new loss of $4,734,203.17. On average each item was sold at 90% of its actual value, at its crux this is where all business should be targetting its focus to operate in the green. The largest category of sales came from electronics encompassing 35.9% of total revenue with the lowest being furniture encompassing 14.7%. In total, 1997 different products were sold to consumers and these products were purchased by the business from 100 different suppliers. The was no consistent category of products that were sold at a loss, at times the same product would be sold at a loss and at a profit to different customers. This calls for a drastic complete review of pricing policies, supplier agreements and discount structures.

## Insights and Analysis

### Monthly Trends
- The business averaged $3,507,040.49 in revenue and 1,652 orders each month.
- October generated the largest revenue and loss with a revenue-to-value ratio of 0.86%, a total of $616,860.83 in losses.
- The revenue growth fluctated between -7% and 10% growth rates, without any obvious signs of seasonality where December sales matching Feburary sales.
- Each month conistently saw electronics as the highest category of sales and furniture as the lowest.

![Monthly Metrics](Images/Monthly_Sales_Revenue_Compared_to_Goods_Value.png)
![monthly_growth_heatmap](Images/monthly_revenue_growth.png)
note: December 2023 growth is slightly inaccurate due to incomplete data for November 2023

### Distribution of Sales
- The ranking of sales amongst the four categories: Accessories, Electronics, Furniture and Home & Kitchen stayed consistent throughout the year.
- The growth of these categories between months were almost identical to each other. This indicates that the sales performance across categories is likely influenced by overarching seasonal trends or promotions, rather than category-specific factors.
- This consistency implies that products from different categories are likely serving distinct customer needs, with minimal overlap. In other words, they do not significantly cannibalise each other’s sales, which supports a diverse product strategy without risk of internal market dilution.

| Category | Revenue | % of Total Revenue |
| --- | --- | --- |
| Electronics | $15,247,167.14 | 0.36 |
| 	Home & Kitchen | $11,182,785.90 | 0.26 |
| Accessories | $9,833,968.69 | 0.23 |
| Furniture | $6,231,783.08 | 0.15 |

![monthly_categorical_sales](Images/monthly_categorical_sales.png)

- The distribution of the volume of each product being sold follows a normal distribution where the median is 45. This shows that the number of sales are being driven by a diverse catalouge of products with only a small number of outliers on either tail. These results can help us derive which products to potentially discontinue.
- The 20% cutoff of top sellers should be emphasised when considering any alterations of prices as they driving the highest customer engagement. These products produce the highest losses, amounting to $-3,719,297.66.
- 228 products contribute to the top 20% of overall sales by volume.

![distibution of sales](Images/product_profitability.png)

- The average product was sold at a loss of -$2370.66, the median loss was -$2228.28 out of all 1997 sold products.
- The highest loss was on the laptop sleeve, amounting to -$60,938.32. This is likely due to the high goods value of $611.11, where the supplier is selling to the business at obscenely high costs.
- The highest profit was on the rice cooker , amounting to $55,705.99.
- There was no consistent time or category amongst the extremities indicating that a thorough and product specific reconfiguration of pricing is necessary.

![product profitability](Images/Distribution_of_Sales.png)

### Performance by Supplier
- Mega Suppliers had the lowest average return on sale at -$300.79 per item. A total of 957 items from Mega Suppliers were sold at a loss amounting to -$287,856.44
- Notably, all 100 supplier had items that sold at a loss. On a positive note, each supplier also had items that sold at a profit.
- The highest profit was by Premier Logistics Inc. Their products made a total of 989 proitable sales, generating $229,196.98 in profit. Accounting for the unprofitable transactions, Premier Logistics Inc was still the highest overall profitable supplier with a total of $86,217.08 out of 1,978 sales.


