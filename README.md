# Problem Statement or Business Objective:
## Paisabazaar Bank Fraud Analysis
Paisabazaar is a financial services company that assists customers in finding and applying for various banking and credit products. The credit score of a person is a significant metric used by financial institutions to determine the likelihood that an individual will repay their loans or credit balances. Therefore we are going to do a comprehensive analysis of Paisabazaar dataset to find out how various important metrics, such as Annual Income, Delay Payment, age, occupation and many others, influenced the credit scores. Credit scores can help Paisabazaar enhance their credit assessment processes like reduce the risk of loan defaults, and offer personalized financial advice to their customers. So let's begin. 
First of all we have to make our data clean, remove duplicates and outliers that I have done through capstone project Module-2, here I did little a bit some  changes like group by using Power Query Editor.

# Dataset Selection

For this EDA project, I have chosen the "Paisabazzar" dataset. This dataset Consist many attributes such as Age, Occupation, Payment Behavior, Annual Income, In Hand Salary and so on. 'Paisabazzar' dataset is a good for exploration in details to get significant business insights that will assist paisabazzar to enhance their credit assessment processes like reduce the risk of loan defaults, and offer personalized financial advice to their customers. 

# Dashboard Objectives or Problem Areas to Explore::
The primary objective of this dashboard is to optimize Paisabazaar’s credit assessment framework by translating complex borrower behavioral profiles into interactive, visual risk profiles. By tracking how financial and demographic metrics influence credit brackets, the analytics aims to:

**1. Reduce Loan Default Risks**
Isolate high-risk indicators (like specific thresholds of payment delays or volatile payment behaviors) to proactively deny or adjust high-risk applications.

**2. Personalized Financial Advice**
Enable Paisabazaar’s customer-facing platforms to offer targeted financial recommendations, helping "Standard" and "Poor" tier customers identify their specific credit bottlenecks and navigate towards a "Good" rating.

to achieve this Instead of treating customers as a single group, this dashboard segments them into three distinct risk tiers: Good, Standard, and Poor. based on that we are going to look each metrics and find out that which metrics are more important to identify Risk and offer personalized financial advice to customers.

# Dataset Details:

- Dataset Name: 'Paisabazzar'
- Source: Link to dataset 
https://drive.google.com/file/d/1eG1IYOXO8DgVapl6BcOvjU51v4q91fIJ/view?usp=sharing

### 📋 Data Dictionary & Key Attributes

* **'ID'** - Unique identification tag for each individual transaction record.
* **'Customer_ID'** - Unique identification tag assigned to each individual customer profile.
* **'Month'** - The specific calendar month of data capture used to track trends over time.
* **'Age'** - The age of the customer, used to assess demographic-based financial stability.
* **'Occupation'** - The primary profession or industry sector of employment for the borrower.
* **'Annual_Income'** - The gross total salary or revenue earned by the customer over a year.
* **'Monthly_Inhand_Salary'** - The net take-home pay a customer receives each month after taxes and deductions.
* **'Num_Bank_Accounts'** - Total number of open deposit and checking accounts owned by the individual.
* **'Num_Credit_Card'** - Total number of active credit cards currently held under the customer's name.
* **'Interest_Rate'** - The base percentage rate charged by lenders on the customer's open loans.
* **'Num_of_Loan'** - Total number of active, outstanding loans currently assigned to the borrower.
* **'Type_of_Loan'** - Categorical description detailing the types of debt held (e.g., Personal, Auto, Home Loan).
* **'Delay_from_due_date'** - Average number of days past the monthly deadline a customer takes to make payments.
* **'Num_of_Delayed_Payment'** - Count of individual payment instances that were missed or late over the tracking period.
* **'Changed_Credit_Limit'** - The percentage change or variation applied to the customer’s available credit limit.
* **'Num_Credit_Inquiries'** - Count of hard credit checks conducted by financial institutions due to new loan applications.
* **'Credit_Mix'** - Classification of the variety and quality of credit accounts held (e.g., Bad, Standard, Good combination).
* **'Outstanding_Debt'** - The remaining net monetary balance yet to be repaid to creditors.
* **'Credit_Utilization_Ratio'** - Percentage of total available credit lines actively used by the customer.
* **'Credit_History_Age'** - The lifespan of the customer’s credit profile, measured continuously in months.
* **'Payment_of_Min_Amount'** - Indicator tracking whether the customer only pays the bare minimum due on credit bills.
* **'Total_EMI_per_month'** - Total fixed Equated Monthly Installments paid toward servicing current liabilities.
* **'Amount_invested_monthly'** - Total capital actively funneled into savings, stocks, mutual funds, or investment schemes.
* **'Payment_Behaviour'** - Spending and repayment category profile (e.g., Low spent Small value, High spent Large value).
* **'Monthly_Balance'** - The disposable cash remaining in the customer's pocket at the end of the month.
* **'Credit_Score'** - Target categorical ranking mapping risk into specific brackets (Good, Standard, Poor).


