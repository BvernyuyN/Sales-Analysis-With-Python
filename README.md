# Sales-Analysis Project
The Sales Analysis Project is a comprehensive data analytics endeavor aimed at understanding and optimizing the sales performance of a business. By harnessing the power of data, this project provides actionable insights into various aspects of sales, including the best-performing months, top-selling products, geographical sales distribution, and customer behavior.

Key objectives of the project include:

1. Identifying the Best Sales Month: Determining which month witnessed the highest sales and calculating the revenue generated during that period. This insight aids in tailoring marketing and sales strategies for peak performance.

2. Analyzing Regional Sales: Uncovering which cities are the most significant contributors to product sales, thereby assisting in targeted regional marketing efforts.

3. Optimal Advertising Timing: Pinpointing the ideal time to display advertisements to maximize the likelihood of customers making purchases.

4. Recognizing Frequently Sold-Together Products: Discovering which products are commonly purchased together can lead to cross-selling opportunities and improved inventory management.

5. Identifying Top-Selling Products: Highlighting the product that dominates sales, allowing for focused promotion and sales expansion.
   
**Columns in the Dataset:**

The columns used for analysis in the dataset include:

- **Order ID:** A unique identifier for each order.
- **Product:** The name of the product sold.
- **Quantity Ordered:** The quantity of the product ordered in each transaction.
- **Price Each:** The price of each product.
- **Order Date:** The date and time when the order was placed.
- **Purchase Address:** The address where the order was shipped.
- **Month:** Extracted from the order date to identify the month of each transaction.
- **Sales:** Calculated as the product of the quantity ordered and the price each.

