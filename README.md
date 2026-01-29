Loan Distribution Analysis of Garima Bikas Bank Limited (GBBL)
This project provides a comprehensive data analysis of the loan portfolio of Garima Bikas Bank Limited (GBBL), a prominent national-level development bank in Nepal. The study examines historical loan distribution trends, identifies patterns in various lending sectors, and assesses portfolio volatility over multiple fiscal years.

Table of Contents
Project Overview

About the Organization

Key Features

Dataset Description

Analysis and Insights

Technologies Used

How to Run

Project Overview
The primary objective of this project is to analyze how loan capital is distributed across different sectors such as Margin Lending, Real Estate, and Personal Hire Purchase. The analysis focuses on understanding growth trends, assessing risk through volatility measures (Coefficient of Variation), and visualizing the shift in the bank's lending priorities from Fiscal Year 2077 to 2080.

About the Organization
Garima Bikas Bank Limited commenced operations in 2064 (Nepali Calendar) and has grown into a national-level development bank through strategic mergers and acquisitions.

Headquarters: Lazimpat, Kathmandu.

Network: 123 branches and 51 ATMs across Nepal.

Motto: "Access to All".

Key Features
Data Cleaning: Automated filtering of non-loan data (e.g., Capital Adequacy, Shareholding Structure) using regular expressions.

Sector-wise Analysis: Detailed breakdown of loan types including Deprived Sector Loans, Residential Real Estate, and Business Term Loans.

Volatility Assessment: Calculation of the Coefficient of Variation (CV) to measure portfolio stability.

Visualizations:

Stacked Area Charts: To visualize the distribution of loan types over time.

Growth Trend Analysis: Year-over-Year (YoY) growth calculations for specific high-volatility sectors.

Dataset Description
The analysis utilizes a dataset (processed via Pandas) containing:

Fiscal Year: Ranging from 2077 to 2080.

Loan Type: Various categories defined by Nepal Rastra Bank (NRB).

Loan Amount: Total principal lent in NPR.

Analysis & Insights
The project revealed several critical findings:

Portfolio Volatility: The overall loan portfolio showed a high level of volatility with a Coefficient of Variation (CV) of 0.7357.

Margin Lending: This sector experienced extreme fluctuations, with a 337% growth in 2077 followed by a 21.6% decline in 2078.

Risk Management: The high volatility suggests a need for enhanced stress testing and risk assessment for specific segments like "Margin Lending" to maintain bank stability.

Technologies Used
Python: Core programming language.

Pandas: For data manipulation and pivot table creation.

Matplotlib & Seaborn: For generating stacked area charts and statistical plots.

Regex (re): For advanced data cleaning and filtering.