# Deliverables

1. **Link of Dashboard Power BI**
https://drive.google.com/file/d/1R4TebYwQlMR8hKhiU5HaKBVpA6tVGwe5/view?usp=sharing

2. **Link of recorded video explaining the dashboard**
https://drive.google.com/file/d/1tLPelwMfqmQhTUbBsMAGpTOhJZpQ-z85/view?usp=sharing

3. **Link of Dashboard Screenshots**
https://drive.google.com/drive/folders/1nVX5dMj9qQu98lcKaelSiTeJtYhqtlY_?usp=sharing


# Major Key Insights and Explanations for Paisabazzar

## Dashboard page 1
<img width="1464" height="864" alt="Screenshot (1 )" src="https://github.com/user-attachments/assets/f30c4c18-b53c-4b50-8fb1-28c372aec325" />

### Observation:
Credit Score Distribution Donut Chart illustrate that 55.7% (6.53K) of consumer portfolio falls into the 'Standard' tier and Paisabazzar's majority of consumer belongs to this largest portion. Followed with 27.44% (3.21K) are classified as 'Poor', which is a significant risk concentration. Only 16.8% (1.98K) fall into the 'Good' tier.

Average Credit History Age Bar Chart shows a clear pattern that consumer with longest credit relationship maintain their credit score as 'Good'.

Average Annual Income by Credit Score and Age Scatter Plot chart reveal age and income combination consumer. Older consumer with high annual income maintained credit score as 'Good'.

### Interpretation:

Age, high annual income, and longer credit history are the primary statistical drivers of strong credit health ('Good' tier). Therefore paisabazzar can use these metric to filter the portfolio. 



## Dashboard page 2

<img width="1461" height="881" alt="Screenshot (2 )" src="https://github.com/user-attachments/assets/df7f51b3-fae0-4f5c-8907-14d4cc7ca64e" />

### Observations
Risk KPIs: The portfolio averages a 20.54-day payment delay, a 32.32% credit utilization ratio, a 14% interest rate, and 1.38K in outstanding debt.

'Poor' credit tier customers experience the highest average delays (exceeding 30 days) and face the highest average interest rates over 20%, whereas 'Good' tier customers keep delays under 10 days and interest rates under 10%.
Income vs Debt scatter plot reveals that 'Poor' risk consumers have the lowest average annual income around 40k but carry the highest outstanding debt around 2.1K, while 'Good' consumers have the highest income approximate 68K and the lowest debt likely 750.

The risk breakdown across occupations shows a highly consistent volume of customers (around 800–900 per profession), with 'Standard' (yellow) making up the vast majority and 'Good' (green) representing the smallest segment across all jobs.


