# Telecom-Customer-Churn-project

## Description:

This project to identify the churn reasons that are provided by the churned customers and further analyze those reasons with other factors available in the dataset to create data-driven conclusions.

## Dataset:

Datasource: [Telecom Customer Churn](https://www.mavenanalytics.io/blog/maven-churn-challenge)

## File structure:

- [Data Understanding.xlsx](https://github.com/BaoMinhHuynh/Telecom-project/blob/main/Telecom-customer-analyst-project/Data%20Understanding.xlsx) : This file contains complete descriptive information for all data fields in the dataset.
- [Telecom Customer Churn.pdf](https://github.com/BaoMinhHuynh/Telecom-project/blob/main/Telecom-customer-analyst-project/Telecom%20Customer%20Churn.pdf) : This is Tableau report (or [ view the public report on the Tableau website](https://public.tableau.com/views/TelecomCustomerChurn_17669199329280/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))
- [Telecom_customer_churn_analysis.ipynb](https://github.com/BaoMinhHuynh/Telecom-project/blob/main/Telecom-customer-analyst-project/Telecom_customer_churn_analysis.ipynb) : This notebook contains all steps of Clean Data, EDA (or [Preview on web](https://nbviewer.org/github/BaoMinhHuynh/Telecom-project/blob/main/Telecom-customer-analyst-project/Telecom_customer_churn_analysis.ipynb)).

## Technologies - Techniques:

- Pandas
- Matplotlib, Seaborn
- Python

## EDA and Report by Tableau

I will highlight some key points in this project, you can find more detail in [Telecom Customer Churn.pdf](https://github.com/BaoMinhHuynh/Telecom-project/blob/main/Telecom-customer-analyst-project/Data%20Understanding.xlsx)

### Overview

![Overview](/Telecom-customer-analyst-project/assets/Dashboard_2.png)

- **Critical Churn Rate:** Despite strong total revenue ($21.3M), the churn rate is alarmingly high at ~26.5%.

- **Ineffective Promotions:** The majority of revenue comes from customers with "No Offer" ($11.35M). Current promotional offers (especially C, D, and E) are underperforming and generating minimal returns.

- **Core Customer Profile:** The business is driven by married customers (64% of revenue).

### Total Charges Vs Total Revenue

![DB4](/Telecom-customer-analyst-project/assets/Dashboard_4.png)

### Churned Overall

![DB5](/Telecom-customer-analyst-project/assets/Dashboard_5.png)

### Churned by Customer Status and Tenure Category

![DB6](/Telecom-customer-analyst-project/assets/Dashboard_6.png)

### Churned Reason: Competitor made better Offer by Offer

![DB8](/Telecom-customer-analyst-project/assets/Dashboard_8.png)

### Conclusion

![DB14](/Telecom-customer-analyst-project/assets/Dashboard_14.png)

### Recommendations

- Offer Benefits Review
- Continuation of older offers
- Marketing Scheme for Offers
- Reward Programs
- Choice of High-Quality Devices Offered
- Training programs for support staff
