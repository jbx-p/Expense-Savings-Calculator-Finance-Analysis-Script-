# Expense-Savings-Calculator-Finance-Analysis-Script-
A Finance tracker script lets the user input monthly income, profits, and a set of recurring expenses, then calculates total expenses and possible savings
Overview
This Python script provides a comprehensive financial analysis tool to help users track and manage their expenses and savings on both monthly and yearly bases. The program calculates net income, cost of living, and recommended savings based on user input, offering valuable insights into personal financial health.

How It Works
1. Initial Setup
The script begins by defining a default monthly expenses dictionary containing common bill categories with sample values:

Rent, utilities (electricity, water, internet)

Personal expenses (phone, transportation, personal care)

Lifestyle costs (food, entertainment, gym)

Miscellaneous expenses

2. Yearly Analysis Function (yearly())
This function provides an annual financial overview through the following steps:

Step 1: Income Calculation

Prompts for monthly paycheck amount

Multiplies by 12 to determine yearly income

Calculates yearly profit from side hustles (assumed to be defined elsewhere as profit)

Computes gross income by combining salary and profit

Step 2: Tax and Net Income

Asks for yearly tax amount

Subtracts tax from gross income to determine net income

Step 3: Cost of Living Analysis

Sums all monthly bills from the predefined dictionary

Multiplies by 12 for yearly total

Calculates remaining income after subtracting cost of living

Step 4: Savings Recommendation

Allocates 40% of remaining income to savings

Calculates final spending balance

Displays comprehensive yearly financial summary

3. Monthly Analysis Function (monthly())
This function offers granular monthly financial tracking:

Step 1: Income Input

Collects monthly paycheck and side hustle profit

Calculates total monthly income

Step 2: Customized Expense Tracking

Prompts for individual bill amounts in each category

Creates a personalized expenses dictionary

Converts expenses to a readable list format for review

Step 3: Financial Health Check

Compares total expenses to total income

Alerts if expenses exceed income (living above means)

Calculates remaining funds after expenses

Step 4: Savings Analysis

Recommends saving 40% of remaining income

Provides motivational feedback based on savings amount

Encourages expense reduction if savings are negative

Key Features
Dual Timeframe Analysis: Both monthly and yearly perspectives

Customizable Input: Users can adjust all financial values

Automated Calculations: Handles all mathematical operations

Financial Health Alerts: Warns when expenses exceed income

Savings Guidance: Recommends 40% savings from disposable income

Clear Breakdowns: Presents expenses in readable formats

Usage Example
When running the yearly function with a $25,000 monthly paycheck and $5,000 monthly profit:

Yearly net income: $362,380 (after $12,000 tax)

Yearly cost of living: $62,400

Yearly savings (40%): $119,992

Remaining spending money: $179,988

Financial Strategy
The script implements a balanced approach to personal finance:

Cover Essentials: Calculate and deduct cost of living

Prioritize Savings: Allocate 40% of remaining income to savings

Balance Spending: Use remaining 60% for discretionary expenses

This tool helps users visualize their financial flow, identify potential issues, and maintain healthy saving habits regardless of income level.
