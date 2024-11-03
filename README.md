![image](https://github.com/user-attachments/assets/6a425d0b-9994-4e6b-83ed-c10ac75fef71)

The bank wants to improve their services. For instance, the bank managers have only vague idea, who is a good client (whom to offer some additional services) and who is a bad client (whom to watch carefully to minimize the bank loses). Fortunately, the bank stores data about their clients, the accounts (transactions within several months), the loans already granted, the credit cards issued The bank managers hope to improve their understanding of customers and seek specific actions to improve services. A mere application of a discovery tool will not be convincing for them.

Streamlit Deployed Website Link - https://credit-card-analysis-qgusy8lihrhygfamb5f2s8.streamlit.app/

<div align="center">
<h1>DashBoard</h1>
</div>
<img src="https://github.com/user-attachments/assets/0b6c6e3d-0d68-4f2d-9d8f-9f111acd3355" alt="Sample Image" style="max-width: 100%;">


<img src="https://github.com/user-attachments/assets/b1b14e9e-d4bd-44a0-b688-48167d33d1a7" alt="Sample Image" style="max-width: 100%;">
<img src="https://github.com/user-attachments/assets/0e99769f-3077-4148-92c7-7bc0816ebae3" alt="Sample Image" style="max-width: 100%;">



<h2>Client Classification and Economic Disparity Analysis for Financial Risk Management</h2><br/>
<H3>Description</H3>
This project analyzes bank client data—including transactions, loans, and credit cards—to classify clients who may be at risk of default. Additionally, the project examines economic disparities across districts and identifies patterns of loan risk to derive insights that can enhance loan approval processes.

<H2>Key Features:</H2>
Client classification based on financial behavior.
Analysis of economic disparities by district to tailor loan products.
Identification of loan risk patterns.
Recommendations for improving loan approval processes based on findings.

<H2>Project Structure</H2>
<H3>1. Data Understanding</H3>
Data Sources: Bank client data, transactions, loans, credit cards, and district information.
Goal: Understand relationships between datasets, examine attribute names, content, and ranges.

<H3>2. Data Preparation</H3>
Renaming Attributes: Ensure column names are meaningful and consistent across datasets.
Extracting Key Information:
Extract client age and sex from birth numbers.
Handling Missing Data:
Replace missing values in District D69 with the average values from other districts.
Sanctions Information: Identify accounts with a history of sanctions by analyzing transaction data.

<H3>3. Analysis</H3>
<H4>a. Client Classification</H4>
Objective: Identify clients at risk of default based on account balance.
Methodology: Determine how many times the balance in their account fell below industry standards and flag clients accordingly.
<H4>b. Economic Disparities</H4>

Objective: Analyze salary and balance disparities across different districts.

<H4>Methodology:</H4>

Compare average salaries and account balances across districts.
Highlight regions with higher and lower average salaries, such as:

High-salary districts: 'Hl.m. Praha', 'Mlada Boleslav', 'Plzen - mesto', etc.

Balanced districts: Chomutov, Zlin, Pardubice, etc.

Tailor loan products based on the economic profile of each district.

<H4>c. Risk Patterns</H4>
Objective: Identify risk patterns in loan performance.

<H3>Key Risk Indicators:<H3>
Loan amount.
  
Loan duration.

Insight: Larger and longer-term loans pose higher risks, requiring stricter credit checks and potentially more collateral.
Code Sections

<H3>1. Data Understanding</H3>
Loading and Cleaning Datasets:
Load client, transaction, loan, credit card, and district data.
Clean datasets to ensure proper relationships between them.

<H3>2. Data Preparation</H3>
Renaming Columns:
Ensure columns have meaningful names.
Extracting Information:
Extract age and gender information from birth numbers.
Handling Missing Data:
Replace missing values in districts with averages.

<H3>3. Client Classification</H3>
<H4>Classifying Clients:</H4>
Identify clients who are at risk of default based on their account balances and how often the balance falls below the threshold.

<H3>4. Economic Disparities</H3>
Analyzing District-Level Disparities:
Compare average salaries and balance trends across districts to highlight economic differences and adapt loan offerings accordingly.

<H3>5. Risk Patterns</H3>
Loan Performance Analysis:
Analyze the risk of loans based on the amount and duration to identify high-risk loans and improve the bank's risk management strategies.

SOME DETAILED SUMMARY
Data Understanding
Business is based of operations in any regular bank such as transactions, clients, credit cards and loans.

Analysis of data tables relationships

Understanding the attribute’s “names” and their meaning

Understanding the attribute’s content meaning (possible values of each attribute like the range and type

Data Preparation
Renaming attribute’s names for more meaningful keywords. Spreadsheet “Demographic Data” Extract implicit knowledge Extract “birthdate” and “sex” from clients birth number Extract client age from birth number Eliminate incoherence provoked by empty files District D69 had missing values that were replace by average value of all other districts Retrieve useful information from “transaction” datasheet. Ex.: Accounts with history of sanctions

<H1>SOME DETAILED SUMMARY
</H1>

<H2>Data Understanding</H2>
Business is based of operations in any regular bank such as transactions, clients, credit cards and loans.

Analysis of data tables relationships

Understanding the attribute’s “names” and their meaning

Understanding the attribute’s content meaning (possible values of each attribute like the range and type


<div align="center">
<h1>Charts</h1>
</div>
<div align="center">
<H2>Distribution Of Client by Age</H2>
</div>
<img src="https://github.com/user-attachments/assets/486fd6b2-2cb8-48fc-9b23-cb85d817fdba" alt="Sample Image" style="max-width: 100%;">

<div align="center">
<H2>Transaction Amount by Transaction Type</H2>
</div>
<img src="https://github.com/user-attachments/assets/71538115-d1fb-426e-974e-790088973f15" alt="Sample Image" style="max-width: 100%;">

<div align="center">
<H2>Transaction Amount by Transaction Type</H2>
</div>
<img src="https://github.com/user-attachments/assets/a94587a5-d3ab-4a29-95ce-e56de24cfa04" alt="Sample Image" style="max-width: 100%;">
![image](https://github.com/user-attachments/assets/a94587a5-d3ab-4a29-95ce-e56de24cfa04)


<div align="center">
<H2>Number of cards issued Overtime</H2>
</div>
<img src="https://github.com/user-attachments/assets/69865db5-fec0-413b-950a-545e2527bae4" alt="Sample Image" style="max-width: 100%;">


<div align="center">
<H2>Average Order Amount by Transaction Type</H2>
</div>
<img src="https://github.com/user-attachments/assets/8286b4a5-61d7-4ffd-894b-d1d0414eed83" alt="Sample Image" style="max-width: 100%;">


<div align="center">
<H2>Insights</H2>
</div>
Client Segmentation and Risk Profiling: The bank can leverage its existing client data to categorize customers based on their financial behavior, such as spending habits, loan repayment history, and credit card usage. By identifying high-value clients for upselling services and risk-prone clients for closer monitoring, banks can tailor their services effectively, enhancing both customer satisfaction and risk management.

Predictive Loan and Credit Approval Models: Utilizing historical data on transactions, loans, and credit card usage can help build predictive models that forecast loan default risks. Analyzing economic disparities across regions can further fine-tune these models. This leads to more informed lending decisions, optimizing loan approval rates while reducing the risk of bad debt.

Tailored Credit Card Offerings: By analyzing transaction patterns and average spend across different transaction types, banks can create customized credit card products for specific customer segments. For example, clients who frequently spend on travel can be offered premium travel credit cards, while those with lower transaction volumes might benefit from no-fee cards with cash-back offers. This approach drives targeted marketing and increases product uptake.

Enhanced Customer Relationship Management (CRM): Using data-driven insights to personalize banking interactions can deepen customer relationships. For instance, offering credit limit increases to clients with a history of responsible card usage, or providing budgeting tools to clients prone to overdrafts, could foster loyalty and improve financial health, increasing long-term engagement with the bank.

Cross-Selling Opportunities via Data Insights: Insights from clients' financial behaviors can help banks identify opportunities for cross-selling other products, such as insurance or investment services. For example, a customer who uses a credit card for large purchases may be interested in personal loans, or those making frequent travel-related purchases could benefit from bundled travel insurance plans.

Conclusion:
This project goes beyond merely applying discovery tools by providing a comprehensive strategy that utilizes data analytics, predictive modeling, and actionable insights to improve the bank's services. This data-driven approach will ultimately enhance customer relationships, increase profitability, and minimize financial risks.

