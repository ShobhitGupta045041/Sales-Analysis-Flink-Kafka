# Sales-Analysis-Flink-Kibana

# About the Dataset
The dataset represents e-commerce sales data, with detailed information about each order. It includes variables such as customer demographics, product details, sales performance, and shipping details. The dataset can be analyzed to understand customer preferences, sales patterns, and operational insights.

# Variable Description<br>
1. Index: A unique identifier for each record in the dataset.<br>
2. OrderID: Unique identifier for each order. Used for tracking and referencing specific purchases.<br>
3. CustID: Unique identifier for each customer. Useful for customer segmentation and behavior analysis.<br>
4. Gender: Gender of the customer. Used for demographic analysis and targeting.<br>
5. Age: Age of the customer. Helps in segmenting customers by age groups.<br>
6. AgeGroup: Age category of the customer. A more generalized classification based on age.<br>
7. Month: Month of the transaction. Useful for analyzing seasonality and trends.<br>
8. Date: Exact date of the transaction. Enables detailed time-series analysis.<br>
9. Status: Status of the order. Tracks the outcome of transactions.<br>
10. Channel: Sales channel or platform through which the order was placed. Useful for channel performance analysis.<br>
11. SKU: Stock Keeping Unit, a unique identifier for each product. Enables inventory tracking.<br>
12. Category: Product category. Helps analyze sales by product type.<br>
13. Size: Size of the product. Useful for identifying popular sizes.<br>
14. Qty: Quantity of the product purchased. Indicates order volume.<br>
15. Currency: Currency of the transaction. Typically used for international sales analysis (if applicable).<br>
16. Amount: Total monetary value of the order. Useful for revenue analysis.<br>
17. ShipCity: City to which the product was shipped. Useful for geographic analysis.<br>
18. ShipState: State to which the product was shipped. Provides insights into regional performance.<br>
19. ShipPostalCode: Postal code for the shipping address. Helps in precise geographic targeting.<br>
20. ShipCountry: Country to which the product was shipped. Important for analyzing international sales.<br>
21. B2B: Indicates whether the transaction was a Business-to-Business (B2B) sale. Useful for separating B2B and B2C transactions.<br>

