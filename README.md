# A-B-test-conversion-analysis
A/B Test: Purchase Funnel Conversion Analysis

Statistical analysis of A/B test results, testing the significance of conversion changes across purchase funnel stages, visualized in an interactive Tableau dashboard.
What was done:

🔗 Connected to BigQuery via Google Colab

🧪 Two-proportion z-tests across four key funnel metrics:


add_payment_info/session

add_shipping_info/session

begin_checkout/session

new_accounts/session


📊 Built a per-metric-per-test results table
📈 Interactive Tableau dashboard: color-coded statistical significance, test number filter, embedded analysis documentation

Key steps:

Formulated hypotheses (H0/H1) for each metric.
Calculated p-values and tested significance at a set confidence level.
Visualized results for easy interpretation by business stakeholders.

Stack: Python (pandas, statsmodels/scipy), Google Colab, BigQuery, Tableau
