Faculty of Engineering & Technology



            Introduction To Data Analytics
        CREDIT CARD FRAUD RISK ANALYSIS
<img width="835" height="468" alt="image" src="https://github.com/user-attachments/assets/0649c690-0d29-4c17-9edf-a35770b1ff4a" />



Bachelor of Technology in Computer Science

Submitted To:

MR. Harshit Bhargave

Assistant Professor 

Faculty of CSED 

Submitted By: 

Team Name: 03 B.Tech Sec.E 

Group Leader: Ayush Sharma 

Total member: 12


																											 
                                                                  

                 ✅ DECLARATION
I, Ayush Sharma hereby declare that the project report titled “Credit Card Fraud Risk Analysis” is an original work carried out by me under the guidance of MR Harshit Bhargave. The work presented in this report is based on my learning, analysis, and interpretation using Power BI. The data and information used in the project have been collected from reliable online sources and are used purely for academic purposes.I further declare that this project has not been submitted previously, in part or full, for the award of any degree, diploma, or certificate to any other institute or organization.
Team Members' Contribution:

S. No.                Student Name                                                         Contribution

1                      Ayush Sharma (leader)                                                    100%

2                       Mukhtar Abbas Rizvi                                                      100%

3                       Vipul Kumar Sahu                                                          100%

4                        Harikesh Singh                                                           100%

5                        Mohammad Saqlain                                                         100%

6                        Rameez Raza Khan                                                         100%

7                        Ravi Kumar                                                                100%

8                        Vansh Rastogi                                                              90%

9                        Deepak Kumar                                                                80%

10                      Pragyansh Agniotri                                                            80%

11                      Pramod                                                                        60%

12                      Gaurav Sagar                                                                  60%

Place: 
Date:
Signature of Team Leader 
B.Tech (CSE) Sec. E
Ayush sharma.

                           CERTIFICATE
This is to certify that the project entitled “Credit Card Fraud Risk Analysis Dashboard” is a 
bona fide work carried out by Mukhtar Abbas Rizvi along with the team members of B.Tech 
Section E, during the academic year 2025–2026, in partial fulfillment of the requirements 
for the award of the Bachelor of Technology in Computer Science (B.Tech CSE) degree. 
The project work has been completed under my guidance and supervision. The team has 
exhibited outstanding teamwork, technical expertise, and analytical skills throughout the 
project duration. 
I am satisfied with the quality of the work and recommend this project for evaluation. 
 

















                       ACKNOWLEDGMENT 
We, the project team of Credit Card Fraud Risk Analysis, would like to express our sincere gratitude to Mr. Harshit Bhargave, our project guide, for his continuous support, valuable feedback, and guidance throughout the development of this project. His encouragement and insights helped us understand the concepts of data analytics and Power BI more deeply.
We extend our heartfelt thanks to Mr. Gaurav Agarwal, Head of Department, Computer Science & Engineering, Invertis University, for providing a motivating environment and the necessary resources to complete this project successfully.
We are also thankful to all the faculty members of the CSE Department for their support and cooperation during the course of this work.
We would like to thank all our team members 
for their consistent contribution, coordination, and dedication in completing this project.
Finally, we thank our families and friends for their constant encouragement, support, and motivation, which helped us stay focused and complete this project with sincerity.


Team Members: 

Ayush Sharma (Leader) 

Mukhtar Abbas Rizvi

Vipul Kumar Sahu

Harikesh Singh

Mohammad Saqlain 

Rameez Raza Khan

Ravi Kumar

Vansh Rastogi  

Deepak Kumar

Pragyansh Agniotri 

Pramod

Gaurav Sagar     

 B.Tech (CSE) Section E (Academic Year 2025–2026)

                          ABSTRACT
Project Title: Credit Card Fraud Risk Analysis
Domain: Data Analytics, Business Intelligence, FinTech, Fraud Detection
Technology Stack: Power BI, Power Query, DAX, Microsoft Excel, CSV Dataset

