# Capstone-Project-Module-2-Airline-Passenger-Satisfaction-Analysis

Skip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@NJT09 
NJT09
/
Purwadhika
Public
Cannot fork because you own this repository and are not a member of any organizations.
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Purwadhika/Capstone_Project_2_README
@NJT09
NJT09 Rename README.md to Capstone_Project_2_README
Latest commit 4c7cc43 3 weeks ago
 History
 1 contributor
166 lines (131 sloc)  13.2 KB

# Background
An airline company is recruiting data scientists. This company has conducted survey to find out the customer satisfaction towards their services. According to the survey, there are some customers who are satisfied, but there are also customers who are not satisfied with the services provided by the airline company.

## Research Question
The airline company wants to know **what are the factors that affect customer satisfaction level**. This information will help the company to improve, revise, or even rehaul their services if needed.

As a data analyst, I am going to try to answer the following question:

**Which factors affect customer satisfaction level? Is there any service that need to be further investigated?**

# Data
To answer above-mentioned question, I will analyze the customer satisfaction data that has been collected by the company. You can access the dataset [here](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction). 

This dataset contains an airline passenger satisfaction survey. There are 24 columns inside dataset 'airline passanger satisfaction', which are:

1. __Id__: Unique ID for each passenger<br>
2. __Gender__: Gender of the passenger (Female, Male)<br>
3. __Customer Type__: Types of customer (loyal customer, disloyal customer)<br>
4. __Age__: The actual age of the passenger<br>
5. __Type of Travel__: Purpose of the flight of the passengers (Personal Travel, Business Travel)<br>
6. __Class__: Travel class in the plane of the passengers (Business, Eco, Eco Plus)<br>
7. __Flight Distance__: The flight distance of this journey<br>
8. __Inflight Wifi Service__: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)<br>
9. __Departure/Arrival Time Convenient__: Satisfaction level of departure/arrival time convenient<br>
10. __Ease of Online booking__: Satisfaction level of online booking<br>
11. __Gate Location__: Satisfaction level of gate location<br>
12. __Food and Drink__: Satisfaction level of food and drink<br>
13. __Online Boarding__: Satisfaction level of online boarding<br>
14. __Seat Comfort__: Satisfaction level of seat comfort<br>
15. __Inflight Entertainment__: Satisfaction level of inflight entertainment<br>
16. __On-board Service__: Satisfaction level of On-board service<br>
17. __Leg Room Service__: Satisfaction level of Leg room service<br>
18. __Baggage Handling__: Satisfaction level of baggage handling<br>
19. __Checkin Service__: Satisfaction level of Check-in service<br>
20. __Inflight Service__: Satisfaction level of inflight service<br>
21. __Cleanliness__: Satisfaction level of Cleanliness<br>
22. __Departure Delay in Minutes__: Minutes delayed upon departure<br>
23. __Arrival Delay in Minutes__: Minutes delayed upon Arrival<br>
24. __Satisfaction__: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)<br>


# Data Analysis
**The analysis will be done by comparing survey rating data to find out which factors have significant effect on the customer satisfaction level.**

We have done data cleaning step. Now, we can start the data analysis process to figure out **Which factors affect customer satisfaction level? Is there any service that need to be further investigated?**.

Hypothesis:

- H0: Mean of numerical categories for satisfied customer = Mean of numerical categories for unsatisfied customer
- Ha: Mean of numerical categories for satisfied customer ≠ Mean of numerical categories for unsatisfied customer

1. The pvalue of "Age" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Age" for satisfied customer is significantly different than the Mean of "Age" for unsatisfied customer
        
2. The pvalue of "Flight Distance" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Flight Distance" for satisfied customer is significantly different than the Mean of "Flight Distance" for unsatisfied customer
        
3. The pvalue of "Inflight Wifi Service" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Inflight Wifi Service" for satisfied customer is significantly different than the Mean of "Inflight Wifi Service" for unsatisfied customer
        
4. The pvalue of "Departure/Arrival Time Convenient" = 1.3891233588756137e-52. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Departure/Arrival Time Convenient" for satisfied customer is significantly different than the Mean of "Departure/Arrival Time Convenient" for unsatisfied customer
        
5. The pvalue of "Ease Of Online Booking" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Ease Of Online Booking" for satisfied customer is significantly different than the Mean of "Ease Of Online Booking" for unsatisfied customer
        
6. The pvalue of "Gate Location" = 0.9695541106460981. pvalue > 0.05. Failed to reject Ho. 
        We DO NOT have enough proof that the Mean of "Gate Location" for satisfied customer is significantly different than the Mean of "Gate Location" for unsatisfied customer
        
7. The pvalue of "Food And Drink" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Food And Drink" for satisfied customer is significantly different than the Mean of "Food And Drink" for unsatisfied customer
        
8. The pvalue of "Online Boarding" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Online Boarding" for satisfied customer is significantly different than the Mean of "Online Boarding" for unsatisfied customer
        
9. The pvalue of "Seat Comfort" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Seat Comfort" for satisfied customer is significantly different than the Mean of "Seat Comfort" for unsatisfied customer
        
10. The pvalue of "Inflight Entertainment" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Inflight Entertainment" for satisfied customer is significantly different than the Mean of "Inflight Entertainment" for unsatisfied customer
        
11. The pvalue of "Onboard Service" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Onboard Service" for satisfied customer is significantly different than the Mean of "Onboard Service" for unsatisfied customer
        
12. The pvalue of "Leg Room Service" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Leg Room Service" for satisfied customer is significantly different than the Mean of "Leg Room Service" for unsatisfied customer
        
