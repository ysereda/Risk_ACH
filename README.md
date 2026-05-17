# Risk_ACH
## Overview
This notebook demonstrates an end-to-end risk analytics workflow aligned with the responsibilities of a Risk & Payments Intelligence Analyst role in fintech and payment processing environments.

The project highlights:

* ACH payment risk analytics
* Fraud and loss trend analysis
* ML risk score evaluation
* Portfolio monitoring
* Cohort and behavioral analysis
* SQL-style data aggregation
* Python-based exploratory analytics
* Decision strategy evaluation
* Analytical automation workflows

The workflow simulates a production-style payments intelligence environment using Python, pandas, NumPy, and machine learning techniques commonly used in fintech risk analytics.

## Business Objective
The objective is to evaluate ACH payment decisioning performance and identify:

* Drivers of payment losses
* Risk patterns by customer segment
* High-risk transaction cohorts
* Performance of ML risk scores
* Impact of approval thresholds on fraud losses
* Operational opportunities to improve portfolio outcomes

## Features
+ transactions_30d: Number of transactions performed by the customer in the last 30 days.
+ chargebacks_90d: Number of chargebacks, disputes, or returned ACH payments associated with the customer in the past 90 days.
+ bank_account_age_days: Age of the linked bank account in days.
+ device_risk_score: Risk score associated with the device used for the transaction.
+ velocity_score: Measures how rapidly activity is occurring.
+ vendor_risk_score: Risk score from external vendors or third-party data providers.
+ geo_risk_score: Risk score based on geographic indicators.