Abstract
With the rapid growth of online payments, e-commerce, and digital banking, the number of credit card transactions has increased dramatically. Along with genuine usage, there has also been a significant rise in fraudulent transactions, leading to financial losses for banks as well as customers. Traditional manual monitoring systems are often slow, reactive, and unable to handle large-scale data in real time.
This project focuses on designing a Credit Card Fraud Risk Analysis Dashboard using Power BI. The main objective is to analyze transaction-level data and derive meaningful visual insights that help identify suspicious patterns, high-risk customers, risky merchants, and fraud-prone time periods.
The dataset used in this project consists of transaction details such as transaction amount, time, location, merchant category, transaction mode, and fraud label (fraud / non-fraud). The data is cleaned and transformed using Power Query, and then modeled in Power BI using DAX measures and relationships. Multiple visualizations such as bar charts, line charts, donut charts, slicers, and KPI cards are used to represent risk metrics.
The final dashboard allows users to explore fraud trends interactively, compare fraud vs non-fraud transactions, and analyze fraud distribution across amount ranges, time of day, regions, and merchant types. This analytical approach supports data-driven decision-making for banks and financial institutions and demonstrates how BI tools can improve fraud risk monitoring in a cost-effective way.
Keywords: Credit Card Fraud, Fraud Detection, Risk Analysis, Power BI, Data Visualization, Financial Analytics, Business Intelligence.
 





                        TABLE OF CONTENTS
1	CHAPTER 1: INTRODUCTION 
1.1	Background ....................................................................................... 

1.2	Motivation ........................................................................................

1.3	Problem Statement ........................................................................... 

1.4	Objectives ........................................................................................

1.5	Scope of the Project ......................................................................... 

1.6	Project Overview ............................................................................. 

2	CHAPTER 2: LITERATURE REVIEW 

2.1	Existing System Analysis ................................................................. 

2.2	Research Gap ................................................................................... 

3	CHAPTER 3: METHODOLOGY 

3.1	Data Collection ............................................................................... 

3.2	Data Cleaning & Preprocessing ..................................................... 

3.3	Data Modeling (Pivot Tables / Power Query) ............................... 

3.4	Dashboard Designing Process ......................................................

4	CHAPTER 4: SYSTEM DESIGN 

4.1	Tools & Technologies Used ............................................................ 

4.2	ER / Data Flow Diagram ................................................................ 

4.3	Architecture of Dashboard .............................................................. 

5	CHAPTER 5: IMPLEMENTATION 

5.1	KPI (Key Performance Indicator) Setup ......................................... 

5.2	Disease Distribution Chart ............................................................. 

5.3	Age Group Distribution Chart ....................................................... 

5.4	Gender Distribution Chart .............................................................. 

5.5	Hospital Performance Chart .......................................................... 

5.6	Cost & Critical Patient Analysis .................................................... 

6	CHAPTER 6: RESULTS & ANALYSIS 

6.1	Dashboard Output Screenshots ...................................................... 

6.2	Insights / Observations .................................................................. 

7	CHAPTER 7: CONCLUSION & FUTURE SCOPE 

7.1	Conclusion ...................................................................................... 

7.2	Limitations ..................................................................................... 

7.3	Future Scope .................................................................................. 

8	REFERENCES ..................................................................................... 

9	ANNEXURES / APPENDIX (Raw Data & Code) .............................




