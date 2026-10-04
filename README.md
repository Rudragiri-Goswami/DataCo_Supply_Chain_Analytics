# DataCo_Supply_Chain_Analytics
# Supply Chain Analytics
### Delivery Performance & Late Delivery Prediction

## Project Overview

This project analyzes supply chain and delivery data from an e-commerce company to understand delivery performance and identify patterns associated with late deliveries.

The analysis focuses on delivery delays across shipping modes, regions, customer segments, departments, order types, and time periods. A machine learning approach is also used to predict the risk of late delivery.

The project combines exploratory data analysis, business analysis, visualization, and machine learning to provide a complete supply chain analytics workflow.

## Business Problem

Late deliveries can affect customer satisfaction and overall supply chain efficiency.

The objective of this project is to understand:

- How frequently deliveries are delayed
- Which shipping modes have higher delay rates
- Which regions and customer segments experience more delays
- Whether certain departments or order types are associated with higher delays
- How delivery performance changes over time
- Whether machine learning can predict late-delivery risk

The analysis is intended to help identify areas that may require closer operational attention.

## Project Objectives

- Clean and prepare the supply chain dataset
- Analyze overall delivery performance
- Identify factors associated with delivery delays
- Compare delay rates across business dimensions
- Analyze delivery performance over time
- Examine the relationship between delivery performance and financial metrics
- Build machine learning models for late-delivery prediction
- Compare model performance and select the best-performing model
- Present the findings through a Power BI dashboard

## Dataset

The project uses the **DataCo Supply Chain Dataset**, which contains information about:

- Orders
- Customers
- Products
- Departments
- Regions
- Shipping modes
- Order dates
- Shipping dates
- Delivery performance
- Sales and order profitability

For the analysis, relevant columns were selected and unnecessary identifiers and personal information were excluded.

### Main analytical fields

- Shipping Mode
- Customer Segment
- Department Name
- Order Region
- Order Status
- Order Type
- Days for shipping (real)
- Days for shipment (scheduled)
- Sales per customer
- Benefit per order
- Order date
- Shipping date
- Late delivery risk

## Delivery Delay Definition

A delivery is considered delayed when the actual shipping time is greater than the scheduled shipping time.

```text
Delay = Actual Shipping Days - Scheduled Shipping Days
