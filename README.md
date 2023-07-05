# Diwali_Sales_Analysis

## Overview of the Dataset Columns:

![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 00_36_00 (2)](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/2f0af7f1-5a7c-4f2b-ac9f-237cc3adb929)

The dataset contains information about customers, products, and their interactions during the Diwali sales period. It includes customer-related attributes such as demographics (gender, age, marital status, occupation), location (state, zone), and purchasing behavior (orders, amount). Additionally, the dataset includes details about the products purchased (product ID, category) and transaction status.

Analyzing this dataset can provide insights into customer preferences, sales performance, and the effectiveness of marketing strategies during the Diwali sales season.

## DATA IN THE DATASET

![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 00_36_00](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/c3ba35da-2216-450b-b707-5d90ff62145a)

## Data Cleaning Process:

1. **Removal of Missing Values:** 
   Missing values are deleted or filled with appropriate values to ensure data integrity and completeness.

2. **Changing Data Types:**
   Data types of columns are adjusted to ensure consistency and accuracy in the dataset.

3. **Handling Duplicates:**
   Duplicate records are identified and removed to prevent skewed analysis results.

4. **Data Transformation:**
   Additional transformations are performed to prepare the data for analysis and ensure its suitability for EDA.

   ## EDA

   **EDA Process: Gender Analysis by ORDERS**


![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 00_46_01](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/60fa2aef-1b0d-4602-815a-41879473d4d4)


As part of the exploratory data analysis (EDA), we performed an analysis of customer orders based on gender. We created a count plot to visualize the distribution of orders between males and females. The count plot revealed interesting insights about the gender-based purchasing behavior during the Diwali sales period.

The count plot showed that the number of orders placed by males was 3,407, while females placed 7,832 orders. This information provides an initial understanding of the gender-based sales distribution within the dataset.

By analyzing the count plot, we can draw several observations and potential implications:

1. **Gender Preference:** The count plot suggests that females had a higher number of orders compared to males. This could indicate that females may have been more active participants in the Diwali sales or had a higher inclination towards purchasing during this period.

2. **Targeted Marketing:** Understanding the gender distribution of orders can help retailers tailor their marketing strategies and promotions. By recognizing the higher number of orders placed by females, retailers can focus their marketing efforts towards this customer segment to maximize sales potential.

3. **Product Segmentation:** Analyzing the products associated with each gender group can provide insights into their preferences. By identifying the products favored by each gender, retailers can adjust their inventory and marketing strategies to cater to specific gender preferences, potentially increasing customer satisfaction and overall sales.

4. **Gender-Based Offers:** Based on the gender distribution of orders, retailers may consider designing gender-specific offers or discounts to further engage customers. This targeted approach can enhance customer experience and encourage repeat purchases.

It is important to note that this analysis provides initial insights into the gender-based order distribution. Further analysis and exploration of the dataset can uncover additional patterns and relationships between gender, product categories, and purchase amounts, providing a more comprehensive understanding of customer behavior during the Diwali sales.

Overall, the count plot by gender serves as a valuable starting point for understanding the role of gender in Diwali sales. It highlights the need for further exploration and emphasizes the importance of gender-based analysis in developing effective marketing strategies and optimizing sales performance.


## EDA Process: Gender Analysis by AMOUNT

![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 00_50_12](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/16b5ffc0-e279-4360-b74d-66609e1d9b0c)

As part of the exploratory data analysis (EDA), we analyzed the amount spent by customers based on their gender during the Diwali sales period. We created a count plot to visualize the distribution of the amount spent by males and females. The count plot revealed interesting insights about the gender-based purchasing behavior and the overall spending patterns.

According to the count plot, the total amount spent by males during the Diwali sales was 31,913,276, while females spent a total of 74,335,853. These figures provide an initial understanding of the gender-based spending distribution within the dataset.

## EDA Process: Age and Gender Analysis

![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 00_55_23](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/06d8653a-156c-433e-8b1d-db8dbd8801c8)



**Overview of Amount Spent by Age Group and Gender (in Rupees):**

- Age Group: 26-35
  - Females: 30,963,953
  - Males: 11,649,489

- Age Group: 36-45
  - Females: 15,509,956
  - Males: 6,635,038

- Age Group: 18-25
  - Females: 11,887,003
  - Males: 5,353,729

- Age Group: 46-50
  - Females: 6,743,393
  - Males: 2,464,451

- Age Group: 51-55
  - Females: 5,385,208
  - Males: 2,876,269

- Age Group: 55+
  - Females: 2,404,931
  - Males: 1,676,056

- Age Group: 0-17
  - Females: 1,441,409
  - Males: 1,258,244

The overview above summarizes the amount spent in Rupees by different age groups and genders during the Diwali sales. It provides a glimpse into the spending patterns observed in the dataset.

