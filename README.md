# Product-Marketing-Campaign-Performance-Analysis-against-Competitors-in-Looker-Studio
Product Campaign Metrics: Comparing Marketing Campaigns against Competitors

This report presents a comprehensive analysis of the business performance of Tech Tech in 2023, examining key metrics such as sales, ROI, and their correlation with external economic factors (GDP growth, inflation rate, and consumer sentiment). By understanding the interplay between these variables, this analysis provides actionable insights and strategic recommendations to improve future performance.

## Project title: 
Product Campaign Metrics: Comparing Marketing Campaigns against Competitors
This case study showcases the use of data analytics to evaluate and enhance marketing strategies within the consumer electronics industry. Focused on assessing the effectiveness of marketing campaigns, the study highlights how data-driven insights can significantly optimize strategies and bolster competitive positioning. Additionally, it offers a practical demonstration of designing and implementing a relational database structure using data analytics tools such as LOOKER, facilitating deeper analysis and better decision-making processes.

Key learning points
1.	Data Blending
2.	Data Analysis
3.	Data Visualization
4.	Recommendations
5.	Dashboard Design and Reporting
6.	Business Overview/Problem

## Business Overview/Problem
TechTech faces a multifaceted business challenge that demands astute resolution. The core elements of this challenge encompass:
 
•	A. Competition Management: TechTech operates in an industry where competition is fierce, with both established giants and nimble newcomers vying for market share. Navigating this competitive landscape requires not only vigilance but also strategic acumen.
•	B. Resource Allocation: In an era of resource constraints, the judicious allocation of marketing resources is critical. Ensuring that every marketing dollar is optimally spent to yield the highest return on investment is an ongoing challenge.
•	C. Performance Evaluation: To thrive in a competitive environment, TechTech must continually assess the effectiveness of its marketing campaigns. Understanding how its campaigns perform relative to competitors is crucial for maintaining a strong market presence.
•	D. Brand Enhancement: In a marketplace teeming with choices, enhancing brand visibility and positioning is an imperative. TechTech must devise strategies that not only resonate with consumers but also strengthen its brand's foothold in the minds of its target audience.

## Rationale for the Project
In the dynamic realm of Marketing and Sales, assessing campaign effectiveness is pivotal. Here are the top five reasons that emphasize the significance of this project:
 
•	A. Competitive Edge: Understanding how TechTech's marketing campaigns fare against competitors will enable the company to maintain a competitive edge.
•	B. Resource Allocation: Efficient allocation of marketing resources based on data-driven insights can significantly enhance ROI.
•	C. Brand Visibility: By optimizing marketing strategies, TechTech can enhance its brand visibility in a highly competitive market.
•	D. Customer Engagement: Targeting the right marketing channels and tactics will lead to improved customer engagement.
•	E Market Trends: Analyzing external factors and industry trends will provide TechTech with a better understanding of the market landscape.

## Aim of the Project
This project has well-defined objectives aimed at addressing the business challenges through POWER BI:
 
•	A. Performance Analysis: Evaluate TechTech's marketing campaign performance.
 
•	B. Strategy Enhancement: Identify strengths and weaknesses in marketing strategies.
 
•	D. Channel Optimization: Determine the most effective marketing channels and tactics.
 
•	E. Actionable Insights: Provide actionable recommendations for improving campaign effectiveness.

## Data Description
This case study contains 4 datasets and they are as follows:
 
### Marketing Campaigns Table:
•	✓ Campaign ID (Text): A unique identifier for each marketing campaign.
•	✓ Customer ID (Text): A reference to the customer associated with the campaign.
•	✓ Ad Spend (Currency, e.g., USD): The amount of money spent on the campaign.
•	✓ Impressions (Number of Impressions): The total number of times the campaign materials were displayed to users.
•	✓ Clicks (Number of Clicks): The number of times users clicked on the campaign materials.
•	✓ Conversions (Number of Conversions): The number of desired actions taken as a result of the campaign.
•	✓ Sales (Currency, e.g., USD): The revenue generated directly attributed to the campaign.
•	✓ Campaign Start Date (Date): The date when the campaign started.
•	✓Campaign End Date (Date): The date when the campaign ended.
 
### Customers Table:
•	✓ Customer ID (Text): A unique identifier for each customer.
•	✓ Age (Years): The age of the customer.
•	✓ Gender (Text): The gender of the customer (e.g., Male, Female, Other).
•	✓ Location (Text): The geographical location of the customer (e.g., City, State, Country).
•	✓ Customer Segment (Text): A categorical designation of the customer (e.g., Premium, Regular, New).
 
### Competitor Campaigns Table:
•	✓ Campaign ID (Text): A reference to the campaign in the Marketing Campaigns Table.
•	✓ Competitor ID (Text): A unique identifier for each competitor.
•	✓ Ad Spend (Currency, e.g., USD): The amount of money the competitor spent on their campaign.
•	✓ Impressions (Number of Impressions): The total number of times the competitor's campaign materials were displayed.
•	✓ Clicks (Number of Clicks): The number of times users clicked on the competitor's campaign materials.
•	✓ Conversions (Number of Conversions): The number of desired actions taken as a result of the competitor's campaign.
•	✓ Sales (Currency, e.g., USD): The revenue generated directly attributed to the competitor's campaign.
•	✓ Campaign Start Date (Date): The date when the competitor's campaign started.
•	✓ Campaign End Date (Date): The date when the competitor's campaign ended.

