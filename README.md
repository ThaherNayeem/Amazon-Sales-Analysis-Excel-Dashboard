# Amazon-Sales-Analysis-Excel-Dashboard
Analyzed 500+ Indian banking transactions using Excel. Built 7 pivot tables and an interactive dashboard covering regional trends, branch performance, channel usage (UPI, ATM, Online), fraud detection, and transaction status breakdown. Techniques used: data cleaning, pivot tables, charts, and KPI dashboards
#Problem Statement

India's banking industry processes billions of digital transactions every month. The goal of this project is to convert raw banking transaction data into meaningful business insights using Excel — helping the bank answer critical questions around regional trends, branch performance, fraud detection, and channel usage.


#Business Objectives


Analyze transaction trends across branches and regions
Identify fraud-prone accounts and patterns
Evaluate the performance of digital vs branch-based channels
Track the status of transactions (Completed, Failed, Reversed)
Build a comprehensive Excel dashboard to visualize key banking KPIs

Dataset Overview

FieldDescriptionTransaction IDUnique identifier per transactionCustomer NameAccount holder's nameAccount NumberUnique bank account numberTransaction DateDate of the transactionTransaction TypeDeposit, Withdrawal, TransferAmountTransaction amount in INRChannelUPI, ATM, Online Banking, Branch, Mobile AppRegionNorth, South, East, West, CentralBranch NameIndian city branch nameTransaction StatusCompleted, Failed, Reversed, PendingIs FraudYes/No fraud flag

Total Records: 500 transactions


#Project Workflow

#Step 1: Data Understanding


Reviewed all dataset columns and understood their business relevance
Identified data types — numeric, date, categorical
Classified fields as transactional, customer-level, or derived


#Step 2: Data Cleaning


Removed duplicate rows based on Transaction ID
Handled missing values and unknown statuses
Standardized naming conventions across branch names and regions
Converted Transaction Date column from text to date format


#Step 3: Pivot Tables Created

#Pivot TablePurposePT1Regional Transaction VolumeWhich region has most transactionsPT2Monthly Transaction TrendsWhich month has most transactionsPT3Branch VolumeHighest and lowest performing branchesPT4Transaction Type BreakdownDeposits vs Withdrawals vs TransfersPT5Fraud Analysis by BranchFraud vs safe transactions per branchPT6Channel PerformanceUPI vs ATM vs Online vs Branch vs MobilePT7Transaction Status BreakdownCompleted vs Failed vs Reversed vs Pending

#Step 4: Dashboard Built


Combined all 7 charts into a single interactive Excel dashboard
Added KPI cards for total transactions, fraud rate, success rate, and top channel
Used bar charts, line charts, donut charts, pie charts, and stacked bar charts



#Key Insights


North region has the highest transaction volume (110 transactions)
East region has the lowest transaction volume (94 transactions)
UPI is the most used channel with 142 transactions (28%)
Mobile App is the least used channel with only 54 transactions (11%)
Delhi CP branch is the most fraud-prone with 8 fraud cases
8% overall fraud rate detected across all transactions
70% success rate — 350 out of 500 transactions completed successfully
17% failed transactions — needs urgent attention from the operations team
Deposits (35%) are the most common transaction type



#Recommendations


Invest in Mobile App — only 11% usage suggests the app needs better UI and marketing
Investigate Delhi CP branch — highest fraud cases, needs immediate security audit
Reduce failed transactions — 17% failure rate is too high, investigate technical issues
Focus on North and West regions — highest transaction volumes, need more resources
Promote UPI — already the top channel, further investment will increase digital adoption
Monitor reversed transactions — 8% reversal rate needs process improvement
