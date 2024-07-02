![RB logo](pictures%20and%20visualization/RB%20logo.png)

# SQL-Rockbuster-Data-Analysis

### This project was completed as part of the curriculum from the CareerFoundry bootcamp.

## Introduction
#### To stay profitable, Rockbuster Stealth LLC, a global movie rental company, is shifting its business model. Facing intense competition from streaming service providers, including major players like Amazon Prime and Netflix, Rockbuster Stealth LLC has experienced a significant drop in rental rates. To remain competitive in the market, the goal is to launch an online rental service.

## Purpose
#### This project aims to use query-based analysis (SQL) within Rockbuster's RDBMS to answer key business-related questions, providing valuable insights for various departments involved in this initiative.


## Key Questions and Objectives

- Which categories contributed to the most/least revenue gain?
- What was the average rental duration for all videos? 
- Which countries are Rockbuster customers based in? 
- Where are customers with a high lifetime value based? 
- Do sales figures vary between geographic regions?

## Data & Main Queries

### 1) Data Understanding

For the project analysis, we utilized Rockbuster’s relational database management system along with PostgreSQL. The dataset includes comprehensive information about Rockbuster’s film inventory, customers, payments, store locations, addresses, staff, and actors. Specifically, it encompasses data on 599 clients from 109 different countries, and a selection of 1,000 films categorized into 20 different genres.

### 2) Queries 

The following query demonstrates the commands used to identify the most profitable category:

<img src="pictures%20and%20visualization/sql%20category.png" alt="sql_category" width="600" height="300">  <img src="pictures%20and%20visualization/total_rev_per_cat.png" alt="total_rev_per_cat" width="600" height="300"> 




#### For visualization of other queries, please refer to the CTE files that demonstrate commands used to identify the top 5 customers, as well as the top 10 countries and cities.

## Results & findings

- Sports, Sci-Fi, Animation, Drama & Comedy are the category that generated the most revenue. Thriller is the least favorite category
- On average, people rented our movies for more than 5 days, with a maximum of 7 days.
- 
- India, China and the USA are the countries with the most customers, and the ones that generate the highest revenue 
([Number of customer and Total Sales of Rockbuster's Rental Service Tableau visualization](https://public.tableau.com/app/profile/oumaima.salmi/viz/NumberofcustomerandtotalsalesofRockbustersRentalService_CFAchievement3/Sheet1?publish=yes))
- High value customers are based mainly in Mexico, Turkey, the USA and India


## Conclusion & Next Steps

- Most customers reside in India, China, USA and Japan, with Asia being the primary market
- Consequently, the majority of the revenue is generated in these countries
- The categories of movies also significantly influence the revenue potential for our planned online rental service

- Entering the Asian market first would be the most straightforward approach due to the large customer base. With the brand already being relatively well-known, implementing a simple brand strategy would be easier.
- Proposing a subscription model or different pricing based on the average rental days could bring beneficial results.
- Lastly, offering discounts to our high-value customers could positively impact the brand's image.

