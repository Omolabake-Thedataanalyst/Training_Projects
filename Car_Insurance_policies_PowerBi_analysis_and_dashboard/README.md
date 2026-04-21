# Insurance Claims & Risk Analysis: A Strategic Data Perspective

## Executive Summary
This project analyzes a comprehensive dataset of over 37,500 insurance policies to evaluate business performance and customer risk profiles. The analysis reveals a state of Risk Uniformity, where claim frequency remains consistent at ~51% across most demographics, despite varying total volumes. The core finding identifies that 72.4% of the portfolio drives zero claims, representing the primary engine of business profitability.

## Business Problem

The objective was to move beyond raw data to provide actionable insights for an insurance firm. The business needed to:
* Identify high-risk customer segments.
* Evaluate the impact of vehicle characteristics (age and make) on claim frequency and severity.
* Provide data-driven recommendations to optimize pricing strategies and risk management.

## Methodology

* Data Cleaning & Transformation: Utilized Power Query to handle null values, duplicates, and standardize currency formats.
* Feature Engineering: Created calculated columns for Customer Age, Customer Age Categories (Young Adult, Middle Age, Senior), Household Income Categories (Low Income, High Income, Middle Income, Executive Income), Vehicle Age, and Vehicle Age Categories (Modern, Mid-Life, Classic, Vintage) using DAX.
* Measure Development: Developed complex DAX measures for Total Claim Amount, Average Claim Amount, Distinct Policy Counts, and Total Claim Frequency to ensure data integrity.
* Performance Optimization: Utilized the Performance Analyzer to ensure rapid visual rendering and efficient query execution.
* Visualization: Developed an interactive single-page dashboard focusing on Executive KPIs and the multidimensional analysis of risk factors across demographic, geographic, and vehicle characteristics.

## Specific Skills Demonstrated

* Data Modeling: Creating relationships between demographic factors and financial outcomes.
* Advanced DAX: Implementing logic-based grouping (SWITCH)
* Business Intelligence: Translating technical metrics (Frequency/Severity) into business language (Profitability/Risk).
* UI/UX Design: Implementing bookmarks and "Clear All Filter" buttons for enhanced user interactivity.

## Results and Insights

* The 72% Profit Center: 27,203 users have zero claims, yet represent the majority of the policy base.
* Risk Uniformity: Demographic markers (Age, Gender, Education, Income) show a remarkably stable claim rate of 51%.
* Exposure vs. Payout: Identified that "Total Claim Amount" likely represents the Maximum Policy Coverage rather than actual cash loss, as zero-frequency users still carry associated dollar values.
* Vehicle Impact: Mid-life vehicles (11–25 years) represent the bulk of the fleet, but vintage car makes carry a 58% higher financial exposure ($7,905 vs $5,000 average).

## Business Recommendations

* Retention Strategy: Launch loyalty programs specifically targeting the 72% of "Zero-Claim" drivers to protect high-margin revenue.
* Strategic Pricing: Pivot from demographic-based pricing (which shows uniform risk) to Asset-Based Pricing, focusing on vehicle rarity and age.
* Data Governance: Audit database field definitions to clearly distinguish between Potential Liability (Coverage) and Actual Loss (Claims paid).

## Next Steps

* Predictive Modeling: Use Python (Scikit-Learn) to build a classification model to predict which customers are likely to transition from 0 to 1+ claims.
* Correlation Analysis: Deep dive into the relationship between household income and vehicle rarity to find "Ultra-High Exposure" niches.

## Tools Used

* Power BI Desktop: Data visualization and DAX modeling.
* Power Query: ETL (Extract, Transform, Load) processes.
* Microsoft PowerPoint: Stakeholder communication and storytelling.

GitHub: Version control and documentation.

Microsoft PowerPoint: Stakeholder communication and storytelling.
