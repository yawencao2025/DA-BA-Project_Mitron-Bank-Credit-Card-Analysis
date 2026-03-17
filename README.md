# Mitron Bank: Analysis for New Credit Card Launch
## Created by Yawen Cao [Linkeldin Profile](https://www.linkedin.com/in/yawen-cao-306975337/)
### Live Dashboard at Tableau Public [Live_link_Tableau_Public](https://public.tableau.com/views/BankData_dashboard/DemographicAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


#
## Table of Content
1. [About Mitron Bank](#about-mitron-bank)
2. [Objective of the Project](#objective-of-the-project)
3. [Problem Statment](#problem-statment)
4. [Demographic Classification](#demographic-classification)
5. [Income Utilization & Spending Analysis](#income-utilization--spending-analysis)
7. [Recomendation](#recomendation-for-next-credit-card)

#
### About Mitron Bank 
Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

### Objective of the Project 
This project serves as a pilot for Mitron Bank’s credit card expansion. It analyzes the provided sample data and delivers actionable insights to the strategy team, helping them tailor credit card offerings to customer needs and market trends to increase market share.

### Problem Statment   

 * **Demographic classification:** Segment customers based on demographic attributes such as age group, gender, occupation, and city to uncover meaningful patterns in their financial behavior.
   
 * **Avg income utilisation %:** Calculate the average income utilization percentage (avg_spends / avg_income), a key metric indicating the likelihood of credit card usage—higher utilization suggests a greater propensity to adopt and use credit cards.
   
 * **Spending Insights:** Analyze where customers spend the most and examine how spending varies across demographics (occupation, gender, city, age). These insights can inform targeted offers, such as specialized rewards for specific purchase categories or demographic groups.

 * **Key Customer Segments:** Identify and profile high-value customer segments most likely to adopt the new credit cards by exploring their demographic characteristics, spending habits, and financial preferences.

 * **Credit Card Feature Recommendations:** Recommend key credit card features that would increase customer adoption and usage, based on observed behaviors and segment-specific needs.
#

## Demographic Classification:   
For demographic classification, a thorough customer demographic analysis was conducted using Tableau, and here are key findings presented in a visually engaging manner:

![Customer_Demographic_All](images/Customer_Demographic_All.png)

### Total Customers:

* The dataset includes a sample of 4,000 customers, which serves as the solid foundation of our analysis.

### Gender Segmentation:

<img src="images/Gender_Segmentation.png" width="250" alt="Gender Segmentation">

* The total of 4000 customers includes 2597 males (64.93%) and 1403 females (35.08%), indicating a slightly male-dominated demographic. 

### Age Group Profiling: 

<img src="images/Age_Group.png" width="500" alt="Age_Group">

* Primary Target Segment: The age group 23-36 emerges as our largest and most significant custoemr segment, with 1948 customers. This group, especially males, exhibits the strong presence (73.3%). The strategy team should prioritize developing and marketing cards with features that appeal to young and mid-career career male professionals(e.g., rewards on tech, dining, travel, or fitness). 

* Secondary Target Group: The 35-45 age group is another key demographic, comprising 1273 individuals. This demographic is likely entering peak earning years, making it ideal for premium cards, balance transfer offers, or family-oriented benefits (e.g., enhanced travel insurance, educational expense tracking). 

* Balanced Niche Segment: Customer aged 21-24 and 45+ are smaller but exhbit relatively balanced gender distribution. This presents an opportunity for niche, university positioned products. For the younger group, consider starter cards with credit-builiding features. For 45+ group, focus on secruity, legacy benefits, and retirement lifestyle perks. 

### City-wise distribution:
<img src="images/City_Segmentation.png" width="500" alt="City_Segmentation">

* Core Market (Mumbai): Our leadig hub with 1078 customers, showing a pronounced male skew. 

* Secondary Hubs (Chennai, Banglore, Delhi NCR): Significant contributor to our customer base, each also demonstrating a male-skewed demographic. 

### Occupation Insight:
<img src="images/Occupation_Insight.png" width="500" alt="Occupation_Insight">

 * Salaried IT Employees represent our largest portion of our customer base (1294 cutsomers), this tech-centric base skews male(+148), confirming a strong initial foothold in this high-income demographic. This is our prime audience for aggresive cross-selling of premium cards with tech-focused perks, travel benefits and partner offers. 
 
 * The diversity in occupations, inlcuding freelancers and busines owners, presents an opportunity to tailor services for varied professional needs, such as unique cash flow and expense management needs. 

 ### Marital Status Summary:
 <img src="images/Marital_Status.png" width="250" alt="Marital_Status">

* Dominant Segment – Married Customers: The vast majority of our base is married (3,136 | 78.4%), underscoring a core demand for family-oriented financial products and joint account features.

* Growth Opportunity – Single Customers: The substantial single segment presents a clear opportunity to capture new market share by designing convenient, lifestyle-focused rewards tailored to individual spending habits.
 
## Income Utilization & Spend Analysis 
To understand customer spending patterns and income utilization across demographic segments, we conducted a dedicated analytical study. The analysis leverages six months of historical spending and income data (May–October), providing a robust foundation for identifying trends.

These findings are synthesized in a custom-built "Customer Spend Analysis" dashboard in Tableau. This interactive dashboard serves as the central hub for exploration, presenting key performance indicators (KPIs) and visualizations that reveal critical insights into spending behavior and financial allocation across the customer base.

![Customer_Spend_Analysis](images/Customer_Spend_Analysis.png)

### Average Income Utilization

<img src="images/Average_Income_Utilization.png" style="width:200px;" alt="Average_Income_Utilization">

* Average Income Utilization (AIU) is calculated by avg_monthly_spends/avg_monthly_income. The higher the average income utilisation %, the more is their likelihood to use credit cards.
* our analysis shows that, on average, customers allocate 42.95% of their monthly income to expenditures in average. 

### Key Metrics: 

<img src="images/Average_Spend_Income.png" style="width:250px;" alt="Average_Spend_Income">

* Average Monthly Income for 6 months: 51.66K
* Average Monthly Spend for 6 monthds: 22.12K

### Average Income, Spend, Utilization by Age Group

<img src="images/AIU_Age_Group.png" style="width:500px;" alt="AIU_Age_Group">


* Age group 35-45 shows the highest average income utilization rate (46.6%). 
* A second-highest is 25-34 age group, with a utilization rate of 43.8%. 
* On average, people spend less after 45 even their average monthly income rise. 

### Average Income, Spend, Utilization by Occupations
<img src="images/AIU_occupations.png" style="width:500px;" alt="AIU_Occupation">


* Salaried IT employees have the highest average inocme utilization rate (50.9%), followed by freelancers (45.7%). 
* Although freelancers have quite noticing AIU, it has relative low average monthly income. On the other hands, business owners has relative lower AIU but they earn most average monthly income, which showing big potentials market. 

### Average Income, Spend, Utilization by City 

<img src="images/AIU_city.png" style="width:500px;" alt="AIU_City">

* The average monthly income differences among these cities are minimal (about 1K difference), Delhi DCR and Hyderabad have slightly higher income compared to other cities.
* Mumbai outstands from other cities, with the highest AIU (51.6%), followed by Delhi NCR (48.1%). Customer in these two cities spend nearly half of their income, indicating a stornger consumption behavior. 
* The high AIU may due to Mumbai and Delhi NCR have higher living costs and more lifestyle consumptions compared to other cities. Therefore, there's higher potential for credit card usage compared to higher saving behavior in other cities. 

💼 Higher AIU is driven by higher spending, not higher income. 

### Total Spend by Month

<img src="images/Total_Spend_Month.png" style="width:500px;" alt="Total_Spend_Month">

* Looking at the trend, the total spend gradually rises from May to September and reaches the peak in
September, accounting for $115.9M, constituting 21.84% of total spend. Then, it drops back to $86M in October. 

If we take a closer look at the total spend on each product category for each month: 

<img src="images/Total_Spend_Month_Product.png" style="width:500px;" alt="Total_Spend_Month_Product">


* We could find the people spend more money on bills, electronics, groceries and travels on Auguest and September. This might be August-September is peak monsoon season in many Indian cities. People tend to stay indoors more, leading to higher utility bills. 

* Also, before major festivals, people may start prepare their homes, and increase usage of some services. 

💼 This seasonal spikes suggest opportunnities for targeted promotions (bills, electronics, groceries and travel) during Auguest-September. 

### Total Spend by Product Category and Age Group 

![Total_Spend_Product_Age](images/Total_Spend_Product_Age.png)

* Bills take part the highest spending than other categories ($104.92M), constituting 19.8% of total spending. 
* Although we have an imbalanced age group distribution, we can find age group 21-24 spends most money on Entertainment, Electronics and Apparel. People in the 25-34 age group start building family that's why bills, groceries become the highest spending in this age group. In the 35-45 age group, people start invest more on health and wellness. Bills, groceries and health&travel are still the primary spendings for age group 45+. 


### Total Spend by Payment Mode and Product Category

![Total_Spend_Payment_Mode](images/Total_Spend_Payment_Mode.png)
* The majority of transactions are made through credit cards, which account for 40.7% of total spend, followed by cash (26.5%) and credit cards (22.5%), likely due to benefits like rewards, EMI options and deferred payments.

![Total_Spend_Payment_Mode_Product_Category](images/Total_Spend_Payment_Mode_Product_Category.png)
* Credit cards are the preferred payment method for high-value or recurrring expenses, such as bills, electronics, health and wellness, and travel. 
* UPI is primarily used for frequent, lower-to-mid value transcations, especially daily essentials such as grocery and food. 


## ⭐️ Key Findings

1. Demographic profiling: 

***Gender insights***

Males are the dominant segment of our customer segments with higher total income and spend compared to females. They have higher AIU (44.73%) than female counterpart (39.64%), inidicating they are targetd customer segment for the new credit card offerings. 

***Age insights***

The age group 25-34 and 35-45 are the most significant segment, demonstrating high income utilization of 43.8% and 46.6% respectively. 

Even age group 25-34 has slightly lower AIU than age group 35-45, they are the most major credit card user, 46.6% of their transaction are paid through credit cards. 

***Occupation insights***

Salaried IT emloyee, freelancers, and salaried other employees are potential high-value users with 50.9%, 45.7%, 42.0% AIU, respectively. Particularly, only 41% of Salaried IT Employee's transactions are from credit cards, with the high income and AIU of this segment, it shows huge potential to attract more customers using credit cards from Salaried IT employee segment. 

Although Freelancers have relative high AIU, credit card is not their preferred transaction method, with only 34.4% of their transaction through credit card. Salraied other employees can also be our targeted customers for new credit cards, they have higher AIU, willing to pay through credict card as 42.4% of their transaction from credit card. Based on their mid-level average monthly income, the rewards for opening new account could be attractive for them. 

2. City-wise consideration: 

***Mumbai and Delhi NCR*** are the most promising markets for credit card expansion, with the highest AIU (51.6% and 48.1%, respectively) and a strong preference for credit card payments. No significant difference of preferrred payment method between cities was found, around 40% of transactions are from credit cards from all cities. 

We can tailor features to align with the spending patterns of customers in specific cities for captusring high-value users. 


## 📌 Recomendation for next credit card

### Personalized rewards: 
* Offer cashback, points for every transaction, encouraing users to use the credit card for every expenses. 
* Provide higher credit limits to accomodate the spending patterns and financial capacity of the target users. 
* Design tiered rewards programs to incentivize higher spending and reward loyal customers.

### Category-centric reward boost: 
* Build strategic partnerships with renowned brands, offer cardholders exclusive discounts, early accesss to sales. Partner with utility companies to offer exclusive discounts or cash back for bill payments made with credit cards. 
* Increase the seasonal rewards and benefits during August-September to facilitate purchase through credit cards. 
* Extend the warranty on electronic purchases made with the credit card and offer purchase protection. 

### Tech-driven convenience: 
Targeted segmentment (Salaried IT employee and salaried other employee) features: 
* Introduce specific rewards aligh with IT professional's spending patterns such as technology purchases, software subscriptions and online services (Claude, chatgpt subscription). 
* Introduce travel-related perks like airport lounge access, travel insurances and discounts on flights or hotel bookings.
* Provide an extended intrest-fee grace period, partucilary for business-related expenses, for start-up, giving users more time to settle payments.

### Improve the convience of credit card usage situation:
* Link the credit cards purchase with UPI for quick and convenient transactions for widespread useage. 
* Implement a swift and efficient approval process for credit card applications to encourage users to adopt the credit card withough unnessary delays.


---------------------
Created by Yawen Cao

Date: 03/17/2026

Base: Austin, TX