The analysis reveals variations in spending behavior based on age and gender. Females generally tend to have higher spending amounts compared to males in most age groups. This information can be valuable for retailers in understanding the purchasing preferences and behaviors of different customer segments.

By leveraging these insights, retailers can develop targeted marketing strategies, create personalized promotions, and optimize their product offerings to better cater to the specific needs and preferences of different age groups and genders.

## EDA Process: State-wise Analysis

![EDA on Diwali Sales - Jupyter Notebook - Google Chrome 06-07-2023 01_04_42](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/414109c0-a3cb-48ba-9ab5-fe1eb80d1e08)

As part of the exploratory data analysis (EDA), we analyzed the amount generated in rupees by different states during the Diwali sales period. We created a bar graph to visualize the distribution of the amount generated by each state.

The bar graph provides insights into the revenue generation across various states, revealing the following observations:

- Uttar Pradesh: The state of Uttar Pradesh generated the highest amount, totaling ₹19,374,968.

- Maharashtra: Maharashtra followed closely, with revenue amounting to ₹14,427,543.

- Karnataka: Karnataka generated a substantial amount of ₹13,523,540.

- Delhi: Revenue from the state of Delhi reached ₹11,603,818.

- Madhya Pradesh: Madhya Pradesh contributed ₹8,101,142 to the overall revenue.

- Andhra Pradesh: Andhra Pradesh generated ₹8,037,146 during the Diwali sales.

- Himachal Pradesh: Revenue from Himachal Pradesh reached ₹4,963,368.

- Haryana: Haryana contributed ₹4,220,175 to the overall revenue.

- Bihar: Bihar generated ₹4,022,757 during the Diwali sales.

- Gujarat: Revenue from Gujarat amounted to ₹3,946,082.

This analysis provides valuable insights into the revenue generated by different states during the Diwali sales. It indicates variations in consumer spending patterns and economic activity across regions.

Understanding the state-wise revenue generation can help retailers optimize their marketing strategies, focus on high-revenue regions, and tailor their offerings to meet the preferences and demands of specific states. It also highlights potential areas for expansion or improvement in states with lower revenue generation.


## EDA Process: Marital Status Analysis

![download](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/31e9154e-9ffd-443a-85f4-780fd624a2eb)


As part of the exploratory data analysis (EDA), we examined the amount spent based on marital status during the Diwali sales period. We created a bar chart to visualize the distribution of the amount spent by different marital statuses and genders.

The bar chart provides insights into the spending patterns based on marital status and gender, revealing the following observations:

- Marital Status: Married (0)
  - Females who were married spent a total amount of ₹43,786,646.
  - Males who were married spent a total amount of ₹18,338,738.



![download (1)](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/9474c894-c737-4522-86e7-740780a031ae)
- Marital Status: Unmarried (1)
  - Females who were unmarried spent a total amount of ₹30,549,207.
  - Males who were unmarried spent a total amount of ₹13,574,538.

These findings highlight the variations in spending behavior based on marital status and gender during the Diwali sales. It indicates that both married and unmarried individuals contribute significantly to the overall spending, with married females having the highest amount spent.

## EDA Process: Occupation Analysis


![download (1)](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/9474c894-c737-4522-86e7-740780a031ae)

As part of the exploratory data analysis (EDA), we analyzed the amount spent by customers based on their occupations during the Diwali sales period. We created a bar graph to visualize the distribution of the amount spent across different occupations.

The bar graph provides insights into the spending patterns based on occupations, revealing the following observations:

- Occupation: IT Sector
  - Customers working in the IT Sector spent a total amount of ₹14,755,079.

- Occupation: Healthcare
  - Customers in the Healthcare sector spent ₹13,034,586 during the Diwali sales.

- Occupation: Aviation
  - Customers in the Aviation industry spent ₹12,602,298.

- Occupation: Banking
  - Customers working in the Banking sector contributed ₹10,770,610 to the overall spending.

- Occupation: Govt (Government)
  - Customers employed in Government roles spent ₹8,517,212 during the Diwali sales.

- Occupation: Hospitality
  - Customers in the Hospitality industry spent a total amount of ₹6,376,405.

- Occupation: Media
  - Customers working in the Media sector spent ₹6,295,832.

- Occupation: Automobile
  - Customers in the Automobile industry contributed ₹5,368,596 to the overall spending.

- Occupation: Chemical
  - Customers working in the Chemical sector spent ₹5,297,436.

- Occupation: Lawyer
  - Customers working as Lawyers spent ₹4,981,665 during the Diwali sales.

- Occupation: Retail
  - Customers in the Retail sector spent ₹4,783,170.

- Occupation: Food Processing
  - Customers working in the Food Processing industry spent ₹4,070,670.

- Occupation: Construction
  - Customers in the Construction sector contributed ₹3,597,511 to the overall spending.

- Occupation: Textile
  - Customers working in the Textile industry spent ₹3,204,972.

- Occupation: Agriculture
  - Customers in the Agriculture sector spent ₹2,593,087.

