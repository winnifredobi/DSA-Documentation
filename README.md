# DSA-Documentation {Hypothetical Project}

## PROJECT TOPIC: Analysis of Product Uptake for different accounts in TAJBank [Download Here](https://tajbank.com)

### Project Overview
To analyze Product Uptake for different accounts in TAJBank, we’ll need to approach the problem in a structured way. This involves looking at how different customer segments (e.g. by account type) adopt the various Bank's products (e.g. Qard, Qard Savings, Mudarabah Savings, Mudarabah Term Deposit and Mudarabah Current Account products).

### Table of Content

[1. Define the Scope](#1-Define-the-Scope)

[2. Data Gathering and Preparation](#2-Data-Gathering-and-Preparation)

[3. Key Metrics To Analyze](#3-Key-Metrics-To-Analyze)

[4. Segmented Analysis](#4-Segmented-Analysis)

[5. Visualization Into Our Data](#5-Visualization-Into-Our-Data)

[6. Insights and Recommendation](#6-Insights-and-Recommendation)

[7. The Future](#7-The-Future)


### 1. Define the Scope
   
  First we clarify what matrices shall be used to determine product uptake:

- Is it new product enrollment?
- Is it usage frequency?
- Is it activation versus non-activation?
- Timeframe (monthly, quarterly, annually?)
- Accounts to be compared (e.g., Qard, Qard Savings, Mudarabah Savings, Mudarabah Term Deposit and Mudarabah Current Account products)
- Product major categories (e.g., Qard and Mudarabah)

### 2. Data Gathering and Preparation
   
Next, we’ll need a dataset with at least the following fields:

- Customer ID
- Account type
- Product type
- Date of product uptake
- Status (active/inactive)
- Demographics (optional: age, income, location, etc.)
- Revenue from each product per account
- Cross-sell / up-sell history

### 3. Key Metrics To Analyze
   
Some of the key performance indicators (KPIs) to consider are as follows:

Metric	Description
- Product Uptake Rate: *The percentage of accounts that have adopted at least one product*
- Average Products per Account:	*Total number of products ÷ total accounts*
- Product Penetration Rate:	*Percentage of accounts that have each type of product*
- Cross-sell Rate: *Percentage of accounts with >1 product*
- Time to First Uptake:	*Average time from account opening to product adoption*
- Churn Rate by Product: *Percentage of accounts closing products over time*

### 4. Segmented Analysis
   
Subsequently we begin to analyze uptake across different product types:

Example:

|Account Type|	Card Uptake| TAJWay Uptake|	USSD Uptake| Internet Banking Uptake|	Avg Products/Account|
|-----------| -----------| -----------| -----------| -----------| -----------|
|Qard|	45%|	40%| 35%|	10%|	1.6|
|-----------| -----------| -----------| -----------| -----------| -----------|
|Mudarabah Current Account|	5%|	10%|	20%| 60%|	2.8|
|-----------| -----------| -----------| -----------| -----------| -----------|
|Mudarabah Savings|	50%|	50%| 45%|	30%|	5.2|
|-----------| -----------| -----------| -----------| -----------| -----------|
|Mudarabah Term Deposit| 0%|	0%|	0%| 0%|	1.3|

### 5. Visualization Into Our Data
   
- Bar chart: *Product uptake per account type*

![Pdt Uptake Per Account Type](https://github.com/user-attachments/assets/c545e31b-0747-4bfb-b798-1f4747c7985a)

- Line graphs: Trends in product adoption
  
![Trends In Product Adoption](https://github.com/user-attachments/assets/ee33c613-878b-4da4-aff7-981c696c0a21)

### 6. Insights and Recommendations
   
From the above analysis, we could extract the underlisted actionable insights:

- Which account type has the highest cross-sell potential?
- Are there underperforming segments for certain products?
- Do specific account types show early uptake trends?
- What promotional or onboarding strategies might boost uptake?

### 7. The Future

   Futuristically speaking, we could perform other analytics such as:

- Predictive modeling: *Use machine learning to predict likelihood of product uptake based on customer/account features.*
- Cohort analysis: *See how uptake varies by customer onboarding cohort.* and ultimately;
- Survival analysis: *Model time to product adoption or churn.*

**Thank you!**








