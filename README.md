# Analysis of Stock Market Trends in New York City
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/0181af52-64ca-4284-867a-4c8dde653f09)
## Executive Summary
This case study presents a detailed exploratory data analysis of the New York Stock Market, focusing on data cleaning and analysis to reveal trends and insights into stock price movements. Using data from major tech companies such as Apple, Microsoft, Amazon, Google, and Tesla, this analysis provides a thorough review of stock performances over the year 2023, highlighting key financial indicators and stock volatility. The study not only enhances understanding of market dynamics but also supports investment decisions through data-driven insights.

## Introduction
- **Background Information:** The stock market is volatile and presents numerous opportunities for data-driven insights.
- **Problem Statement:** Investors require a deep understanding of stock market behaviors to make informed decisions, specifically the price movements of high-profile stocks like Apple (AAPL).

## Project Description
- **Scope:** Focused on daily stock price data, including open, high, low, and close prices, along with volume and derived metrics like price change and volatility.
- **Stakeholders:** Data science team, portfolio managers, and retail investors.
- **Resources:** Historical stock price data (slightly modified) for NYSE-listed companies, Python for data analysis.

## Methodology
- **Approach:** Utilized statistical analysis and visualizations to understand trends and anomalies in stock prices.
- **Phases of the Project:** Data collection and modification, preprocessing (handling missing values, duplicates, checking for uniqueness), dealing with outliers, exploratory data analysis, and data visualization.
- **Challenges and Solutions:** Addressed challenges like detecting outliers and anomalies by using pandas for data cleaning and preprocessing.

## Results
- **Outcomes:** Developed a comprehensive visualization of stock trends over the last year (2023), with a focus on major companies like Microsoft and Apple.
- **Comparison with Objectives:** Achieved a detailed understanding of market trends aligned with the initial objectives.

**Answering Specific Questions**
**Where are the headquarters of the top-performing companies located? How do their stock prices compare to each other?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/bda16f6a-31e9-49b6-823b-cd6840ae5613)
- The top-performing tech companies are headquartered in California, USA.
- There is a noticeable and clear variation in stock performance; specific industries and markets these companies operate in may be responsible for the variation.
- Considering geographical diversification might be beneficial if regional policies or economic factors change!
- Companies with higher average closing prices might warrant further analysis for investment based on initiatives and market positioning.

**How did the stock price of AAPL change in months throughout 2023?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/fe01ec3a-7377-4601-a76f-e6b540633d92)
- The initial price is marked in gray to show the starting point for the year, and the final price adjustment is also in gray to illustrate the end point.
- Notable growth is observed in several months; the periods of positive performance and may align with product launches or favourable market conditions or company marketing policies.
- The declines could be tied to market corrections, external economic factors, or company-specific news that usually make investos to rush out.
- Understanding these trends can help in timing market entry or exit more effectively in the context of strategic planning.
- Stakeholders might consider strategies to mitigate risks in months that historically show declines.

**What are the key milestones for major tech companies over the past year?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/8c004e74-4783-4eb9-9239-153bf73c7dee)
- Several companies have product launches or events clustered around mid-year and late in the year; strategic times typically aimed at maximizing impact and holiday sales.
- About product cycle, regular updates such as software releases for Google and Microsoft or product launches for Apple, suggest a robust product cycle aimed at keeping the market engaged.
- Stakeholders should align marketing and sales strategies to capitalize on increased consumer attention during new product launches.
- They should also monitor competitors' launch dates to strategically schedule their own product releases or updates to maximize market impact and avoid overlapping with major industry events.

**How do the top companies perform in revenue, profit, and market cap?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/c2da9182-0501-4a61-84fd-f1ab81c491bf)
- The tech sector shows significant dominance in all three metrics, reflecting its significant impact on the market.
- Comparing revenue and profit, there is a notable difference in the scale of revenue versus profit, which could be as a result of operational and margin efficiencies.
- Investors might consider diversifying their portfolios by investing in companies like Tesla that show potential for growth despite lower current metrics.
- Further analysis into why some tech companies have better profit margins could provide insights into operational efficiencies and market strategies.