**Step 1 Data collection:**
Monthly sales data that spand a period of 12 months was downloaded from [Dataset](https://drive.google.com/drive/folders/1RZsJUDSCs6FR51qhPfbPdqORwSKhQMgX?usp=drive_link)  this data was merge to a single csv file and named yearly_sales_data.csv this new datase was renamed as df and loaded using pandas  pd.read_csv () function 

**Step 2 Data verification :**
To verify the readiness of this dataset for analysis, the .head(), .shape, .info(), .isna() methods were used to verify by check the head, shape, info, and missing values

**Step 3 Data cleaning:**
Missing values were dropped, and additional columns like 'Month,' 'Sales,' 'City,' 'Hour,' 'Minute,' and 'Count' were added to the dataset.

**Step 4 Exploratory Data Analysis:**
Various questions aimed at achieving the project's objectives were answered and visualized using horizontal and vertical bar charts, line graphs, and Matplotlib. Functions like groupby, sum, max, and idxmax were commonly used.
For more detailed insights and the complete analysis, please refer to the detailed notebook in my [GitHub repository](https://github.com/BvernyuyN/sales-analysis-/blob/main/sales_analysis.ipynb).


**Findings insights and posible recommendations**

In this analysis, we have uncovered several key findings that provide valuable insights into the company's sales and customer behavior. These findings shed light on the company's performance, consumer preferences, and potential areas for optimization. Let's delve into each of these findings to gain a deeper understanding of their implications and how they can influence the company's business strategies.

1. **Best Month for Sales (December):**
    December stands out as the best month for sales, generating $4.6 million in revenue.
   
   <img width="400" alt="monthsale" src="https://github.com/BvernyuyN/sales-analysis-/assets/149203833/afe4396f-b500-465f-a813-96875b50ec3e">

The discovery that December is the best month for sales, generating $4.6 million in revenue, carries significant implications for business operations and strategies:

**Seasonal Sales Opportunities:**
1. **Capitalizing on Seasonal Trends:** December is traditionally a high-sales month due to the holiday season. Businesses should leverage this period to maximize sales and revenue. This might involve creating special promotions or holiday-themed marketing campaigns.

**Inventory Planning:**
1. **Inventory Management:** Recognizing the increased demand in December, businesses should ensure they have sufficient stock of popular products to meet customer needs. It's crucial to maintain an optimal balance to prevent overstock or understock situations.

**Marketing Strategies:**
1. **Tailored Campaigns:** Design marketing campaigns and advertising strategies that are specific to the holiday season. This might include themed ads, holiday discounts, and promotions.

**Revenue Projections:**
1. **Financial Planning:** Understanding that December generates the highest revenue allows for better financial forecasting and budgeting. Businesses can allocate resources effectively and plan for expansion, if necessary.

**Customer Engagement:**
1. **Customer Loyalty Programs:** December provides an opportunity to implement loyalty programs or incentives to attract and retain customers during the holiday season and beyond.

**Seasonal Variations:**
1. **Sales Variability:** Assess the reasons behind December's peak sales. Is it due to holiday gifts, end-of-year purchases, or other factors? Understanding the sales patterns can help in identifying areas to focus on during other times of the year.

**Recommendations:**

1. **Holiday Promotions:** Create targeted holiday promotions, discounts, and bundles to attract shoppers during the holiday season.

2. **Supply Chain Management:** Streamline supply chain and inventory management to ensure product availability and quick restocking.

3. **Advertising:** Allocate a larger share of the advertising budget to holiday campaigns. Leverage social media, email marketing, and online advertising for maximum reach.

4. **Customer Engagement:** Implement loyalty programs and customer engagement initiatives to foster long-term relationships with holiday shoppers.

5. **Sales Analytics:** Continuously monitor and analyze sales data during the holiday season to identify trends and adjust strategies as needed.

By recognizing the significance of December as the best sales month, the business can strategically position itself to capture the increased demand, boost revenue, and provide customers with a rewarding holiday shopping experience.


2. **City with Highest Product Sales (San Francisco):**
San Francisco emerges as the city with the highest product sales, totaling 50,239 products sold.

<img width="295" alt="city" src="https://github.com/BvernyuyN/sales-analysis-/assets/149203833/5cbbfa78-aa18-48cb-ac77-b223bc3f3139">  

The finding that the city with the highest product sales is San Francisco, with a total of 50,239 products sold, provides valuable insights that can be used to drive business growth and marketing strategies:

**Market Potential:**
1. **High Demand:** San Francisco has demonstrated a high demand for our products. This indicates the potential for growth in this market. Businesses should consider allocating more resources and marketing efforts to tap into this lucrative market.

**Customer Behavior:**
1. **Consumer Preferences:** Understanding the products that sell well in San Francisco is key to tailoring product offerings. Analyze which specific products are popular in this city and ensure their availability.

**Geographical Targeting:**
1. **Geographical Marketing:** Leverage this finding to create geo-targeted marketing campaigns. Tailor advertising and promotions specifically for San Francisco to maximize sales in this area.

**Store Location:**
1. **Physical Stores:** If the business has physical stores, consider opening or expanding stores in San Francisco. High product sales indicate the potential for increased foot traffic and in-store sales.

**Economic Analysis:**
1. **Economic Viability:** Investigate the economic factors that contribute to higher sales in San Francisco. Factors such as income levels, industry, and market trends may provide insights into the local market.

**Recommendations:**

1. **Marketing Investment:** Allocate a portion of the marketing budget to target San Francisco with tailored campaigns that highlight the products popular in this city.

2. **Inventory Management:** Ensure that there is an ample supply of the products that sell well in San Francisco to meet the high demand.

3. **Geographical Expansion:** Consider opening or expanding stores in San Francisco, if feasible and aligned with the business's growth strategy.

4. **Customer Insights:** Conduct surveys or gather data to understand the specific preferences and needs of customers in San Francisco to tailor product offerings further.

5. **Competitive Analysis:** Assess competitors in the San Francisco market and identify unique selling propositions that can be emphasized in marketing strategies.

By capitalizing on this finding, the business can maximize its sales potential in San Francisco, enhance customer satisfaction, and drive revenue growth in a location where there is already a strong demand for its products.



3. **Best Hours for Advertising (19:00):**
This finding highlights the importance of timing in capturing the attention of potential customers and maximizing the impact of marketing efforts.The best hours for advertising, as indicated by the graph, are around 19:00 (7:00 PM). 
    This findings regarding the best hours for advertising, with the peak at 19:00, as well as the effective advertising slots between 11:00-13:00 and 18:00-20:00, are significant insights that can be interpreted and rationalized as follows:

**Peak Advertising Hour - 19:00:**
1. **Consumer Engagement:** The hour of 19:00 (7:00 PM) appears to be the peak time for consumer engagement. This could be attributed to several factors, including people returning home from work, having leisure time, or seeking entertainment. At this hour, potential customers are more likely to pay attention to advertisements and make purchase decisions.

2. **Family and Leisure Time:** 19:00 often coincides with the evening hours when families and individuals unwind after a day's work. This is an opportune moment to reach a wide audience, as people gather for meals, relax, and engage in leisure activities. Targeting advertisements during this time can tap into this relaxed and receptive audience.

 <img width="267" alt="ad" src="https://github.com/BvernyuyN/sales-analysis-/assets/149203833/44914552-db40-4953-8e6c-8c8099c1ed0d">

**Effective Advertising Slots (11:00-13:00 and 18:00-20:00):**
1. **Lunchtime (11:00-13:00):**
   - During lunchtime, individuals often take breaks from work or daily routines. It's a convenient period for browsing or shopping online. Advertising between 11:00-13:00 can capture the attention of both office workers and individuals at home, making it an effective time to promote products or services.

2. **Evening Hours (18:00-20:00):**
   - The early evening hours are prime time for relaxation and leisure activities. Families gather for dinner, and individuals are likely to engage in online activities. Advertisements during this time can be effective, as consumers are open to exploring products or services, particularly if they align with their leisure and lifestyle needs.

**Possible Reasons for Effectiveness:**

- **Optimal Audience Availability:** Advertising during these hours takes advantage of the availability of the target audience. Consumers are more likely to be online and receptive to advertisements during moments of relaxation and convenience.

- **Behavioral Patterns:** These hours align with common behavioral patterns of consumers, such as meals, breaks, and leisure activities. Effective advertising slots consider these patterns to reach consumers when they are most receptive.

- **Promotions and Offers:** Businesses may run promotions, discounts, or special offers during these times to incentivize purchases. This can make advertisements more compelling and lead to increased conversions.

**Recommendations:**

1. **Targeted Campaigns:** Develop targeted advertising campaigns specifically for the peak hour at 19:00 and the effective slots between 11:00-13:00 and 18:00-20:00. Ensure that the content and messaging are aligned with the expectations and needs of consumers during these hours.

2. **Adaptive Marketing:** Use data analytics and customer insights to understand the preferences and behaviors of your target audience during these times. Tailor marketing strategies to address their specific interests and pain points.

3. **Ad Scheduling:** Leverage digital advertising platforms that allow precise scheduling to reach the audience at the right moment. Adjust ad budgets and bids to optimize ad placement during these peak and effective hours.

4. **A/B Testing:** Implement A/B testing to measure the performance of ads during these hours and refine strategies over time. Monitor key performance indicators (KPIs) such as click-through rates, conversions, and return on investment (ROI).

By capitalizing on these findings and recommendations, the business can enhance its advertising effectiveness during the identified peak and effective hours, leading to increased engagement and potentially higher sales.


4. **Frequently Purchased Product Combinations (iPhone and Lightning Charger Cable):**
The most frequently bought together products are the iPhone and Lightning Charger Cable, with a total count of 1,005. These combinations suggest a strong correlation between customers buying iPhones and the accompanying charger cables. The finding that the most frequently purchased product combination consists of iPhones and Lightning Charger Cables, with a total count of 1005 occurrences, is a valuable insight that can be explained and utilized for business improvement:

 <img width="384" alt="prod combo" src="https://github.com/BvernyuyN/sales-analysis-/assets/149203833/52ed50f3-9496-4414-85d1-a257f759a565">
 
**Consumer Preferences:**
1. **Apple Ecosystem:** Apple customers often seek to complete their Apple ecosystem. When customers purchase iPhones, they frequently need compatible accessories like Lightning Charger Cables. This combination is popular among Apple users as it ensures seamless connectivity and charging.

**Cross-Selling Opportunities:**
1. **Strategic Pairing:** Recognizing this common pairing, the business can strategically pair iPhones and Lightning Charger Cables as a bundle or offer them at a discounted price when purchased together. This encourages customers to buy both products simultaneously.

**Enhanced Customer Experience:**
1. **Convenience:** Providing frequently purchased product combinations as a package simplifies the buying process for customers. It offers convenience and ensures that customers have all they need to use their new iPhone right away.

**Sales Promotion:**
1. **Special Promotions:** The business can create marketing campaigns around these combinations, highlighting the benefits of purchasing both products together. Special promotions, such as "Buy an iPhone, Get a Lightning Charger Cable at Half Price," can attract customers.

**Recommendations:**

1. **Bundling Strategy:** Consider offering bundled deals for frequently purchased combinations. For instance, offer a discount when customers buy an iPhone along with a Lightning Charger Cable.

2. **Cross-Selling:** Implement cross-selling strategies that suggest complementary products during the checkout process. For customers adding an iPhone to their cart, recommend adding a Lightning Charger Cable.

3. **Marketing Campaigns:** Create marketing campaigns that promote the convenience and cost savings of purchasing these combinations. Highlight the seamless experience of owning both an iPhone and a Lightning Charger Cable.

4. **Inventory Management:** Ensure that there is sufficient stock of both iPhones and Lightning Charger Cables to meet the potential increase in demand when promoting these combinations.

By leveraging this finding, the business can enhance its sales and customer experience by offering tailored solutions that cater to the preferences of its customers. This not only drives more sales but also fosters customer satisfaction and loyalty.

5. **The Product sold most was AAA Batteries (4-pack):**
The finding that the highest-selling product was AAA Batteries (4-pack), with a total of 32,027 units sold, is a significant insight for the business. This discovery can be interpreted and rationalized in the following manner:

<img width="295" alt="hihest goods sold" src="https://github.com/BvernyuyN/sales-analysis-/assets/149203833/183f3b18-65d6-4ae3-9e8c-dd2bdeff9549">

**Customer Demand and Necessity:**
   - AAA batteries are a common necessity in households. They power a wide range of devices, from remote controls to children's toys and small electronics. Customers often buy these batteries in bulk to ensure they have an adequate supply at home. The high sales volume of AAA batteries reflects their essential role in daily life.

**Frequent Replacement Item:**
   - AAA batteries are typically consumed quickly, especially in devices that are frequently used. Consumers regularly replace these batteries as they run out, resulting in a steady demand. This frequent replacement cycle can explain the substantial sales figures for AAA batteries.

**Affordability and Accessibility:**
   - AAA batteries are relatively inexpensive and widely available. Customers are more likely to make spontaneous purchases when the price point is low, and the product is easily accessible. This affordability and accessibility contribute to the high sales numbers.

**Cross-Category Relevance:**
   - AAA batteries are versatile and compatible with a variety of devices. This cross-category relevance means that customers from different demographics and with diverse needs purchase them. Whether for household electronics, children's toys, or other gadgets, AAA batteries cater to a broad customer base.

**Seasonal and Promotional Factors:**
   - Seasonal factors, such as holiday gifting, can also drive sales of AAA batteries. For example, during the holiday season, gift recipients may receive battery-operated toys or gadgets that require AAA batteries. The company's promotions and marketing strategies may also influence sales, such as bundling AAA batteries with other products or offering discounts.

**Recommendations:**
   
To capitalize on the popularity of AAA batteries (4-pack) and further enhance sales, the business can consider the following recommendations:

1. **Promotional Bundles:** Create bundles that include AAA batteries along with other relevant products. For instance, bundle AAA batteries with remote controls, children's toys, or portable gadgets. This strategy can encourage customers to purchase complementary items.

2. **Subscription Services:** Offer subscription services for AAA battery delivery at regular intervals. Subscribers can receive batteries automatically, ensuring they never run out. This subscription model can build customer loyalty and generate recurring revenue.

3. **Seasonal Marketing:** Leverage the seasonal demand for AAA batteries by running targeted marketing campaigns during peak seasons when battery usage is high. Highlight the convenience of gifting battery-operated devices and include AAA batteries in holiday gift guides.

4. **Customer Education:** Provide tips and guides on battery maintenance and safe disposal. Educating customers about proper battery care can foster goodwill and repeat business.

By implementing these recommendations, the business can not only maintain its strong sales of AAA batteries but also create opportunities to cross-sell and enhance the overall customer experience.

**Conclusion**

These findings and recommendations provide a data-driven roadmap to enhance our sales, improve customer satisfaction, and streamline our operations. By aligning our strategies with these insights, we can drive growth, adapt to customer preferences, and remain competitive in the market.

The Sales Analysis Project demonstrates the power of data analytics in gaining a deeper understanding of our business's dynamics. As we continue to refine and implement these recommendations, we are poised for a brighter and more successful future in the world of sales.

For more detailed insights and the complete analysis, please refer to the detailed notebook in my [GitHub repository](https://github.com/BvernyuyN/sales-analysis-/blob/main/sales_analysis.ipynb).
















