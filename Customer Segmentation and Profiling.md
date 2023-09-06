# CUSTOMER SEGMENTATION AND PROFILING
<p align="center">
<img src="https://github.com/Hoaithomint/Power-BI/assets/141213880/713cd937-3ba5-401d-b318-d8f4ea2a5758" alt="Image">

## Table Of Contents
  
  - [Database](#database)
  - [Business Context](#business-context)
  - [Problem Statement](#problem-statement)
  - [Visualization using Power BI](#visualization-using-power-bi)

## Database
The AdventureWorks database supports standard online transaction processing scenarios for a fictitious bicycle manufacturer (Adventure Works Cycles). Scenarios include Purchasing, Product Management, Sales, and Human Resources.

- You could explore data [here](https://console.cloud.google.com/bigquery?authuser=0&project=adventureworks2019&ws=!1m0&pli=1)

- Data Dictionary [here](https://drive.google.com/file/d/15kCAbYbG0pchpVHmkV_2CeLfAFe1D9_5/view?usp=sharing)

## Business Context

Adventure Works Cycles, a large, multinational manufacturing company,  produces and distributes metal and composite bicycles to North American, European,  and Asian commercial markets. While its base operation is located in Bothell,   Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. In 2000, Adventure Works Cycles bought a   small manufacturing plant, Wide World Importers, which is located in Mexico City,  Mexico. Wide World Importers manufactures several critical subcomponents for the  Adventure Works Cycles product line. These subcomponents are shipped to the Bothell  location for final product assembly. In 2001, Wide World Importers became the sole  manufacturer and distributor of the touring bicycle product group. 

After a successful fiscal year, Adventure Works Cycles is looking to broaden its  market share by focusing its sales efforts on the company’s best customers, and reducing the cost  of sales by reducing production costs.

## Problem Statement

Sales representatives from regional sales offices have assigned sales territories in the United States, Canada, England, Australia, Germany, and France. Each regional office consists of several sales representatives and a team manager. In their daily sales activities, sales representatives use both laptops and Handheld PCs that run Microsoft® Windows CE. A typical work day for a sales representative starts with the representative dialing in to the regional office and downloading current data such as inventory, product, and promotional information. During customer visits, the sales representative takes orders on the laptop or Handheld PC. At the end of each day, the sales representative sets up appointments for the following day or week, checks the appointments of other representatives in the area for possible collaboration, and updates the contact list. The sales representative dials back into the regional office, sends updated information, and receives any new internal communications from the base office or regional office. The company currently uses Microsoft Outlook® for email. 

The sales teams have identified the following requirements that will enable them to perform their jobs better: 

**Customer segmentation and profiling:**
The sales team needs to be able to extract valuable information from raw data available in the databases to answer questions such as the following: 
- What are the early warning signs of problems? 
- Who are the best customers across all product lines? With whom should the sales team focus its efforts for building long-term relationships? 
- What are customers’s issues, categorized according to demographic groups (geographic location, revenue history, and so on)? 
- What products are the customers buying and at what rate?

## Visualization using Power BI
![AdventureWorkCycleImage](https://github.com/Hoaithomint/Power-BI/assets/141213880/f1e0a0c9-db25-453b-bca5-c4e708e7c89a)
### Insights:
The primary driver for customers when purchasing Adventureworks bike products is the pricing policy.

Based on the RFM analysis conducted to examine and categorize customers according to their historical transaction data (accumulated over the company's entire business cycle from 2011 to 2014), Adventureworks has identified areas for potential improvement:

1. **Hibernating Customers**: Approximately one-third of the total customer base falls into this category. These customers have not made purchases for an extended period and exhibit weak purchasing behavior, characterized by infrequent buying and low shopping cart values.

2. **Lost Customers**: Approximately 11% of the customer base falls into this category. These customers have also not made purchases for a significant duration, and their purchasing frequency and shopping cart values are notably low. Typically, this group consists of customers who either seek variety in their purchases or have made a single purchase to test and compare Adventureworks' products or services with others.

On a positive note, looking at the most recent transaction data, the company has successfully attracted:

- **New Customers**: Approximately 24% of new customers have been acquired. These are individuals who made recent purchases, had relatively low cart values, and did not make frequent purchases.

- **Promising Customers**: Around 8% of the customer base falls into this category. These customers show potential for increased engagement and loyalty.

- **Champions and Loyals**: A significant 23% of customers fall into this category. They exhibit frequent purchasing behavior, with moderate to generous spending.

In terms of product lines:

- **Bikes**: Bikes are the leading product line in terms of revenue, even though the accessories line has a higher concentration of orders. Specifically, Road, Mountain, and Touring bikes are the top-performing segments within the bike product line.

When analyzing demographic segments:

- **Geographic Concentration**: The majority of website visitors are concentrated in two primary regions, the United States (32%) and Australia (31%).

- **Age Group**: The primary age group of customers ranges from 45 to 65 years old.

- **High Revenue Customer Profile**: Customers with university degrees, employed in professional positions, with an average annual income ranging from $50,000 to $70,000, homeowners, and without children, contribute the highest revenue to the company.

### Recommendations
To leverage these insights, here are some actionable strategies:

1. **Marketing Reinforcement**: Focus marketing efforts on high-demand product lines such as road, mountain, and touring bikes. Consider bundling these bikes with relevant accessories to capture customer attention and drive higher sales.

2. **Geographic Concentration**: Concentrate marketing efforts and resources on the two primary potential markets: Australia and the United States. These regions boast substantial populations and a strong bicycle culture.

3. **Customer Incentives and Rewards**: Implement incentives and rewards programs for both existing and potential customers. Retaining loyal customers often incurs lower costs than acquiring new ones. Standardize new customer care processes and offer welcome coupons to enhance the onboarding experience.

4. **Flash Sales and Promotions**: Host weekend flash sales and offer free shipping for a limited duration to stimulate purchases. Additionally, provide new product coupons to incentivize customers to explore and buy new offerings.

5. **Customer Engagement via Email**: Utilize email marketing to send timely reminders to different customer segments. These reminders can include alerts for dormant customers, nurturing campaigns for customers who require attention, and personalized offers to re-engage customers.

**To Re-Engage Hibernating and Lost Customers:**

1. **Personalized Reconnection**: Reach out to these customers with personalized and interactive communication. Use email, social media messages, or even phone calls to reconnect. Address any negative experiences they may have had and emphasize improvements made since their last purchase.

2. **Retargeting Campaigns**: Implement retargeting campaigns to remind them of your products and services. Showcase short-term promotions, vouchers, discounts, or exclusive offers to entice them back.

3. **Diversify Product Offerings**: Present them with other relevant products and special discounts that align with their previous purchases. This not only rekindles their interest but also broadens their engagement.

4. **Recreate Brand Value**: Use marketing strategies to reestablish the brand's value. Highlight any enhancements, updates, or unique selling points that differentiate your products or services.

5. **Reach-Out Campaigns**: Consider running specific reach-out campaigns targeting these customer segments, focusing on those who have been inactive. Ignore customers who have explicitly opted out of communication.

By implementing these strategies, Adventureworks can increase customer retention rates, boost average cart values, and foster long-term customer loyalty across various segments of their customer base.

**To Nurture New Customers and Promising Customers:**

1. **Methodical, Personalized Care**: Create a methodical and highly personalized care process for new customers. This includes sending a thank-you message and soliciting feedback on their initial purchase experience.

2. **Welcome Discounts**: Provide a discount welcome voucher for their next purchase. This not only encourages a repeat purchase but also shows appreciation for their business.

3. **Continuous Interaction**: Maintain regular interaction with these customers. Suggest products related to their initial purchase, offering cross-sell and upsell options, bundles, or larger-sized products.

4. **Brand Awareness**: Continue to build brand awareness among new and promising customers. Share information about your brand's values, mission, and product/service quality to create a lasting impression.

5. **Free Trials**: Offer free trials or samples where applicable. This allows customers to experience your products or services before committing to larger purchases.

**To Retain Champion Customers:**

1. **Loyalty Program**: Develop an exclusive loyalty program tailored to this group. Offer different and highly personalized benefits such as special offers, promotions, point accumulation, and redemption programs. Create separate incentives for different tiers within this group to acknowledge their varying levels of loyalty.

2. **Personalized Upselling**: Given their high trust and commitment to the brand, implement personalized upselling strategies. Analyze their order history to make predictions about their preferences, and suggest items of greater value and product combos that align with their previous purchases.

3. **Rewards and Early Access**: Show appreciation for their loyalty by rewarding them with exclusive benefits. Consider making them early adopters of new products, allowing them to experience and promote your brand's latest offerings.

**To Increase Cart Value for Loyal Customers:**

1. **Incentive Programs**: Propose incentive programs that are tied to spending thresholds. Offer rewards or discounts for reaching specific spending milestones, encouraging them to increase their cart value with each purchase.

2. **Upselling**: Recommend higher-value products or bundles to loyal customers based on their purchase history and preferences. Highlight the additional value and benefits of these products to entice them to upgrade their purchases.

3. **Request Reviews**: After a successful purchase, ask loyal customers to leave reviews or feedback. Positive reviews can inspire confidence in other potential customers and may lead to increased sales.

4. **Engagement**: Continuously engage with loyal customers through personalized communication. Keep them informed about new products, promotions, and relevant updates to encourage them to explore and purchase more from your brand.

By implementing these strategies, Adventureworks can maintain the loyalty of their Champion customers while encouraging their Loyal customers to increase their cart values with each transaction, ultimately driving higher revenue and customer satisfaction.