### External Factors Table:
•	✓ Date (Date): The date for which the external data is recorded.
•	✓ GDP Growth Rate (Percentage): The percentage change in Gross Domestic Product (GDP) compared to the previous period.
•	✓ Inflation Rate (Percentage): The percentage change in consumer price inflation compared to the previous period.
•	✓ Consumer Sentiment Index (Index Score): An index representing consumer sentiment and confidence.
•	✓ Industry Trends (Text): A description of emerging trends and developments in the industry.

## Tech Stack: Tool - Looker
 
It will be used for :
•	A. Data Integration
•	B. Data Transformation
•	C. Data Analysis and Modeling
•	D. Real-time Data Visualization
•	E. Dashboard Design
•	F. Reporting
•	G. Cloud Integration

## Project Scope
•	A. Exploratory Data Analysis: Explore the data to understand its characteristics and discover patterns.
 
•	B. Data Transformation: Prepare the data for analysis by transforming, encoding, or normalizing it.
 
•	C. Data Analysis: Analyze data to understand patterns in order to generate insights that will be visualized.
 
•	D. Data Visualization: Create visual representations to communicate insights effectively.
 
•	E. Interpretation and Insight Generation: Extract meaningful insights and interpret the results.

## Key Performance Metrics:
Sales and ROI Trends (2023):
•	Q1, 2023:
o	Sales: +109.09%
o	ROI: +101.93%
•	Q2, 2023:
o	Sales: +105.86%
o	ROI: +106.89%
•	Q3, 2023:
o	Sales: +103.86%
o	ROI: +104.24%
•	Q4, 2023:
o	Sales: +84.89% (significant decline)
o	ROI: +89.41% (notable decrease)
External Factors:
•	GDP Growth Rate:
o	Peaked at 104.58% in Q2 and declined to 94.62% in Q4.
•	Inflation Rate:
o	Highest at 103.43% in Q1, decreasing to 98.08% in Q4.
•	Consumer Sentiment Index:
o	Peaked at 101.42% in Q3, falling to 99.47% in Q4.
________________________________________
## Insights:
1.	Strong Start in Q1 and Q2:
o	Sales and ROI were at their highest in Q1 and Q2. This performance was driven by strong economic conditions, including high GDP growth (104.58% in Q2) and positive consumer sentiment. The business capitalized on favorable market conditions, leading to increased consumer spending.
2.	Decline in Q4 Performance:
o	A sharp decline in both sales and ROI was observed in Q4. This coincided with a notable slowdown in GDP growth and consumer sentiment. The business faced external pressures from a cooling economy, leading to reduced purchasing power and lower returns.
3.	Resilience to Inflation in Early Quarters:
o	Despite elevated inflation in Q1 (103.43%) and Q3 (101.71%), the business maintained strong sales and ROI. This suggests effective pricing and marketing strategies that mitigated inflationary pressures and preserved consumer demand.
4.	Consumer Sentiment's Impact:
o	Fluctuations in consumer sentiment had a direct impact on ROI. Higher consumer confidence in Q2 and Q3 translated into stronger business performance, while the dip in sentiment in Q4 aligned with a decline in sales and ROI.
________________________________________
## Recommendations:
1. Adjust Strategies Based on Consumer Sentiment:
•	Consumer confidence is a critical driver of performance. When sentiment is high, consider launching premium or value-added services to maximize revenue. During periods of low confidence, focus on discounts, promotions, or loyalty rewards to sustain sales and encourage customer retention.
2. Proactive Economic Sensitivity Planning:
•	The business showed sensitivity to economic downturns, particularly in Q4. Implement preemptive measures, such as adjusting pricing strategies or optimizing supply chain operations, to reduce costs and protect margins during economic slowdowns.
3. Inflation-Resistant Marketing Campaigns:
•	Given the resilience to inflation in Q1 and Q3, continue leveraging marketing campaigns that emphasize value and necessity over luxury. Highlight affordability and long-term benefits in product messaging to maintain sales momentum even in times of high inflation.
4. Quarterly Business Review Process:
•	Given the quarterly fluctuations in sales and ROI, establish a quarterly review process for business strategies. This should include analyzing the impact of external economic factors, evaluating ongoing campaigns, and making adjustments to align with real-time market conditions.
5. Diversification of Product Offerings:
•	As the business faces external volatility, diversification of product offerings, especially in recession-resistant segments, will help maintain stable revenue streams. Focus on identifying customer pain points during economic downturns and tailor product offerings to address those challenges.
________________________________________
## Conclusion:
The 2023 performance of Tech Tech exhibited significant sensitivity to external economic factors, particularly GDP growth, inflation, and consumer sentiment. By closely monitoring these factors and implementing the recommendations outlined above, the business can enhance its resilience to economic fluctuations and improve overall sales and ROI. A proactive and flexible approach, paired with timely adjustments to marketing and operational strategies, will ensure long-term business sustainability and growth.
________________________________________
This report serves as a data-driven foundation for strategic decision-making, enabling Tech Tech to optimize its business performance in line with external market conditions.

PS: View the interactive nature of the dashboard on Looker studio: https://lookerstudio.google.com/reporting/e68caf4b-a1ab-4849-9f4c-003b990acd64
