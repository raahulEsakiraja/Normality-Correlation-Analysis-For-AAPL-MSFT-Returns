# Normality-Correlation-Analysis-For-AAPL-MSFT-Returns
This project investigates the distribution and correlation structure of daily stock returns for Apple (AAPL) and Microsoft (MSFT), focusing on the validity of normality assumptions and their impact on statistical interpretation. Using the Shapiro-Wilk and Jarque-Bera tests, we find strong evidence that both return series significantly deviate from normality due to skewness and kurtosis, despite W statistics being relatively close to 1. This violation of normality is critical, as commonly used correlation measures like Pearson’s coefficient rely on those assumptions.

Our analysis shows a strong positive correlation (~0.7) between AAPL and MSFT returns under Pearson’s method, but noticeable discrepancies emerge when comparing this with non-parametric methods like Spearman’s rho and Kendall’s tau. These gaps suggest that outliers and distribution shape materially influence the correlation structure. As a result, we recommend using robust, rank-based correlation measures for financial data, which better reflect underlying relationships without being distorted by non-normality. This study emphasizes the importance of aligning statistical tools with the characteristics of the data in order to produce reliable insights in financial analysis.
