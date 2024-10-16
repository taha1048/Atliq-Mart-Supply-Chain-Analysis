# Atliq-Mart-Supply-Chain-Analysis
### This project is one of the [Codebasics.io resume challenges](https://codebasics.io/challenge/codebasics-resume-project-challenge)

# Problem Statement
### AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

### AtliQ Mart is currently facing a problem where (a few key customers did not extend their annual contracts due to service issues). It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

### The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.

# Data Source
You can download the material from [here](https://codebasics.io/challenge/codebasics-resume-project-challenge/5)

# KPIs 
### 1. Line Fill Rate	(LIFR %)	    = Number of order lines shipped In Full Quantity / Total Order Lines
### 2. Volume Fill Rate	(VOFR %)    = Total Quantity shipped / Total Quantity Ordered		
### 3. On Time Delivery %	(OT %)    = Number of orders delivered On Time / Total Number of Orders
### 4. In Full Delivery %	(IF %)    = Number of orders delivered in Full quantity / Total Number of Orders
### 5. On Time In Full % (OTIF %)   =	Number of orders delivered both IN Full & On Time / Total Number of Orders

# Variables
### 1. Customer
### 2. City
### 3. Product
### 4. Product Category

# EDA and Data Mining
I used Python and SQL to explore the data to see how to clean and visualize it and to test some hypothesies. You can find the file [here](https://github.com/taha1048/Atliq-Mart-Supply-Chain-Analysis/blob/main/EDA%2C%20Data%20Cleaning%2C%20%26%20Data%20Mining.ipynb)

# Asking Questions
We want to identify: 
### 1. The issue
### 2. Who has it
### 3. Where
Note : Usually we would consider a when question, but after exploring the data, the numbers where similar all the time so there is no correlation here

# 1. Identifing The Issue
I created a switch button to move between different KPIs and see the Actual VS Target for each one 
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-1](https://github.com/user-attachments/assets/cc72f18d-e67d-4bcf-a023-779450ff163e)

# 2. Who has it 
Comparing between customers in terms of all the previous KPIs
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-2](https://github.com/user-attachments/assets/ef89c23d-256b-48d9-b13e-0ec2790da1a5)

# 3. Where
Looking at the city level and city-customer level by switching between kPIs
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-3](https://github.com/user-attachments/assets/1390412a-55e0-4eb8-98ce-53e9a909ed13)

---
### After answering these questions and in order to solve the problem we need to manage our stores, lines of production, and timing, so let's keep going.
---
# 4. Product Analysis
1. Products that are ordered the most
2. Average quantity ordered/dilevered/delayed per line
3. Category & size comparison
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-4](https://github.com/user-attachments/assets/90b83304-8cfd-4fdd-a6e7-ab6e657f0af7)

# 5. Lines & Orders
1. Peek of orders & lines
2. Shipping days
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-5](https://github.com/user-attachments/assets/f9a0b506-6302-4e7b-8c71-11cd4daa7396)

---
Results
---
# 1. On Time Delivery 
As shown we didn't meet our target even once, nor for customers, cities, or time.

![OnTime](https://github.com/user-attachments/assets/5943e8d5-a6a9-4fb3-abbe-56d71f74170f)

We have a huge drop for these 3 customers:
1. Lotus Mart
2. Acclaimed Stores
3. Coolblue

The problem is that those are on the top of our customers list

![customers table](https://github.com/user-attachments/assets/12c23a23-5ba7-47b1-923b-e174aefc4d70)