This analysis provides valuable insights into the amount spent by customers across various occupations during the Diwali sales. It highlights variations in spending behavior based on different professional fields.

It is important to note that this analysis provides a snapshot of the spending patterns during the Diwali sales based on occupations. Further exploration of the dataset, considering additional variables such as age, gender, or location, can uncover more nuanced insights and contribute to a comprehensive understanding of customer behavior.

## EDA Process: Product Category Analysis

![download (2)](https://github.com/himanshurawat2003/SuperStoreAnalysis-/assets/113167021/fb72a105-05bb-45b8-8854-be245aabf3fb)

As part of the exploratory data analysis (EDA), we examined the amount generated by different product categories during the Diwali sales period. We created a bar graph to visualize the distribution of the amount generated across various product categories.

The bar graph provides insights into the revenue generation by different product categories, revealing the following observations:

- Product Category: Food
  - The Food category generated the highest amount, totaling ₹33,933,883.

- Product Category: Clothing & Apparel
  - Revenue from Clothing & Apparel amounted to ₹16,495,019.

- Product Category: Electronics & Gadgets
  - Electronics & Gadgets contributed ₹15,643,846 to the overall revenue.

- Product Category: Footwear & Shoes
  - Revenue from Footwear & Shoes reached ₹15,575,209.

- Product Category: Furniture
  - The Furniture category generated ₹5,440,051.

- Product Category: Games & Toys
  - Revenue from Games & Toys amounted to ₹4,331,694.

- Product Category: Sports Products
  - The Sports Products category contributed ₹3,635,933 to the overall revenue.

- Product Category: Beauty
  - Revenue from the Beauty category reached ₹1,959,484.

- Product Category: Auto
  - The Auto category generated ₹1,958,609.

- Product Category: Stationery
  - Revenue from Stationery amounted to ₹1,676,051.

This analysis provides valuable insights into the revenue generation by different product categories during the Diwali sales. It highlights the popularity and revenue potential of specific product categories, with Food being the highest revenue generator.

Understanding the revenue generation by product categories can help retailers optimize their marketing strategies, focus on high-revenue categories, and tailor their product offerings to meet the preferences and demands of customers. It also helps in identifying potential areas for expansion or improvement within specific product categories.

## RECOMMENDATIONS :-
Based on the insights gained from the previous data analysis of Diwali sales, we provide the following recommendations for business growth:

1. **Targeted Marketing:** Utilize the insights from gender analysis to develop targeted marketing strategies. Design promotions and campaigns tailored to specific gender segments, considering their preferences and spending patterns. This can lead to increased customer engagement and higher sales.

2. **Product Optimization:** Analyze the product categories and their revenue generation to identify popular and high-potential areas. Focus on optimizing product offerings within these categories, ensuring a diverse range of options to meet customer demands and preferences.

3. **Customer Segmentation:** Leverage customer segmentation based on age, gender, marital status, and occupation to personalize marketing efforts. Develop tailored offers, discounts, and promotions for different customer segments, ensuring a personalized experience that enhances customer satisfaction and loyalty.

4. **Regional Focus:** Consider the revenue generated by different states during the Diwali sales. Identify regions with high revenue generation and allocate resources to target these areas more effectively. This can include localized marketing campaigns, partnerships with local businesses, and region-specific promotions.

5. **Enhanced Customer Experience:** Use the insights gained from the analysis to improve the overall customer experience. Focus on customer satisfaction, personalized recommendations, and efficient customer support. Providing exceptional service can drive customer loyalty and encourage repeat business.

6. **Inventory Management:** Optimize inventory management based on popular product categories and customer preferences. Analyze the sales performance of different products and adjust the inventory accordingly to ensure sufficient stock availability of in-demand items.

7. **Continuous Analysis:** EDA is an ongoing process. Continuously monitor and analyze data to identify changing trends, emerging customer preferences, and evolving market dynamics. This will enable businesses to adapt quickly, make informed decisions, and stay ahead of the competition.

8. **Partnerships and Collaborations:** Explore partnerships or collaborations with other businesses or influencers to expand reach and attract new customers. Joint promotions or cross-selling opportunities can provide mutual benefits and boost sales.

9. **Predictive Analytics:** Incorporate advanced statistical modeling and predictive analytics to forecast future sales trends. This can help in anticipating customer demands, optimizing inventory management, and making proactive business decisions.

10. **Customer Feedback and Surveys:** Collect customer feedback and conduct surveys to gather insights into customer satisfaction, preferences, and areas for improvement. Utilize this feedback to refine marketing strategies, enhance product offerings, and address any pain points.

By implementing these recommendations, businesses can optimize their strategies, enhance customer satisfaction, and drive business growth during the Diwali sales and beyond. It is important to adapt these recommendations based on the specific business context and continuously monitor and evaluate the outcomes to make data-driven decisions for sustained success.
