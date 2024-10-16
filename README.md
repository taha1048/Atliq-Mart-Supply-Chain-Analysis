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
### 4. When

# 1. Identifing The Issue
I created a switch button to move between different KPIs and compare between Actual and Target for each one 
![13c5a1bf9fba47819d25b5bdce751339Ho1thUJQEHwMZnjf-1](https://github.com/user-attachments/assets/cc72f18d-e67d-4bcf-a023-779450ff163e)
