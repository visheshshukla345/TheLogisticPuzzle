# The Logistics Puzzle: Optimizing Operations for Delightful Deliveries

## About
This project focuses on optimizing logistics operations to streamline processes, minimize costs, and maximize resource utilization. By examining various components such as warehouse management, transportation modes, and shipping strategies, the project aims to enhance the efficiency of logistics operations, ensuring timely delivery and maintaining high customer satisfaction.

## Project Overview
Efficient logistics operations are crucial for maintaining customer satisfaction and gaining a competitive advantage. This project, titled “The Logistics Puzzle: Optimizing Operations for Delightful Deliveries,” explores different aspects of logistics to improve operational efficiency and delivery performance. The study includes a comprehensive analysis of warehouse efficiency, transportation modes, and the impact of shipping discounts on customer satisfaction and sales performance.

## Objectives
1. **Analyze Warehouse Efficiency**: Investigate the impact of different warehouse block allocations on product storage patterns and operational efficiency.
2. **Evaluate Transportation Mode Effectiveness**: Examine how various transportation modes (sea, air, road) affect delivery performance and customer satisfaction.
3. **Optimize the Impact of Shipping Discounts**: Assess the effectiveness of shipping discounts on customer satisfaction and sales performance, particularly for high-priority products.

## Dataset Description
The dataset contains information on 10,999 observations with 12 variables. These variables include:
- **ID**: Unique identifier for customers
- **Warehouse_block**: Categorical variable indicating warehouse location
- **Mode_of_Shipment**: Categorical variable representing shipping methods
- **Customer_care_calls**: Numerical variable indicating the number of customer inquiries
- **Customer_rating**: Numerical variable indicating customer satisfaction levels
- **Cost_of_the_Product**: Numerical variable representing product cost in USD
- **Prior_purchases**: Numerical variable indicating the number of previous purchases
- **Product_importance**: Categorical variable indicating product importance level
- **Gender**: Categorical variable representing customer gender
- **Discount_offered**: Numerical variable indicating discount percentage
- **Weight_in_gms**: Numerical variable representing product weight in grams
- **Reached_on_Time_Y_N**: Binary target variable indicating on-time delivery (0 for on-time, 1 for delayed)

## Exploratory Data Analysis
### Summary for Numerical Variables
- **Customer Care Calls**: Range from 2 to 7 calls, with an average of 4.05 calls.
- **Cost of the Product**: Costs vary from 96 to 310 units, with a mean of 210.2 units.
- **Prior Purchases**: Range from 2 to 10, with a median of 3.
- **Discount Offered**: Discounts range from 1 to 65 units, with a mean of 13.37 units.
- **Weight in gms**: Weights range from 1001 to 7846 grams, with a mean of 3634 grams.

### Frequency Distribution for Categorical Variables
- **Warehouse Block**: Block F has the highest shipments (3666).
- **Customer Rating**: Mean rating close to 3.
- **Mode of Shipment**: Most shipments are made by ship (7462).
- **Product Importance**: Majority of products are of low importance (5297).
- **Gender**: Almost equal distribution with 5545 females and 5454 males.
- **Reached on Time**: 6563 shipments reached on time, while 4436 did not.

## Data Modeling
Several models were evaluated to address the study's objectives:
1. **Logistic Regression**
2. **Random Forest**
3. **Gradient Boosting**
4. **XGBoost**
5. **Decision Tree**
6. **Principal Component Analysis (PCA)**
7. **KMeans Clustering**

Performance metrics used include accuracy, sensitivity, specificity, precision, recall, F1 score, and area under the ROC curve.

## Key Findings
- **Warehouse Efficiency**: Efficient block allocations enhance logistics performance and delivery punctuality.
- **Transportation Modes**: Air transport is the fastest but most expensive; sea transport is cost-effective for bulk shipments; road transport is balanced for moderate distances.
- **Shipping Discounts**: Effective in boosting sales and customer satisfaction but need to be balanced to maintain profitability.

## Recommendations
1. **Optimize Storage in Block F**: Maximize efficiency and accessibility.
2. **Sea Freight for Large Quantities**: Manage large volumes and optimize shipping costs.
3. **Flexibility in Transportation Modes**: Ensure timely deliveries and manage customer expectations.
4. **Balance Costs and Customer Expectations**: Offer shipping discounts or incentives to encourage purchases.
5. **Reduce Customer Care Calls**: Improve delivery efficiency and timeliness.

## Conclusion
This project provides actionable insights for optimizing logistics operations, enhancing customer satisfaction, and achieving better business outcomes. Future research should focus on the dynamic aspects of logistics operations to further refine these strategies.

## Repository Contents
- **Project Report**: Detailed analysis and findings.
- **Presentation**: Summary of key points and visuals.
- **Code**: Scripts and notebooks used for data analysis and modeling.