CHAPTER 1: INTRODUCTION
1.1 Background
Digital payments have transformed the way financial transactions are carried out. Credit cards are widely used for online shopping, bill payments, subscriptions, and POS transactions. While this convenience has improved user experience, it has simultaneously opened new doors for fraudsters. Techniques like card theft, skimming, phishing, data breaches, and identity theft are commonly used to commit fraud.
Banks and financial organizations generate huge volumes of transaction data every day. If this data is properly analyzed using tools like Power BI, it can reveal hidden patterns and help in identifying high-risk transactions. Instead of relying only on manual checking or static reports, a visual dashboard can provide faster and clearer insights into fraud behavior, which is essential in the era of digital banking.
1.2 Motivation
Credit card fraud results in financial loss, customer dissatisfaction, and loss of trust in digital systems. Many frauds go unnoticed until the customer or bank manually detects them, by which time the damage is already done.
The motivation behind this project is:
•	To use data analytics to better understand fraud patterns instead of guessing.
•	To show how Power BI can be used as a fraud monitoring tool, even without complex coding.
•	To build a clear, interactive dashboard that can support bank officers in quickly spotting suspicious behavior.
•	To gain hands-on experience with real-world financial data analysis, which is highly relevant in the FinTech and IIoT domains.
1.3 Problem Statement
Although banks collect detailed transaction records, they often lack a simple and interactive system to visually analyze fraud trends:
•	Data is stored across multiple files and systems.
•	Many existing reports are static and cannot be filtered dynamically.
•	Financial analysts may need to manually check large tables, which is time-consuming.
Problem:
How can we design a Power BI-based dashboard that analyzes credit card transaction data and helps in identifying fraud risk patterns in an interactive and understandable way?
1.4 Objectives
The main objectives of this project are:
1.	To clean, organize, and analyze credit card transaction data.
2.	To compare fraud and non-fraud transactions based on various factors like amount, time, location, and merchant type.
3.	To design KPIs and visualizations that clearly show fraud trends and high-risk segments.
4.	To develop an interactive Power BI dashboard with filters and slicers for flexible analysis.
5.	To generate actionable insights that can support fraud detection strategies and customer risk management.
1.5 Scope of the Project
•	The project focuses on historical transaction data, not live real-time monitoring.
•	It covers descriptive and diagnostic analytics, not full machine learning-based prediction.
•	The dashboard is designed as a decision-support visualization tool for analysts and managers.
•	The project is suitable for academic demonstration of Power BI skills, data cleaning, modeling, and financial analytics.
1.6 Project Overview
The project begins with data collection from a credit card transaction dataset (e.g., publicly available Kaggle dataset or synthetic data). The data is then cleaned and preprocessed using Power Query. Next, a data model is created in Power BI, with relationships, calculated columns, and DAX measures.
Finally, multiple reports and dashboard pages are designed to show fraud vs non-fraud trends, top risky merchants, amount distribution, and time-based fraud behavior. The report ends with results, conclusion, limitations, and future scope.


CHAPTER 2: LITERATURE REVIEW
2.1 Existing System Analysis
Existing fraud detection systems in banks generally include:
•	Rule-based systems (e.g., if amount > X at unusual location, flag).
•	Manual reviews by fraud analysts going through alerts and reports.
•	Static MIS reports generated periodically in Excel or other tools.
Limitations:
•	Rules may become outdated and do not adapt to new fraud patterns.
•	Manual checking is slow, tiring, and error-prone.
•	Data from different channels (ATM, POS, online) may not be integrated properly.
•	Visual representation is limited, making it hard for managers to quickly see overall fraud risk.
2.2 Research Gap
From studying various articles, blogs, and academic papers on fraud detection:
•	Most focus on complex machine learning models, but ignore simple visual dashboards for day-to-day analysis.
•	Many solutions are costly and complex, not suitable for small banks or educational demonstration.
•	There is a lack of simple, low-cost, Power BI-based analytic dashboards that allow quick exploration of fraud trends.
This project tries to fill this gap by providing a clear and easy-to-use Power BI dashboard for credit card fraud risk analysis.

 
CHAPTER 3: METHODOLOGY
3.1 Data Collection
•	Dataset of credit card transactions with fields like:
o	Transaction ID
o	Customer ID
o	Transaction Date & Time
o	Transaction Amount
o	Merchant Category
o	Transaction Type (Online, POS, ATM, etc.)
o	Country / City
o	Fraud Flag (0 = Non-Fraud, 1 = Fraud)
•	Data source:
o	Public dataset (e.g., Kaggle) or synthetic/fake data generated for project purposes.
3.2 Data Cleaning & Preprocessing
Goals of cleaning:
1.	Remove duplicate transactions.
2.	Handle missing values (amount, merchant, etc.).
3.	Ensure correct data types (date, number, category).
4.	Standardize merchant categories and location names.
5.	Add derived columns useful for analysis.
Typical steps in Power Query:
•	Import raw CSV/Excel file into Power BI.
•	Remove blank and duplicate rows.
•	Replace null amounts with 0 or remove invalid rows.
•	Convert date-time to separate Date and Hour columns.


