# fraud-data-analysis

**Objective**
  The goal of this analysis is to understand patterns and trends in transaction and fraud data, identify high-risk behaviors, and develop strategies to minimize financial      losses.

**Approach**
  **Data Exploration:** Performed a detailed review of transaction data to uncover potential anomalies and risk factors.
  **Trend Analysis:** Investigated hourly, daily, and monthly transaction trends to pinpoint high-risk periods.
  **Rule-Based Strategies:** Developed fraud detection rules based on historical patterns to flag risky transactions.
  **Projections:** Used simple a forecasting method to anticipate future fraud trends and enhance preventive strategies.

**Interesting Findings**
  
  **Transaction Amount Distribution:**
  - Most transactions are concentrated in lower ranges, but significant outliers (high-value transactions) indicate potential risks.    
  - High-value transactions skew the distribution, emphasizing the need for enhanced monitoring of such cases.
    <img width="389" alt="image" src="https://github.com/user-attachments/assets/dfdb0d5f-9619-45bc-95fb-7f854b245413" />
    <img width="390" alt="image" src="https://github.com/user-attachments/assets/54f89dcb-61d6-4c06-b314-253cae4053d2" />

  **Month-over-Month Key Metrics Performance:**
  - November 2023 experienced both increased sales and a slight rise in fraud rates. This aligns with high transaction volumes during peak activity periods. December 2023        saw a decline in sales but a dramatic reduction in fraud rates, coupled with a recovery in approval rates. This may indicate improved control mechanisms during November      2023.
    <img width="902" alt="image" src="https://github.com/user-attachments/assets/86cc42e3-d85b-4b07-80cb-f4a90d26a5a7" />

  **Temporal Insights:**
  - Specific hours of the day exhibit higher transaction volumes, correlating with increased fraud activity.
  - Identified the best and worst hours:
    - Best Hour: 14:00 (2 PM)
      Approval rate peaks (~95%) during this hour, indicating efficient transaction processing. Fraud remains relatively low compared to other high-transaction hours like         10:00 or 20:00. Although not the highest, the transaction frequency is still significant, ensuring solid revenue generation.
    - Worst Hour: 10:00 (10 AM)
      Fraud rate peaks at 20%, indicating a substantial risk. Approval rate is around 85%, lower than during better hours like 14:00. The Transaction Frequency is High,           which amplifies the impact of fraud, as a larger number of transactions are at risk. Despite high transaction activity, the high fraud rate and moderate approval            efficiency make this hour the least favorable.
    <img width="896" alt="image" src="https://github.com/user-attachments/assets/b5da9520-56ee-4854-8ea0-5052d04aae76" />

  **Merchant Insights:**
  - Identified Merchants with highest losses over months
    <img width="436" alt="image" src="https://github.com/user-attachments/assets/55c8fbf0-dcba-4661-8c26-33dd0a7612e5" />
  - Identified Top 10 Merchants with highest losses in Nov-23
    <img width="445" alt="image" src="https://github.com/user-attachments/assets/99bb35f3-f4b2-4a9c-ba4b-b678808c8840" />



  