### Interpretation
Paisabazzar can mark that how income, interest and outstanding debt are important to find out the risky behavior of consumer. it can be seen clearly in  Income vs Outstanding Debt Scatter Plot on the bottom left, A strong negative correlation exists between income and outstanding debt, lower-income individuals are heavily debt burden, which is the major cause for payment delays and  interest rate burdens due to risk pricing.

Homogeneous Professional Risk: Credit risk distribution is heavily uniform across all  occupations (from Lawyers to Writers), indicating that job title alone is a weak predictor of credit health compared to direct behavioral metrics like income level and payment delays.


### Dashboard page 3


<img width="1490" height="862" alt="Screenshot (3 )" src="https://github.com/user-attachments/assets/81bc7f22-23c8-41c7-a749-d2fad1796b0b" />


### Observations
the horizontal bar chart maps out the Total Delay from due date by Payment Behavior. Look at the top bar 'Low spent Small value payments'. Consumers classified as "Low spent Small value payments" drive the highest volume of late payments. This is followed by "High spent Medium value payments", while "Low spent Large value payments" cause the lowest total delay. 

The right-hand chart shows three distinct cycles mapping Average Monthly Inhand Salary against the combination of Credit Score and Credit Mix vs Total Income. Across all segments, consumers labeled as having a "Good" credit mix consistently peak at an average monthly inhand salary close to 6K, regardless of whether their credit tier is Good, Poor, or Standard. Conversely, segments with "Bad" or "Standard" credit mixes hit salary troughs below 4K.

### Interpretation

The highest repayment delays generated by user from low-spending, small-value transaction users. This means that a high frequency of small, fragmented debts is a primary key of payment delay.

Income level correlates much more strongly with the diversity of the user's financial products ("Credit Mix") than the standalone credit score. A higher monthly salary is another key to achieving a "Good" credit mix, even if the user's baseline credit score is currently flagged as Poor or Standard.



### Dashboard page 4

<img width="1467" height="881" alt="Screenshot (4 )" src="https://github.com/user-attachments/assets/790f3cc3-50b6-4238-aab5-3bd13dd11e79" />


This is the Drill Through target page. 

In this page charts are perfect for spotting visual trends, In case if we need a data dense view when conducting deep analysis. When we looking at any chart on the previous pages can right-click a data point and select 'Drill Through'. Power BI will instantly bring to this page, automatically filtering this matrix to show the micro-level numbers behind that specific group.

### Observations
Notice that the page is filtered down to the Standard credit score tier using our synchronized top slicers. This changes our view to an average delay of 19.04 days and an average outstanding debt of 1.20K.

If you expand the row hierarchy under the Bad (Poor) credit group, the financial red flags stand out immediately. Regardless of their spending habits, 'Bad' credit customers average an alarming 6.75 active loans and nearly 20 delayed payments (19.81). Their average delay from due dates is 37.94 days, and they carry a heavy debt load of 3,445.65.

Compare that to the Good row folder, these customers average less than 2 loans (1.95), only 6.49 delayed payments, an average delay of just 8.84 days, and a well-controlled outstanding debt average of 746.39.



### Dashboard page 5

<img width="1474" height="856" alt="Screenshot (5 )" src="https://github.com/user-attachments/assets/0b2fbf66-742f-4f42-977a-443dd9035545" />

### Observations
Risky Behaviour Analysis page, which focuses on a hidden risk indicator, the Average Number of Credit Inquiries. In consumer lending, a sudden surge in credit inquiries means a customer is actively looking for multiple new loans. This signals credit hunger, potential cash flow issues, or an upcoming financial crunch.

When we see the Good credit segment. Their inquiry rate is incredibly low and stable, averaging between 1.98 and 2.21 inquiries, regardless of their spending habits. These customers are financially secure and only look for credit when necessary.

Poor credit customers, inquiry volume spikes drastically, averaging between 6.63 and 8.02 inquiries per customer. The highest numbers belong to the 'Low spent Small value payments' cohort at 8.02 inquiries. This confirms our earlier insight, customers with weak credit scores who rely on small-value transactions are constantly applying for new loans or cards. 

