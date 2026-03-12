

# Problem Statement
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodra. They want to expand to other metro/tier1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend the annual contract due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers on a daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’ and OnTime in full (OTIF) % of the customer orders on a daily basis against the target service level set for each customer.

## Task  
As the data analyst in the supply chain team who joined Atliq Mart recently. You have been briefed about the the task in the stakeholder business review meeting. Now Imagine yourself play the role of the new data analyst who is excited to build this dashboard and perform the following task

1.Create the metrics according to the metrics list.

2.Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in the form of a comic.

3.Create relevant insights that are not provided in the metric list/stakeholder meeting
 
## **Datasource**
The data, metrics list, domain concepts, business stakeholder meetings can all be sourced on codebasics.io

## Data Cleaning and Transformation
To perform this task, the process involved were:

1.Importing data as a CSV file and creating a data model from scratch to link the tables 

![Data Model](https://github.com/Hussainsyedarshad/Atliq_mart-Supply-Chain-Analysis/blob/main/Screenshot%20(177).png)
                    **power BI Data Modeling**

2. Using the appropriate data types and creating calculated columns to aid in providing more insights

3. Creating Measures & calculations using DAX to track requested metrics, like;

    a. DOT% - Delivery on Time
    
    b. DIF% - Delivery in Full
    
    c. OTIF% - On Time In Full
    
    d. Total orders and Total Orderlines
    
    e. LIFR% - Line Fill Rate
    
    f. VOFR% - Volume Fill Rate
    
    g. Delivery Days, etc
    
 4. Creating tooltips and visuals using appropriate charts to communicate findings

## Some Major Insights 

- All the Key Metrics (OT%, IF%, OTIF%) are far behind the target
- On an average, orders are delayed 0.42 days from the agreed date of delivery
- Lotus Mart, Coolblue, Acclaimed stores have the highest orders as well as delayed the most to deliver the products on time 
  - Is it because we are not estimating the right delivery date?
  - Is it because we are receiving more orders than expected?
- Ghee, curd and butter products are most delayed to deliver. 
- There is no noticeable improvements in any of the key metrics in the last few months
- There is a huge gap in IF% for most of the customers. Is it because of less production?


## **Insights**
[![Power_BI REPORT]
(https://github.com/Hussainsyedarshad/Atliq_mart-Supply-Chain-Analysis/blob/main/Screenshot%202026-03-12%20161359.png) 
(https://github.com/Hussainsyedarshad/Atliq_mart-Supply-Chain-Analysis/blob/main/AtilQ%20Mart%20(1).pbix)

click to view power BI dashboard
