# Fiber-Internet-Project

This is the Business Intelligence project I did after taking the BI professional certificate. Specifically, it broke down into three phases corresponding with 3 courses to complete this project:
* The 1st phase is to complete the BI documents, which include **stakeholders' requirements, project requirements, and strategy requirements**
    * **Stakeholders document** enables capturing stakeholder requests and requirements to understand their needs before planning the rest of the project details or strategy 
    * **Project document** contains the following: purpose, stakeholder requirements, success criteria, etc.
    * **Strategy document** deals with approaching the data and getting feedback from the stakeholders
* The 2nd phase is to **consolidate** the data from **multiple sources into a target table** by using SQL and **load** it into the unified destination (Tableau in this project)
* The final phase is to create the **dashboard, and the **slide-deck presentation** to present the insights to the stakeholders (here is the Tableau workbook: https://public.tableau.com/app/profile/viet.pham4981/viz/Fiber_/Google_Fiber_Project)

#### Here is the scenario: 

You are interviewing for a job with Google Fiber, which provides people and businesses with fiber optic internet. As part of the interview process, the Fiber customer service team has asked you to design a dashboard using fictional data. The position you are interviewing for is in the customer call center, where Fiber uses business intelligence to monitor and improve customer satisfaction.

The team needs to understand how often customers  phone customer support again after their first inquiry; this will help leaders understand whether the team is able to answer customer questions the first time. Further, leaders want to explore trends in repeat calls to identify why customers are having to call more than once, as well as how to improve the overall customer experience.

This fictional dataset is a version of actual data the team works with. Because of this, the data is already anonymized and approved. It includes:
* Number of calls
* Number of repeat calls after first contact
* Call type
* Market city
* Date

Specifically, the dashboard will provide insights with the following: 
* Understand how often customers are calling customer support after their first inquiry; this will help leaders understand how effectively the team is able to answer customer questions the first time
* Provide insights into the types of customer issues that seem to generate more repeat calls
* Explore repeat caller trends in the three different market cities
* Design charts so that stakeholders can view trends by week, month, quarter, and year.

The team’s ultimate goal is to reduce call volume by increasing customer satisfaction and improving operational optimization.

In order to anonymize and fictionalize the data, the datasets the columns market_1, market_2, and market_3 to indicate three different city service areas the data represents. 

The data also lists five problem types:
* Type_1 is account management
* Type_2 is technician troubleshooting
* Type_3 is scheduling
* Type_4 is construction
* Type_5 is internet and wifi

Additionally, the dataset records repeat calls over seven-day periods. The initial contact date is listed as contacts_n. The other call columns are then contacts_n_number of days since first call. For example, contacts_n_6 indicates six days since first contact. 