13. The pvalue of "Baggage Handling" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Baggage Handling" for satisfied customer is significantly different than the Mean of "Baggage Handling" for unsatisfied customer
        
14. The pvalue of "Checkin Service" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Checkin Service" for satisfied customer is significantly different than the Mean of "Checkin Service" for unsatisfied customer
        
15. The pvalue of "Inflight Service" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Inflight Service" for satisfied customer is significantly different than the Mean of "Inflight Service" for unsatisfied customer
        
16. The pvalue of "Cleanliness" = 0.0. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Cleanliness" for satisfied customer is significantly different than the Mean of "Cleanliness" for unsatisfied customer
        
17. The pvalue of "Departure Delay In Minutes" = 3.153596061795601e-106. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Departure Delay In Minutes" for satisfied customer is significantly different than the Mean of "Departure Delay In Minutes" for unsatisfied customer
        
18. The pvalue of "Arrival Delay In Minutes" = 1.273235124714396e-228. pvalue <= 0.05. Reject Ho. 
        We DO have enough proof that the Mean of "Arrival Delay In Minutes" for satisfied customer is significantly different than the Mean of "Arrival Delay In Minutes" for unsatisfied customer
        
From the conclusion above, we can focus on the categories that have significant difference in their mean (Satisfied vs Unsatisfied):
- Age
- Flight Distance
- Inflight Wifi Service
- Departure/Arrival Time Convenient
- Ease Of Online Booking
- Food And Drink
- Online Boarding
- Seat Comfort
- Inflight Entertainment
- Onboard Service
- Leg Room Service
- Baggage Handling
- Checkin Service
- Inflight Service
- Cleanliness
- Departure Delay In Minutes
- Arrival Delay In Minutes

We can ignore the following category for now, since they do not have significant difference in their mean (Satisfied vs Unsatisfied). But, for the sake of a detailed and complete analysis, we will include this category:
- Gate Location

# Conclusion and Recommendation 

From data analysis that we have done, we can conclude that:
- The oldest customers are 85 years old while the youngest are 7 years old.
- The highest amount of customer age is between 39-40 years old (2969 customers).
- The average age of customer is 39.38 years old
- Majority of customers are dissatisfied/neutral with the services provided, doesn't matter whether they are a loyal or disloyal customer
- Customers who travel for personal reasons have higher dissatisfaction/neutral ratio compared to customers who travel for business purposes
- The class that has the biggest difference in ratio percentage of satisfaction level is Eco Class, followed by Eco Plus Class and Business Class. More effort should be given as priority to Eco and Eco Plus Class
- For the customers who rated '1-3' on the Inflight Wifi Service, the ratio of dissatisfaction/neutral is far larger than the satisfied customers. Some adjustments need to be done to improve the Inflight Wifi Service
- All rating score in Departure/Arrival Time Convenient has higher dissatisfied/neutral customers than satisfied customers. This is an extremely critical issue and need to be reviewed immediately
- Most customers tend to be dissatisfied/neutral and rated lower for Online Booking. Some improvements need to be done
- The majority of customers are dissatisfied/neutral with the gate location. Improvements are advisable
- Most customers are dissatisfied/neutral with the food and drink provided. Some improvements are necessary. Example: expand the menu selection, improve the quality and taste of food and drink, lower the price (and at the same time, reduce the portion to maintain profit)
- The majority of customers are dissatisfied/neutral with the online boarding system. Some improvements are needed
- The majority of customers are dissatisfied/neutral with the seat and leg room provided. Some adjustments are necessary
- The majority of customers are dissatisfied/neutral with the baggage handling service. Some improvements are recommended
- Almost all rating group (1-4) are dissatisfied/neutral with the check-in service. Some immediate changes are required
- Most of the customers are dissatisfied/neutral with the inflight service provided. Immediate adjustments are necessary
- Most customers are dissatisfied/neutral with the cleanliness of the aircrafts. Some major improvements are necessary
- The average departure and arrival delay duration that made customers dissatisfied/neutral are 16.50 minutes and 17.07 minutes respectively
- Majority of customers are dissatisfied/neutral with the departure and arrival delay

**Recommendation**
1. Improve overall service provided
2. Put more effort to improve satisfaction level on Eco and Eco Plus Class. But that does not mean we can neglect the Business Class
3. Increase the onboard wifi speed, lower the wifi price or if feasible, make it free
4. Improve UI/UX for online booking, expand the payment method options, and minimize the booking steps/progress to shorten the time needed to book a flight
5. Use the closest boarding gates to the check-in/immigration counter. If not possible, provide dedicated on-ground transportation (e.g. buggy cars) to minimize the effort needed to reach the boarding gate
6. Improve the quality and taste of food and drinks, lower the price (but also reduce the portion to maintain profit)
7. Improve the UI/UX for online boarding system
8. Widen the seating area and arm rests, use softer material for the seat cushion, increase the leg room space
9. Increase the efficiency of baggage handling process by using automated machinery instead of human elements. This is also great to reduce labor cost
10. Improve the behavior and SOPs of PICs at the check-in counters, install self check-in counter at major airports
11. Improve the flight attendants' ability in giving services above and beyond the standard, create online purchase system to let customers purchase inflight services (food, drink, merchandise, entertainment, etc) before the flight
12. Increase the intensity of cleaning for areas with high traffic (toilet, aisle, table tray, etc)
13. Reduce the departure and arrival delay by maximizing baggage loading, baggage unloading, take off, landing, refueling, and other processes' efficiency

With these recommendations, we hope that this analysis will be useful for the airline company to increase customer satisfaction level.
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Purwadhika/Capstone_Project_2_README at main · NJT09/Purwadhika