•	Create new columns such as:
o	Amount Range (Low, Medium, High)
o	Time Slot (Morning, Afternoon, Evening, Night)
3.3 Data Modeling (Power BI & DAX)
•	Create a Fact Table for transactions and dimension tables for:
o	Date
o	Customer
o	Merchant
o	Location
•	Establish relationships between tables.
•	Define DAX measures, such as:
o	Total Transactions
o	Total Fraud Transactions
o	Fraud Percentage
o	Total Fraud Amount
o	Average Transaction Amount
3.4 Dashboard Designing Process
Steps followed:
1.	Identify KPIs to display on the dashboard.
2.	Choose suitable charts for each analysis (bar, line, donut, map).
3.	Arrange visual elements on the report page in a clean layout.
4.	Add slicers for filters like Date, Country, Merchant Category, Fraud Flag.
5.	Format visuals with proper titles, labels, legends, and tooltips
 
CHAPTER 4: SYSTEM DESIGN
4.1 Tools & Technologies Used
•	Power BI Desktop – main dashboard tool.
•	Power Query – data cleaning and transformation.
•	DAX – calculations and measures.
•	Microsoft Excel / CSV – source data.
•	PowerPoint / Word – report and presentation.
4.2 Data Flow Diagram (Conceptual Description)
1.	Input: Transaction dataset in CSV/Excel.
2.	Power Query: Clean and transform data.
3.	Data Model: Build relationships and measures in Power BI.
4.	Visualization Layer: Create charts, KPIs, maps.
5.	User Interaction: Apply filters and analyze fraud trends.
4.3 Architecture of the Dashboard
•	Data Layer: Transaction dataset.
•	Processing Layer: Power Query + DAX.
•	Visualization Layer: Charts, tables, KPI cards, slicers.
•	User Layer: Analyst/manager using the dashboard to view fraud risk.
.

 
CHAPTER 5: IMPLEMENTATION
5.1 KPI (Key Performance Indicator) Setup
Main KPIs used:
•	Total Transactions
•	Total Fraud Transactions
•	Fraud Percentage
•	Total Fraud Amount (₹)
•	Average Fraud Amount (₹)
Each KPI is shown using Card visuals in Power BI.

5.2 Fraud Distribution by Transaction Type
•	Visual: Donut / Pie Chart
•	Categories: Online, POS, ATM, Contactless, International, etc.
•	Purpose: To see which transaction type has the highest fraud share.

5.3 Fraud Analysis by Amount Range

•	Visual: Bar Chart
•	Amount Ranges:
o	0–1000
o	1001–5000
o	5001–10000
o	Above 10000
•	Helps to identify whether fraud is more common in small, medium, or high-value transactions.
5.4 Time-Based Fraud Analysis

•	Visual: Line or Column Chart
•	X-axis: Time of day or date.
•	Y-axis: Number of frauds.
•	Shows peak hours or peak days when fraud is more frequent.

5.5 Customer Segment & Location-Based Risk

•	Visual: Map / Bar Chart
•	Shows fraud count per country, state, or city.
•	Also can show risk by customer segment (e.g., new customers, high spenders).

 
CHAPTER 6: RESULTS & ANALYSIS
6.1 Dashboard Output Screenshots (Explain in words)
This section presents the visual representation of the Credit Card Fraud Risk Analysis carried out using Microsoft Power BI. The dashboard contains multiple KPIs and analytical charts that help in understanding fraud trends, risk levels, transaction categories, and geographic distribution.
The following figures highlight different aspects of credit card fraud patterns, including fraud types, risk segmentation, monthly variation, and state-wise distribution
Figure 6.1: Complete Fraud Analysis Dashboard Overview
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/4928fadf-39a5-49c8-bb1e-cc4174854413" />

 This figure displays the overall dashboard layout showing filters, KPIs, charts, and visual analytics. It gives a complete overview of fraud rate, total fraudulent transactions, and top fraud types detected in the dataset




Figure 6.2: Fraud Detection KPI Summary
<img width="940" height="116" alt="image" src="https://github.com/user-attachments/assets/bc026cf8-24c9-4da5-9b8f-b2dc17c61c60" />

 This chart showcases the major KPIs including Fraud Rate %, Total Fraudulent Transactions, Critical Risk Transactions, Total Fraudulent Amount, and Top Fraud Type. These KPIs provide a quick summary of the fraud status and overall risk level.