### Interpretation
Paisabazaar can immediately use this insight for risk mitigation. Paisabazzar should flag any account where credit inquiries cross above 5 within a short window, triggering a temporary freeze on new personal loan offers.



### Dashboard page 6
this is the Page Tooltip and entire page is hidden from the end-user. It doesn’t act as a standard dashboard tab. 


### Dashboard page 7

<img width="1463" height="863" alt="Screenshot (7 )" src="https://github.com/user-attachments/assets/b3c56cf5-d5ff-4d79-8474-ba9abb294226" />

### Observations
**RAC of Num of delay Payment:** In this Page the Decomposition Tree chart is to conduct a Root-Cause Analysis (RAC) to understand what underlying factors drive our portfolio baseline average of Delayed Payments.

This decision tree chart maps specific consumer pathways to show how loan volumes, interest rates, utilization ratios, and spending behaviors culminate in a 'Poor' credit score.

**Root Node Base:**  a baseline node of an Average number of delays at 13.07. The highlighted primary path branches to a consumer segment carrying 8 active loans, which shows a notable average of 19.75 payment delays. Interest Rate Node for 8-loan segment, the path flows into a high-risk pricing bracket with an interest rate of 28%, averaging 19.19 payment delays. 

**Target Risk Destination:** The path continues through a 23.2% credit utilization ratio and a "High spent Medium value payments" transactional profile, ultimately terminating at a targeted terminal node of a 'Poor' credit score.


### Interpretation
Carrying a high volume of 8 loans acts as a structural warning for repayment risk, nearly doubling the average number of payment delays from 13.07 to 19.75.

High credit volumes trigger elevated interest rate 28%, which compounds the debt burden and locks the consumer into a predictive pathway that tend into a 'Poor' credit classification.



### Dashboard page 8

<img width="1452" height="813" alt="Screenshot (8 )" src="https://github.com/user-attachments/assets/2fdc52cd-b63b-4b6a-9882-724d7c7d5e07" />


### Observations
our final tab is the Breakdown of Delay from due date. This page utilizes a Waterfall Chart titled 'Average of Annual Income by Credit Score and Delay from due date' to show how average annual income increments and drops as we move across different credit profiles and payment delays.
Starting from the baseline 'Good' credit score segment, income consistently increases (green steps) as it aggregates group with distinct repayment delays, peaking close to 0.4M average annual income.

on the other hand 'Standard' credit score tier, representing a significantly lower baseline income level compared to the peak of the 'Good' tier.

From the secondary 'Standard' baseline, the chart shows a steady, cascading decrease in average annual income (red steps) across sequential delay groups, finally bottoming out at the lowest income level in the 'Poor' credit score segment.


### Interpretation

In the 'Good' credit tier, consumers are able to maintain their top-tier credit status despite varying days of payment delays (like delays of 32, 33, 39 days) because their higher average annual income.
 
when income drops then there is a downward migration from 'Standard' to 'Poor' credit brackets. Lower annual income directly compromises a consumer's cash flow stability, making repayment delays a destructive factor that rapidly degrades credit scores.


# Conclusion

After analysis of data I came to an conclusion that PowerBi dashboard yield a significant business key insight. 
**The  Paisabazaar Credit Risk Monitor portfolio proves:**
Richer and older customers with a long credit history can easily survive a few late payments. Their high income acts as a safety net, allowing them to keep a 'Good' credit score. Lower-income customers often get trapped. They take out too many loans at once (like the 8-loan) and get hit with high interest rates (28%). This makes it very hard to pay on time, dragging them down into the 'Poor' credit score bracket. A massive 83% of the people in this data fall into the 'Standard' or 'Poor' categories. This means the vast majority of the portfolio carries a high risk of not paying back what they owe.




