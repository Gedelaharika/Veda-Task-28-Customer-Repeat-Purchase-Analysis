# Veda Task 28 – Customer Repeat Purchase Analysis

## Project Overview

This project analyzes customer purchasing behavior to understand repeat purchases, customer segments, and the difference in purchasing value between first-time and repeat customers.

## Objectives

- Calculate the repeat customer rate.
- Segment customers based on purchase frequency.
- Compare First-Time and Repeat Customer AOV.
- Identify important customer behavior patterns.
- Generate business insights from the analysis.

## Dataset

The analysis uses the Online Retail II dataset for the 2009–2010 period.

## Data Preparation

The following preprocessing steps were performed:

- Removed records with missing Customer IDs.
- Removed cancelled transactions.
- Removed transactions with invalid or non-positive quantities.
- Removed transactions with invalid or non-positive prices.
- Calculated revenue using:

`Revenue = Quantity × Price`

## Customer Segmentation

Customers were grouped according to their number of purchases:

| Segment | Purchase Frequency |
|---|---:|
| First-Time | 1 purchase |
| Low-Frequency | 2–5 purchases |
| Medium-Frequency | 6–10 purchases |
| High-Frequency | More than 10 purchases |

## Key Results

### Repeat Customer Rate

- Total Customers: **4,383**
- Repeat Customers: **3,116**
- Repeat Customer Rate: **71.09%**

### Customer Segmentation

| Customer Segment | Customers | Customer Share |
|---|---:|---:|
| First-Time | 1,267 | 28.91% |
| Low-Frequency (2–5) | 1,898 | 43.30% |
| Medium-Frequency (6–10) | 716 | 16.34% |
| High-Frequency (>10) | 502 | 11.45% |

### AOV Comparison

| Customer Type | AOV |
|---|---:|
| First-Time Customers | ₹351.69 |
| Repeat Customers | ₹468.30 |

Repeat customers have an AOV that is approximately **33.16% higher** than first-time customers.

## Key Insights

1. **Repeat customers are the majority:** 71.09% of customers made more than one purchase.

2. **Low-frequency repeat customers form the largest segment:** Customers with 2–5 purchases account for 43.30% of the customer base.

3. **High-frequency customers are a smaller but valuable segment:** Customers with more than 10 purchases represent 11.45% of customers.

4. **Repeat customers have higher order value:** Repeat customer AOV is ₹468.30 compared with ₹351.69 for first-time customers.

5. **Customer retention is important:** The higher AOV of repeat customers indicates that encouraging customers to make additional purchases can be commercially valuable.

## Conclusion

The analysis shows that repeat purchasing behavior is an important contributor to customer value. Most customers in the analyzed dataset are repeat customers, and repeat customers have a substantially higher AOV than first-time customers.

Businesses can therefore focus on customer retention strategies, personalized offers, loyalty programs, and targeted campaigns to encourage first-time customers to make additional purchases and move existing repeat customers into higher-frequency segments.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Type

Customer Analytics / Exploratory Data Analysis / Customer Retention Analysis