Figure 6.3: Fraud Type vs Transaction Category


 This visual compares different fraud types—such as Card Not Present, Card Skimming, Identity Theft, Account Takeover, and Phishing—across various transaction categories like Apparel, Electronics, Groceries, E-commerce, and Transportation.
It helps identify which fraud type is most frequent in specific purchasing categories.







Figure 6.4: Fraud Risk Level Distribution
 <img width="673" height="408" alt="image" src="https://github.com/user-attachments/assets/28d6657e-75c1-4646-a6c7-5674fbd5af9d" />

This donut chart divides the fraudulent transactions into four major risk levels: Low, Medium, High, and Critical.
It highlights that while low-risk transactions are most common, high and critical risk transactions form a significant portion and require immediate attention.
Figure 6.5: Fraudulent Transactions by State
<img width="940" height="397" alt="image" src="https://github.com/user-attachments/assets/d69ae13b-f7d8-44f0-bfed-0ef1cb42fb6b" />

 This chart displays the number of fraudulent transactions recorded in different states such as Maharashtra, Karnataka, Rajasthan, West Bengal, and Uttar Pradesh.
It helps identify which states are more prone to card fraud activities.


Figure 6.6: Monthly Trend of Fraudulent Transactions
 <img width="677" height="411" alt="image" src="https://github.com/user-attachments/assets/74a1f74d-46c1-40b8-bdc9-d79b36cfe8f3" />

This line chart shows the monthly fluctuation of fraudulent transactions. The trend indicates peaks during mid-year months and a significant high in December, suggesting increased risk during festive and holiday seasons.

6.2 Insights / Observations 
1.	Fraud Rate is High:
The dashboard shows a fraud rate of 28.60%, indicating that a large portion of total transactions are fraudulent.
2.	Card Not Present is the Top Fraud Type:
The most common fraud type is Card Not Present, which usually occurs in online or remote transactions.
3.	Total Fraud Amount is Very Large:
The total fraudulent transaction amount is 3M, showing a major financial loss risk.
4.	Fraud Cases are Higher in Certain States:
States like Maharashtra, Karnataka, Rajasthan, and West Bengal have the highest number of fraudulent transactions.
5.	Monthly Fraud Trend Shows Peaks:
Fraud cases are lower in January but significantly increase in July, August, and December.
6.	Risk Level Distribution is Clearly Defined:
Fraud is divided into Low, Medium, High, and Critical risk levels, with Low being the highest percentage, but High and Critical risks still being concerning.
 
CHAPTER 7: CONCLUSION & FUTURE SCOPE
7.1 Conclusion
The Credit Card Fraud Risk Analysis project successfully demonstrates how Power BI can be used to transform raw transaction data into interactive visual insights. By cleaning, modeling, and visualizing the data, it becomes easier to:
•	Understand fraud behavior.
•	Identify risky transaction types and regions.
•	Support decision-making for banks and financial institutions.
This work proves that even without heavy coding, BI tools can play an important role in fraud monitoring systems.
7.2 Limitations
•	Uses historical data only; no real-time streaming.
•	The dataset may be synthetic or limited in size.
•	The project focuses on visual analytics, not deep machine learning prediction.
7.3 Future Scope
•	Integrate real-time transaction data using IIoT and API-based streaming.
•	Apply machine learning models for automatic fraud prediction.
•	Add alert systems that notify when risk exceeds a threshold.
•	Deploy the dashboard as a web or mobile app for bank officers.

 
                           REFERENCES