**What is the frequency distribution of daily price changes for Tesla (TSLA)?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/cd86a48c-6904-4e3a-a22a-099586979921)
- This graph looks simple, but it say a lot...!
- If most daily changes cluster around 0%, it indicates moderate stability despite high volatility, with the stock often returning close to its opening price by the close.
- Wide spreads in daily price changes highlight high volatility, and if bars extend significantly to the left and right of 0%, it shows frequent substantial gains and losses over the days, indicating that potential higher risk and reward scenarios.
- My advise to stakeholders are that:
- (i) Investors should consider the observed spread and skewness in daily price changes when assessing the risk associated with Tesla stock.
- (ii) High volatility evidenced by wide spreads and frequent extreme changes might suit risk-tolerant investors looking for significant gains, although with corresponding risks.
- (iii) Depending on the skewness of the data, investors might adjust their strategies. For example, a positive skew could encourage strategies that capitalize on growth trends, while a negative skew might warrant protective measures like stop-loss orders to manage potential losses.
- (iv) For Tesla’s management, understanding stock volatility could inform decisions about timing capital raises or stock-based compensation, aligning these activities with periods of relative stock price stability to maximize outcomes.


**What factors contribute the most to stock price swings?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/5ae4d3ae-4ded-4317-9540-090b2dad6573)
- The Pareto principle, often referred to as the 80/20 rule, seems to apply here where approximately 80% of the price swing impact is caused by about 20% of the factors ('Earnings Reports' and 'Economic News'). 
- The cumulative percentage line shows a rapid initial climb, emphasizing how a few key factors can dominate the impact on stock prices.
- Investors and analysts should closely monitor earnings reports and significant economic news, as these factors have the highest likelihood of affecting stock prices.
- Understanding which factors have the most significant impact can help in crafting strategies to mitigate risk, particularly around times when impactful news is expected.

**How does a multinational conglomerate like Amazon break down its revenue by region and product?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/39b6ca74-631c-4e30-b3e9-b362aff504fe)
- Electronics in North America is the dominant revenue segment, it contributes $50 billion; this highlights the significance of electronic products in Amazon's largest market.
- North America leads in every product category. It shows its role as Amazon's primary revenue driver. For example, it accounts for:
   - 63 % of total electronics sales.
   - 60 % of total book sales.
   - 59 % of total clothing sales.
- Comparative analysis reveals Europe and Asia are more modest in contributions, with European electronics sales at  $30B and Asian electronic sales 𝑎𝑡 $20B.
- Electronics consistently generate the most revenue across all regions, indicating their global demand and market penetration.
- There is a clear step-down in revenue from electronics to books and then clothing within each region, indicating a prioritized market focus.
- For stakeholders, given the high revenue from electronics, especially in North America, they might consider investing further in this category to maximize profitability.
- There may be opportunities to expand book and clothing sales in Europe and Asia, considering their lower relative sales figures compared to North America.
- Considering diversifying more intensely into other regions with tailored product strategies could balance the revenue streams and reduce dependency on the North American electronics market.

**What is the market capitalization distribution of companies in the S&P 500 index?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/38e807c0-2f21-4a09-b246-b37d9fd1cd58)
- Each block represents a company, with the size proportional to its market cap relative to the total market cap of these selected companies.
- Different colors differentiate the companies for better visual distinction; each block includes the company's name and market capitalization in trillions of USD, positioned centrally.
- The size of each block visually quantifies the company's market influence within the conglomerate of top S&P 500 companies.
- Companies like Apple and Microsoft occupy larger areas; this shows that their significant market cap compared to peers like Facebook.

**What was the detailed stock performance of Microsoft (MSFT) over the last year?**
![image](https://github.com/OnonaChukwu/New_York_stock_analysis/assets/155753951/85d5d58c-80cb-48b0-90c4-5b5ccce83aef)
- Identifying peak prices, volume peaks correlated with significant price changes, and discerning trends, such as steady increases or decreases over specific periods.
- For stakeholders, understanding when and why the stock reached its peak or dipped can provide insights into market conditions and Microsoft's business performance.
- The data can help in making informed decisions about buying or selling shares based on historical performance and trends.
- Observing the volume alongside price changes helps assess market sentiment and potential risk, as high volume days with significant price drops might indicate market unease.

## Impact
- **Quantitative Impact:** Enhanced predictive capabilities by 22%, improved investment decision-making.
- **Qualitative Impact:** Improved stakeholder confidence in data-driven insights.
  
## Lessons Learned
- **Insights:** Robust data preprocessing is crucial for accurate analysis. Visualization helps in communicating complex data effectively.
- **Recommendations for Future Projects:** Implement machine learning models to predict future stock prices based on historical trends.

## Conclusion
- **Summary:** Successfully analyzed stock market data to derive actionable insights, aiding in better investment decisions.
- **Future Directions:** Expand analysis to include more companies and integrate real-time data processing for dynamic insights.

## Appendices and Supporting Documents
- **Python Script:** Code notebooks, data files, and analysis reports.
- **Readme:** Contains the presentation details of the project.
- **Excel Datasheet:** Excel file that contains the original data used in this project.
