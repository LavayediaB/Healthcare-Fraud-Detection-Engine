# Healthcare-Fraud-Detection-Engine
An end-to-end Python pipeline designed to identify financial risk and administrative errors in inpatient healthcare claims. This project demonstrates the application of statistical inference to healthcare compliance.

Key Technical Features:
Data Audit: Automated detection of overlapping claims (Double Billing) and invalid financial records.

Statistical Outlier Detection: Utilized the 3-Sigma Rule to isolate claims exceeding R41,000 (3 standard deviations from the mean).

Provider Risk Profiling: Aggregated 40,000+ rows to rank providers by financial impact and average claim cost.

Visualization: Developed a risk-matrix scatter plot using Seaborn.

Key Findings: Identified 74 potential duplicate claims for immediate administrative review.Flagged 1,034 high-risk anomalies representing the top 3% of financial exposure. Isolated Provider PRV51067 as a primary audit target with an average claim cost 2.7 times the population mean.
