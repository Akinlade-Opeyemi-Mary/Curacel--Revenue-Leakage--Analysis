# CURACEL REVENUE LEAKAGE ANLYSIS 

# Executive Summary

Curacel is a subscription-based financial technology (SaaS) company providing insurance automation, business intelligence, and fraud detection solutions. Despite steady customer activity and consistent platform usage, the company identified a gap between expected revenue and actual revenue realized.

This analysis was conducted to identify where revenue leakage was occurring, uncover the root causes of these losses, and recommend data-driven strategies to improve revenue accuracy and overall profitability.

Using Power BI, DAX, and data modeling techniques, multiple dashboards were developed to analyze revenue leakage trends, billing errors, discount effectiveness, and customer monetization behavior.

The findings revealed that revenue leakage was primarily driven by **billing errors**, with no significant evidence linking discounts to revenue loss. Additionally, certain customer segments—particularly Large Enterprise—were identified as under-monetized, showing high product usage but relatively low revenue contribution.

Strategic recommendations were proposed to strengthen billing processes, implement automated validation systems, optimize pricing structures, and improve revenue capture across high-usage customer segments.

By addressing these operational inefficiencies, Curacel can recover lost revenue, improve financial accuracy, and enhance long-term business performance without increasing customer acquisition costs.

# Company Overview

Curacel is a subscription-based financial technology (SaaS) company that provides digital solutions to streamline insurance operations and improve decision-making.

The company’s core offerings include:

- Insurance automation software  
- Business intelligence and analytics tools  
- Fraud detection and risk management solutions  

Curacel enables organizations to manage customer data, process claims efficiently, and gain actionable insights through data-driven platforms.

Revenue is generated through multiple streams, including:

- Monthly subscription plans  
- Annual subscription packages  
- Usage-based pricing models  
- Enterprise licensing agreements  

As a SaaS business, Curacel relies on accurate billing, effective pricing strategies, and optimal customer utilization to maximize revenue performance and sustain growth.

# Business Challenges

Despite consistent customer activity and steady platform usage, Curacel faced challenges in accurately capturing its full revenue potential.

The primary challenge identified was a gap between expected revenue and actual revenue realized, indicating the presence of revenue leakage within the system.

Several key business issues contributed to this challenge:

- **Billing Inefficiencies:** Errors in billing processes led to undercharging or missed revenue capture.  
- **Lack of Revenue Visibility:** Limited insight into where and why revenue losses were occurring made it difficult to take corrective action.  
- **Under-Monetized Customer Segments:** Certain customers demonstrated high platform usage but contributed relatively low revenue.  
- **Operational Inconsistencies:** Variations in pricing and billing workflows across services created potential revenue gaps.  

These challenges highlighted the need for a structured, data-driven approach to identify leakage sources, improve billing accuracy, and optimize revenue performance across customer segments.

## 3. Data Architecture & Tools

### Data Source

The dataset used for this analysis is available here:

👉 [Download here](https://docs.google.com/spreadsheets/d/1O4AN_i_aN00606H8ZvzI0zClW7pU-cgw/edit?usp=sharing&ouid=105443892095484323960&rtpof=true&sd=true)

This consolidated dataset includes Public Performance Measure (PPM) data, railway journey records, delay minutes by operator and cause, and cancellation statistics. These datasets were integrated to provide a comprehensive view of rail reliability from both operational and passenger perspectives.

---

### Tools and Technologies Used

- **Microsoft Excel** → Initial data extraction, cleaning, and validation  
- **Power BI** → Primary tool for data modelling, dashboard development, and visual analytics  
- **Power Query** → Data transformation, cleaning, and feature engineering  
- **DAX (Data Analysis Expressions)** → Creation of calculated measures and KPIs (PPM %, On-Time %, Delay Minutes, Cancellation Rate, Infrastructure Delay Share)  
- **Data Modelling (Star Schema)** → Structuring fact tables and a central date dimension for consistent analysis  
- **Power BI Visuals** → Interactive dashboards for reliability, root cause analysis, and impact assessment  
- **PowerPoint / Wireframing** → Dashboard design and executive storytelling structure  
- **GitHub** → Documentation, version control, and portfolio presentation  

---

This toolset enabled effective data integration, performance analysis, and the development of actionable insights to support decision-making in improving UK rail network reliability.

---

This toolset enabled effective data integration, performance analysis, and the development of actionable insights to support decision-making in improving UK rail network reliability.
