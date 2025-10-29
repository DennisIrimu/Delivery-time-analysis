# Delivery time analysis Predictive Model
# Business Context

In modern supply chains, delays in shipment delivery affect costs, customer satisfaction, and overall operational efficiency.
By predicting shipment delays in advance, logistics providers can allocate resources more efficiently and proactively address issues before they escalate.

### Business Problem Statement

The company wants to predict whether a shipment will be delayed or on-time using historical logistics data.

### Objective

Build a classification model that predicts shipment delay based on available operational data (e.g., shipment mode, origin/destination, weight, carrier type, etc.).

### Success Metric
	•	Primary metric: Accuracy (to gauge general performance)
	•	Secondary metrics: Precision, Recall, and F1-score (especially if classes are imbalanced)
	•	Business metric: Reduction in average delay and proactive mitigation of risk

### About data used

https://www.kaggle.com/datasets/prachi13/customer-analytics

#### Context
An international e-commerce company based wants to discover key insights from their customer database. They want to use some of the most advanced machine learning techniques to study their customers. The company sells electronic products.

#### Content
The dataset used for model building contained 10999 observations of 12 variables.
The data contains the following information:

ID: ID Number of Customers.
Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,E.
Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.
Customer care calls: The number of calls made from enquiry for enquiry of the shipment.
Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).
Cost of the product: Cost of the Product in US Dollars.
Prior purchases: The Number of Prior Purchase.
Product importance: The company has categorized the product in the various parameter such as low, medium, high.
Gender: Male and Female.
Discount offered: Discount offered on that specific product.
Weight in gms: It is the weight in grams.
Reached on time: It is the target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.

#### Acknowledgements
I would like to specify that I am only making available on Github in Data collected data about product shipment to Kagglers. I made this as my project on Customer Analytics stored in GitHub repository.

#### Inspiration
This data of Product Shipment Tracking, answer instantly to your questions:

1. What was Customer Rating? And was the product delivered on time?
2. Is Customer query is being answered?
3. If Product importance is high. having higest rating or being delivered on time?
