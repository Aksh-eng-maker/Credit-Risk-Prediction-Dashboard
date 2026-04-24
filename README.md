# Credit Risk Predictive Suite
End-to-End Financial Analytics & Machine Learning
This project delivers a comprehensive credit risk assessment tool designed to help financial institutions identify high-risk borrowers. By combining Python-driven predictive modeling with Power BI visualizations, the suite transforms 30,000+ raw records into actionable lending insights.

## Project Overview
The goal of this analysis was to predict the likelihood of loan default and quantify the financial exposure of "at-risk" capital. I utilized a combination of exploratory data analysis (EDA), machine learning classification, and interactive dashboarding to bridge the gap between technical metrics and executive decision-making.

## Technical Stack
Data Engineering: Excel (initial cleaning, validation), Python (Pandas)

Machine Learning: Scikit-Learn (Classification, Model Evaluation)

Visualization: Power BI (DAX, Interactive Dashboarding)

## The Analytics Workflow
1.Data Cleaning & Integrity:Excel / Python.Validated 30,000 borrower records for missing values and outliers. Handled skewed income data using logarithmic transformations to improve model stability.
2.Predictive Modeling:Python (Scikit-Learn).Developed a classification model to identify high-risk clusters. Optimized for Recall, ensuring the model captures as many potential defaults as possible to minimize bank losses.
3.Dashboard Engineering:Power BI.Connected the modeled data to an interactive dashboard. Built KPIs for Global Default Rate and Total Capital Exposure, allowing stakeholders to filter risk by income level and loan intent.

## Key Findings & Impact
Model Accuracy: Successfully identified high-risk borrower clusters representing 15% of total loan volume.

Operational Efficiency: Automated the risk categorization process, reducing manual review time for "Low Risk" applications by an estimated 40%.

## Repository Structure
/Data: Raw and processed datasets (CSV/Excel).

/Notebooks: Python Jupyter Notebooks containing the ML model and EDA.

/Dashboard: The .pbix Power BI file.

/Exports: Screenshot of the final dashboard for quick viewing.