1.	Dal Pozzolo, A., Boracchi, G., Caelen, O., Alippi, C., & Bontempi, G. (2018). Credit Card Fraud Detection and Concept Drift Adaptation. Elsevier Expert Systems with Applications.
2.	Carcillo, F., Dal Pozzolo, A., Le Borgne, Y. A., Caelen, O., Mazzer, Y., & Bontempi, G. (2021). Scarff: A Scalable Framework for Streaming Credit Card Fraud Detection. Information Systems Journal.
3.	Kaggle. (2018). Credit Card Fraud Detection Dataset.
Available at: https://www.kaggle.com/mlg-ulb/creditcardfraud
4.	Microsoft Power BI Documentation. (2023). Power BI Desktop – Data Modeling, DAX, and Visualization Tools.
Available at: https://learn.microsoft.com/en-us/power-bi/
5.	Bhattacharyya, S., Jha, S., Tharakunnel, K., & Westland, J. C. (2011). Data Mining for Credit Card Fraud: A Comparative Study. Decision Support Systems, Elsevier.
6.	Sahu, S., & Dash, S. (2020). A Study on Online Payment Fraud Detection Using Machine Learning Techniques. International Journal of Computer Applications.
7.	Ryman-Tubb, N. F., Krause, P., & Garn, W. (2018). How Artificial Intelligence and Machine Learning Research Impacts Payment Card Fraud Detection: A Survey and Industry Benchmarks. IEEE.
8.	Bank for International Settlements (BIS). (2020). Fraud Risk Management in Digital Payments.
9.	Analytics Vidhya. (2023). Understanding Credit Card Fraud Detection and Key Risk Indicators.
10.	Towards Data Science. (2021). Visual Analytics for Financial Fraud Detection Using Power BI.

 
            ANNEXURES / APPENDIX
________________________________________
Appendix A – Raw Dataset (Excel/CSV File)
•	The raw dataset used for this project contains credit card transaction records, which include both genuine and fraudulent transactions.
•	It consists of attributes such as Transaction ID, Customer ID, Amount, Merchant Category, Transaction Type, Date & Time, State, and Fraud Flag (0 = Non-Fraud, 1 = Fraud).
•	The dataset was stored and processed in Microsoft Excel / CSV format before data cleaning and visualization.
•	Each record represents a single credit card transaction and forms the foundation for all fraud-risk analysis performed in Power BI.
•	The dataset was imported into Power BI for transformation, modeling, and dashboard creation.
________________________________________
Appendix B – Data Preparation / Fake Dataset Logic (If Dataset is Synthetic)
Since detailed real-world credit card fraud datasets are not publicly available due to privacy and banking security concerns, a synthetic dataset was prepared for analytical and academic purposes.
The fake dataset was designed to mimic real financial transaction behavior and commonly observed fraud patterns.
Data Generation Logic:
1.	Base Transaction Count:
A starting transaction count was assumed and expanded with random variations to simulate real activity.
2.	Fraud Percentage Logic:
o	Fraud Rate set between 1% – 30%, depending on category and risk type.
o	Fraud Flag assigned using probability-based random distribution.
3.	Amount Range Distribution:
o	Low Value: 100 – 1000
o	Medium Value: 1001 – 5000
o	High Value: 5001 – 20000
Higher value transactions have a slightly higher probability of being classified as fraud.
4.	Fraud Type Logic:
Fraud types were distributed based on realistic financial patterns:
o	Card Not Present
o	Card Skimming
o	Identity Theft
o	Account Takeover
o	Phishing
5.	State Distribution:
Fraud cases were distributed across Indian states such as Maharashtra, Karnataka, Rajasthan, West Bengal, and Uttar Pradesh, according to typical digital-fraud trends.
6.	Timestamp Logic:
Transactions were assigned random dates and times to generate a realistic monthly trend and identify fraud spikes.
7.	Rounding and Validation:
All values were validated and formatted properly before using the dataset for dashboard creation.
________________________________________
Appendix C – Final Dashboard Layout
This appendix presents the final layout of the Credit Card Fraud Risk Analysis dashboard created in Microsoft Power BI.
The dashboard includes:
•	KPI Cards: Fraud Rate, Total Fraud Transactions, Critical Risk %, Total Fraud Amount, Top Fraud Type.
•	Charts:
o	Fraud Type vs Transaction Category
o	Fraud Risk Distribution (Donut Chart)
o	State-wise Fraud Cases
o	Monthly Fraud Trend
•	Filters / Slicers: Fraud Type, State, Merchant Name
•	Visual Theme: Dark background theme for better clarity and contrast.
 <img width="940" height="533" alt="image" src="https://github.com/user-attachments/assets/07ec318c-b519-406e-aafb-ae67f596a468" />



