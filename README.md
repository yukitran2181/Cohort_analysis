# **Introduction**

**1.1. Business question**

Using Python to analyze transaction data from KPMG to evaluate user engagement from their first transaction

**1.2. Dataset**

Dataset KPMG.xlsx includes one table containing transaction information of customers purchasing products in the year 2017

<p align="center">
  <img src="KPMG table.png" width=800><br/>
  <i>Table_Information</i>
</p>


**1.3. Method: Cohort analysis**

Cohort analysis definition

- Cohort analysis is a type of behavioral analytics in which you take a group of users, and analyze their usage patterns based on their shared traits to better track and understand their actions.
- A cohort is simply a group of people with shared characteristics

Three major types of Cohort

- Time cohorts: customers who signed up for a product or service during a particular time frame.
- Behavior cohorts: customers who purchased a product or subscribed to service in the past.
- Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.

Cohort type of this project

- This project focuses on performing **Cohort Analysis based on Time**
- Customers will be divided into acquisition cohorts depending on the month of their first purchase (cohort month)
- The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction

# **Data Visualization**

<p align="center">
  <img src="Transaction.png" width=800><br/>
</p>

<p align="center">
  <img src="Number of customers.png" width=800><br/>
</p>

# ****Insights****

- In general, the retention rate at KPMG is quite stable, mostly maintained in the range of 31% to 45%. However, the number of customers who made the first purchase decreased sharply over the months, from 1347 customers (Jan 2017) to 4 customers (Dec 2017)
- Customers who placed their first order between April and July 2017 tend to have higher retention rates than the other groups: 48.1% in the fifth month of July 2017, 45.1% in the fourth month of April 2017.
- Retention rates of customers purchasing their first products in January, February, and March 2017 were relatively stable (about 33% to 43%). Meanwhile, these rates in August, September, and October 2017 are more fluctuating, especially in August: 43.1% in the 3rd month but 25.5% in the 5th month.

# Recommendations

- KPMG did a good job of maintaining stable retention rates over the user's lifetime, but the number of customers who made the first purchase declines over time → We need to gather more information about the context in the past (promotions, seasonal trends, ****product quality changes, etc.) to analyze the cause and evaluate the effectiveness of marketing campaigns
- The mid-year months (Apr - Jul) have higher retention rates than other groups -> focus on finding out the characteristics of these groups to design special offers or new marketing campaigns for other months of the year.
