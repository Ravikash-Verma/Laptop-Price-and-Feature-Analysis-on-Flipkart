# Laptop-Price-and-Feature-Analysis-on-Flipkart

Objective: Conducted a comprehensive analysis of laptop data from Flipkart to identify pricing trends, discount patterns, and brand performance.
ETL Process:
Extract: Retrieved data from Flipkart listings.
Transform:
Converted 'NIL' values to NaN and removed rows with missing values.
Extracted and standardized brand names from product titles.
Calculated discount percentages from actual and discounted prices.
Cleaned and converted review counts from string format to integers.
Load: Prepared cleaned data for analysis and visualization.
Data Visualization: Utilized Seaborn and Matplotlib to create visualizations, including histograms of actual and discounted prices, scatter plots of star ratings versus prices, and bar plots displaying average discounts, ratings, and reviews by brand.
Key Insights:
Discount Trends: Gigabyte offers the highest average discount, while Apple provides the least. Companies should consider adjusting discount strategies to remain competitive.
Brand Ratings: Thomson is the top-rated brand, and Apple is also well-regarded, whereas Ultimus has lower ratings. Brands with higher ratings could use this data to highlight their quality, while lower-rated brands might focus on improving product features or customer service.
Review Analysis: Realme and Primebook are the most reviewed brands, indicating high customer engagement. Companies with fewer reviews should enhance their marketing strategies to increase product visibility and customer feedback.
Correlation Analysis: Found a strong correlation between actual and discounted prices, with minimal impact of star ratings on pricing. Companies should leverage pricing strategies that align closely with actual product values to optimize discount effectiveness.
Processor Pricing: Intel Core i9 processors are the most expensive, while AMD Ryzen 3 processors are the least expensive. Companies could adjust their product offerings and pricing strategies based on processor popularity and market demand.
Recommendations for Companies:
Adjust Discounts: Implement competitive discount strategies similar to high-performing brands to attract more customers.
Enhance Product Quality and Service: Focus on improving product quality and customer service to boost brand ratings and customer satisfaction.
Increase Reviews and Visibility: Encourage more customer reviews and improve marketing efforts to enhance product visibility and consumer engagement.
Optimize Pricing: Align discount strategies with actual product value and market trends to maximize sales and profitability.
Tech Stack: Python, Pandas, Seaborn, Matplotlib.