# Dataset
![image](https://github.com/user-attachments/assets/08a7f3d3-83b2-4521-b11d-e9f28539eaef)<br>

[Dataset Link](https://www.kaggle.com/datasets/mishrashikhar/sales-dashboard)<br>

# Dashboard
![Whole Dashboard1](https://github.com/user-attachments/assets/4c17588b-50fb-4c47-9138-248c61b3f07d)<br>
![Whole Dashboard2](https://github.com/user-attachments/assets/a0a00249-7cef-42ed-9c15-b47c830d5dc6)<br>



[Video Me.webm](https://github.com/user-attachments/assets/65e81b32-066f-4061-b6ad-855f000fe0df)



# Analysis
Question 1. What is the distribution of orders between male and female customers?<br>

Graph:<br>

![Graph-1](https://github.com/user-attachments/assets/bf7b541f-6924-4c57-859d-5deb45b7db7f)
<br>

Purpose of the Graph:<br>
- To understand the demographic breakdown of orders and assess which gender contributes more to the business.<br>

Insights:<br>
- Amazon is the leading sales channel, contributing the highest sales amount, surpassing ₹1,200,000.<br>
- Myntra and Flipkart follow, with similar performance levels, generating slightly less than Amazon.<br>
- Ajio and Naalli contribute significantly less, with Naalli showing the lowest sales among all channels.<br>
- This indicates a clear disparity in performance, suggesting that Amazon, Myntra, and Flipkart should remain focal platforms for sales strategies, while efforts might be needed to improve performance on Ajio and Naalli.<br>

----

Question 2. What is the distribution of orders between male and female customers?<br>

Graph:<br>

![Graph-2](https://github.com/user-attachments/assets/11d125c2-83fb-4833-a5ca-2465fdee1b02)
<br>

Purpose of the Graph:<br>
- To understand the demographic breakdown of orders and assess which gender contributes more to the business.<br>

Insights:<br>
- Women account for a significantly larger share of orders, as represented by the green section, dominating the overall distribution.<br>
- Men contribute a noticeably smaller proportion, as depicted by the blue section.<br>
- This insight suggests that the product range or marketing strategies may be more appealing to female customers.<br>
- Businesses can leverage this data to further target female audiences or explore strategies to increase engagement and orders from male customers.<br>

----

Question 3. How are different age groups distributed by gender?<br>

Graph:<br>

![Graph-3](https://github.com/user-attachments/assets/7a561e51-c021-4ffe-b8b0-7aaf25d5fe61)
<br>

Purpose of the Graph:<br>
- To analyze and compare the gender distribution (Men and Women) across different age groups (Adult, Teenager, Senior).<br>

Insights:<br>
- Adults: This group has the highest count, with a larger proportion of women compared to men.<br>
- Teenagers: The count is lower than adults but higher than seniors. Men make up a notable share, though women still outnumber men.<br>
- Seniors: This group has the smallest count, with women again outnumbering men.<br>

----

Question 4. How does the average amount spent vary across different ages?<br>

Graph:<br>

![Graph-4](https://github.com/user-attachments/assets/9ce501eb-2173-4516-a474-e35ba25e7355)
<br>

Purpose of the Graph:<br>
- To identify spending patterns among individuals of different age groups and assess trends in spending behavior.<br>

Insights:<br>
- The highest spending is observed among younger individuals (around age 20–30), with the peak amount spent by people in their early twenties.<br>
- Spending gradually decreases with age, showing a consistent downward trend from age 30 onward.<br>
- Individuals above age 60 have the lowest spending levels, potentially indicating reduced income or changes in spending priorities as people age.<br>

----

Question 5. How is the order volume distributed across states and e-commerce channels?<br>

Graph:<br>

![Graph-5](https://github.com/user-attachments/assets/e9a6872d-5e74-420d-a60a-b2536ef4fdad)
<br>

Purpose of the Graph:<br>
- To identify the states with the highest and lowest order volumes for different e-commerce platforms and understand geographical distribution patterns.<br>

Insights:<br>
- Amazon and Myntra have the highest order volumes, particularly in Maharashtra and Karnataka.<br>
- Flipkart performs well in states like Telangana and Uttar Pradesh, but it is less dominant compared to Amazon and Myntra.<br>
- Other platforms such as Ajio, Nalli, and Meesho have significantly lower order volumes across most states, indicating limited market presence or niche customer bases.<br>
- States like Delhi, West Bengal, and Andhra Pradesh show moderate activity across all platforms but lack peak order volumes seen in larger markets like Maharashtra.<br>

----

Question 6. Which cities contribute the most to sales based on the sum of the amount?<br>

Graph:<br>

![Graph-6](https://github.com/user-attachments/assets/2c6c3a79-50ae-485c-a2eb-19ecd44afa24)
<br>

Purpose of the Graph:<br>
- To visually identify cities with the highest sales contributions. The size of the text in the word cloud indicates the sales volume, allowing for quick insights into which cities are top contributors.<br>

Insights:<br>
- Bengaluru appears to be the city with the highest sales, followed by Hyderabad, New Delhi, and Mumbai.<br>
- Cities like Kolkata, Chennai, and Pune also contribute significantly but are relatively smaller in sales compared to the top cities.<br>
- The word cloud provides a clear indication of sales distribution across different cities, highlighting major sales hubs.<br>

----

Question 7. What is the total revenue or sales amount?<br>

Graph:<br>

![Graph-7](https://github.com/user-attachments/assets/a8763e91-b0f9-42ec-bc1e-002155c1510e)
<br>

Purpose of the Graph:<br>
- To provide a clear, single-value summary of the total sales achieved, enabling a high-level view of overall performance.

Insights:<br>
- The total sales amount is 3,445,324. This serves as a key performance indicator (KPI) for overall revenue, helping stakeholders quickly assess the company's financial performance.<br>
- This metric is critical for tracking revenue targets and comparing performance across different time periods or against benchmarks.<br>

----

Question 8. How does revenue vary by product category across different sales channels?<br>

Graph:<br>

![Graph-8](https://github.com/user-attachments/assets/14b57055-339b-4af1-9926-99ee700b2381)
<br>

Purpose of the Graph:<br>
- To analyze the revenue contribution of different product categories and evaluate performance across sales channels such as Amazon, Flipkart, Myntra, etc.

Insights:<br>
- Top-performing category: The "Set" category generates the highest revenue across all channels, with Amazon contributing significantly.<br>
- Kurta and Western Dress follow as high-revenue categories, though their contributions vary across channels.<br>
- Channels like Amazon dominate revenue generation in multiple categories, with a steep lead in most.<br>
- Categories like Bottoms and Women's Ethnic Dresses show minimal revenue contributions across all channels.<br>
- Competitive channels like Flipkart and Myntra also perform well in categories like Kurta and Saree, but their revenue is lower compared to Amazon.<br>

----

Question 9. What are the top 6 clothing sizes that generate the highest revenue?<br>

Graph:<br>

![Graph-9](https://github.com/user-attachments/assets/0a39e113-1abe-4c06-83e6-1b2b54a4699c)
<br>

Purpose of the Graph:<br>
- To identify the most revenue-contributing clothing sizes in the product range. This information can be used to optimize inventory management, marketing strategies, and production planning.<br>

Insights:<br>
- The sizes M, XL, and L seem to dominate the chart, indicating their higher popularity and contribution to revenue.<br>
- Smaller sizes like XS and S have a smaller proportion, suggesting lower demand in these categories.<br>
- Size XXL also has a notable contribution, showing that there is some demand for larger sizes, but not as much as medium or large sizes.<br>

----

Question 10. How do sales differ across various age groups (Adults, Teenagers, and Seniors)?<br>

Graph:<br>

![Graph-10](https://github.com/user-attachments/assets/337959d3-0990-4b25-89d9-541e97625465)
<br>

Purpose of the Graph:<br>
- To analyze and compare the contribution of different age groups to total sales. This information is valuable for targeting specific demographics in marketing and product development strategies.<br>

Insights:<br>
- Adults are the highest contributors to sales, with a total of 1,747,678, indicating that this age group is the most active or significant customer base.<br>
- Teenagers follow with 1,059,269, showing they also form a substantial portion of the market but not as dominant as adults.<br>
- Seniors, with 675,068, contribute the least to sales, suggesting lower purchasing power or less engagement with the product offerings.<br>
- The color coding (green, yellow, red) suggests predefined sales benchmarks, with all three groups falling below the highest threshold of performance (red zone).<br>
