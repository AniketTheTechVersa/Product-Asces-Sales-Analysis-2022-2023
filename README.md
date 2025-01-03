# Asces Sales Performance Analysis: 2022–2023 and Beyond

## Project Background
Asces Sound is a global leader in audio technology, providing high-quality audio solutions for professionals and enthusiasts. Established as a trusted name among musicians, content creators, and audio engineers, Asces Sound specializes in state-of-the-art audio interfaces, microphones, and accessories. With a focus on advanced engineering and unmatched durability, the company drives creative workflows and empowers users worldwide.

This project analyzes sales data from 2022 to 2023 and extends to insights from 2024 to uncover trends, anomalies, and actionable strategies. The aim is to enhance strategic decision-making for Asces Sound while showcasing my data analytics expertise.

Insights and recommendations are provided on the following key areas:
- **Revenue by Country**: Identifying top-performing regions and trends.
- **Temporal Trends**: Examining revenue, profit, and seasonal performance.
- **Product Performance**: Evaluating top sellers and identifying growth opportunities.
- **Discount Strategies**: Understanding the impact of discounts on revenue and profitability.
- **Customer Segments**: Analyzing revenue patterns by customer type.

The SQL queries used to inspect and transform the data for this analysis can be found [here](https://github.com/AniketTheTechVersa/Personal_Projects-Data-Anakytics/blob/main/Asces_Data_Transformation_queries.sql) 
 
An interactive Power BI dashboard used to report and explore sales trends can be found here [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmRmYzIyMTctNmQ5ZC00YjBhLWFmYTUtNzhlYWVhNGRlZWIxIiwidCI6IjM0YmQ4YmVkLTJhYzEtNDFhZS05ZjA4LTRlMGEzZjExNzA2YyJ9)

---

## Data Structure & Initial Checks
The company's main database structure includes detailed sales, product, customer, and transaction records. Key elements analyzed:
- **Sales Data**: Contains transaction-level details, including product, revenue, discount, and customer type.
- **Product Details**: Includes descriptions, categories, and price points.
- **Customer Segments**: Tracks buyer personas such as enterprise, government, and creators.

![Screenshot 2025-01-03 165325](https://github.com/user-attachments/assets/d14fe105-dcea-4aa1-9411-debeef1cdcd5)




---

## Executive Summary

### Overview of Findings
This analysis uncovered several critical insights driving sales and profitability:
1. **Canada leads global revenue** at $613,913, while South America underperforms, requiring targeted efforts.
2. **Seasonality plays a significant role**, with Q4 and June driving peak revenue, aligning with holiday shopping and targeted campaigns.
3. **Scarlett 2i2 dominates sales**, contributing 28.58% to total revenue, highlighting its flagship status.
4. **Discount strategies need optimization**, as medium discounts strike a balance, while excessive high discounts reduce profitability.
5. **Enterprise customer growth surged by 197.93% in 2023**, reflecting successful B2B engagement.

![Screenshot 2025-01-04 001614](https://github.com/user-attachments/assets/08cc5737-7bf5-4e1b-9c9b-ec4a267438b3)



---

## Insights Deep Dive

### **1. Revenue by Country**
#### **Main Insights**
- **Canada contributes 20.78% of total revenue**, with Germany trailing at $558,375.
- The **USA accounts for 31.86% of accidents**, driven by high-volume enterprise and government clients.

#### **Analysis**
Canada's success reflects a mature market with high product adoption, while South America's underperformance signals lower awareness and distribution issues.

#### **Recommendations**
1. **Expand Marketing in South America**: Focus on localized campaigns to raise awareness.
2. **Customer Retention Programs in Canada**: Use loyalty initiatives to maintain leadership.

![Screenshot 2025-01-04 002611](https://github.com/user-attachments/assets/822acd99-91cf-4b35-b785-ef91f94b60b7)



---

### **2. Temporal Trends**
#### **Main Insights**
- **2023 saw a revenue increase of 52.68%**, reversing a 13.33% decline in 2022.
- **Quarter 4 led sales in 2023**, with $478,200 in revenue, while June consistently performed well across years.

#### **Analysis**
Seasonality aligns with holiday-driven demand in Q4 and promotional spikes in June.

#### **Recommendations**
1. **Seasonal Campaigns**: Launch promotions aligned with Q4 and June trends.
2. **Mid-Year Launches**: Introduce new products during off-peak months to balance sales.

![Screenshot 2025-01-03 235438](https://github.com/user-attachments/assets/741dcf62-61ee-4d17-a5a8-629bbcc1b7cc)


---

### **3. Product Performance**
#### **Main Insights**
- **Scarlett 2i2 contributed $844,493** in revenue, outperforming competitors by 143.56%.
- Other notable products: MV7 and NT1-A microphones, which drive volume but with thinner margins.

#### **Analysis**
Scarlett 2i2's versatility appeals to both creators and professionals, while MV7’s lower margins suggest room for pricing optimization.

#### **Recommendations**
1. **Expand the Scarlett Ecosystem**: Introduce complementary products to boost cross-sells.
2. **Optimize Pricing for MV7**: Reduce discounts for less price-sensitive buyers.

![Screenshot 2025-01-04 000002](https://github.com/user-attachments/assets/1d624671-48e2-4ba4-8a05-c6f5eb974536)


---

### **4. Discount Strategies**
#### **Main Insights**
- Medium discounts contributed **$915,541**, offering the best balance of sales and profitability.
- High discounts drove revenue but reduced margins, especially on MV7.

#### **Analysis**
Medium discounts work best across segments, while high discounts require careful application to avoid profit erosion.

#### **Recommendations**
1. **Focus on Medium Discounts**: Apply selectively for maximum impact.
2. **Reevaluate High Discounts**: Limit to inventory clearance or market penetration.

![Screenshot 2025-01-04 000542](https://github.com/user-attachments/assets/51c2442e-0fb5-41ad-9d25-57b99ccf40e9)


---

### **5. Customer Segments**
#### **Main Insights**
- **Government customers led sales**, contributing 52% of revenue but with reduced margins due to discounts.
- **Enterprise customers grew by 197.93% in 2023**, reflecting successful B2B strategies.

#### **Analysis**
Institutional markets offer volume but require careful discount management, while B2B growth highlights the potential for customized solutions.

#### **Recommendations**
1. **Enterprise Relations**: Expand customized bundles for enterprise clients.
2. **Enhance B2C Engagement**: Focus on creators and small businesses to diversify revenue streams.

![Screenshot 2025-01-04 000941](https://github.com/user-attachments/assets/b4410f99-e93c-4cb8-99a3-4c6b405397d3)


---

## Recommendations:
Based on the insights and findings above, Asces Sound should consider:
1. **Geo-Targeted Campaigns**: Invest in localized marketing for underperforming regions like South America.
2. **Seasonal Promotions**: Align campaigns with high-revenue months (June, Q4).
3. **Product Expansion**: Build complementary offerings around Scarlett 2i2.
4. **Discount Optimization**: Focus on medium discounts for sustainable growth.
5. **Customer Diversification**: Balance B2B strategies with improved B2C engagement.

---

## Assumptions and Caveats:
This analysis was based on several assumptions:
1. Missing data for specific months was estimated using prior trends.
2. Currency conversions were standardized to USD for consistency.
3. Some outlier transactions (e.g., refunds or unusually high discounts) were excluded for clarity.
4. Customer segmentation relied on provided categories without external validation.

---

You can explore the interactive dashboard for more insights.  
[Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYmRmYzIyMTctNmQ5ZC00YjBhLWFmYTUtNzhlYWVhNGRlZWIxIiwidCI6IjM0YmQ4YmVkLTJhYzEtNDFhZS05ZjA4LTRlMGEzZjExNzA2YyJ9)

