# Olist Ecommerce Analysis
### Project Overview:

This GitHub repository contains the code and documentation for an Ecommerce Insights project. The primary goal of this project is to analyze key performance indicators (KPIs) to identify areas for improvement in sales, customer satisfaction, and overall business performance.

## Data
OLIST is a Brazilian Ecommerce Marketplace.

I have the data of three years (2016,2017,2018) which shows us that OLIST has almost 1 lakhs no of orders.

The given data contains 9 tables each table contains 10 Lakhs of records.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Null values and blank values has been remove as per requirement.
- Step 5 : Create custom columns
- Step 6 : Load only the required data from power query editor.


## Problem Statements:

![Olist_Ecom_KPI_page-0001](https://github.com/AnasAhmed91/Ecommerce_Analysis/assets/156163917/62188c58-3a47-411f-99ff-d1992afeb218)


### Weekday vs. Weekend Sales Discrepancy:

- Problem: Uneven distribution of sales between weekdays and weekends.
- Solution: Implement targeted marketing campaigns during peak weekday hours and exclusive promotions to maximize weekend sales.

### Number of Orders - Review Score & Credit Card Payments:

- Problem: Correlation between low review scores and specific payment types.
- Solution: Introduction of loyalty programs and targeted marketing for customers using credit cards.

### Average Delivery Days for pet_shop:

- Problem: Average delivery time is 11 days.
- Solution: Optimize the supply chain, improve logistics, and enhance communication for faster and more efficient deliveries.

### Average Price & Payment Values - São Paulo:

- Problem: Limited insight into customer spending patterns in São Paulo.
- Solution: Tailor marketing strategies to align with average price (112) and payment values (140) in São Paulo. Introduce localized promotions.

### Shipping Days vs. Review Scores:

- Problem: Longer delivery times associated with lower review scores.
- Solution: Optimize logistics, improve communication, and focus on prompt deliveries.



### Low Rating Analysis:

![low rating analysis_page-0001](https://github.com/AnasAhmed91/Ecommerce_Analysis/assets/156163917/6039f8d3-95a9-4fd7-b5ea-583f91437a2e)

- Problem: An analysis of low ratings is needed to understand common pain points.
- After analyzing customer feedbacks, the top 5 reasons for low ratings are 
1. Product not deliver on time.
2. No Feedback Given.
3. Product not recieved as per ordered.
4. Quality related complaints.
5. Defective products.

    1. Product Not Delivered on Time:
Solution:
Implement a robust logistics and fulfillment strategy to ensure timely deliveries.
Utilize advanced tracking systems for real-time monitoring and communication with customers.
Set clear delivery expectations during the ordering process.
    
2. No Feedback Given:
Solution:
Implement a follow-up email system to remind customers to share their experiences.
Ensure a user-friendly and accessible platform for leaving reviews.

3. Product Not Received as Ordered:
Solution:
Strengthen quality checks and inspection procedures before shipping.
Improve accuracy in order fulfillment by cross-verifying product details.
Implement a customer-friendly return and exchange policy.

4. Quality Related Complaints:
Solution:
Enhance product quality control measures during manufacturing and storage.
Regularly solicit and incorporate customer feedback into product improvement processes.
Offer refunds or replacements for products that do not meet quality expectations.

5. Defective Products:
Solution:
Strengthen quality assurance procedures at all stages of production.
Implement rigorous testing protocols to identify and rectify defects before products reach customers.
Streamline the return process for defective products and offer prompt replacements.




### Product Not Delivered on Time:
![Product not delivered on time Analysis_page-0001](https://github.com/AnasAhmed91/Ecommerce_Analysis/assets/156163917/86ba3c8e-c17c-49d8-90ae-2f2066ae7921)

- Problem: Instances of products not being delivered within the expected timeframes.

- Average delivery days for all the observed sellers is 5 to 15 working days, And they show a consistent delay count in all months except in the month of November 2017.
by analyzing the trends we found that the unexpected delay in November month can possiblly by - 
1. Transportation strike / Post office strike/ Negligence by post office.
2. Increase in orders in November might have caused stock unavailability.

    Solution: Streamline the supply chain, optimize fulfillment processes, and improve communication to ensure timely deliveries, and having its own established Delivery agencies. Example : Amazon

    Contributions:
Contributions are welcome! Feel free to fork the repository, make improvements, and create pull requests. If you identify additional problem statements or have suggestions for solutions, please share them through the issue tracker.

Happy analyzing and improving our ecommerce operations! 🚀✨
