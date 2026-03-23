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

#  Data Architecture & Tools

## Data Source:
The dataset used for this analysis is available here:  
[Curacel Revenue Dataset](https://docs.google.com/spreadsheets/d/1O4AN_i_aN00606H8ZvzI0zClW7pU-cgw/edit?usp=sharing&ouid=105443892095484323960&rtpof=true&sd=true)

The dataset contains transaction-level data including pricing, discounts, billing status, customer segmentation, and usage metrics, which were used to analyze revenue leakage and customer behavior.

---

## Tools and Technologies Used:

- **Microsoft Excel** → Initial data exploration and validation  
- **Power BI** → Primary tool for data analysis, modeling, and dashboard development  
- **Power Query** → Data cleaning, transformation, and handling missing/invalid values  
- **DAX (Data Analysis Expressions)** → Creation of calculated columns and measures (e.g., revenue leakage, discount rate, KPIs)  
- **Data Modeling** → Relationship building between tables (e.g., Date table and transaction data)  
- **PowerPoint** → Dashboard wireframing and executive storytelling  
- **GitHub** → Documentation, version control, and portfolio presentation
  
---

# Executive Dashboards & Analysis

This section highlights the key dashboards developed to analyze revenue performance, identify leakage drivers, and provide actionable insights to improve profitability at Curacel.

---

## 1. Revenue Leakage Dashboard

**Objective:** Identify where revenue is being lost and quantify the overall impact on business performance.

**Key Insights:**

- Total Expected Revenue: £556K  
- Total Actual Revenue: £528K  
- Total Revenue Leakage: £14K  
- Revenue Leakage Rate: 2% of expected revenue  
- Customers with Leakage: 475 customers affected  

**Leakage by Product / Service:**

- Service D contributes the highest revenue leakage  
- Leakage is concentrated in specific services, indicating process inefficiencies  

**Billing Error Impact:**

- 100% of revenue leakage is linked to billing errors  
- No significant evidence that discounts are driving revenue loss  

**Takeaway:**  
Revenue leakage is primarily driven by internal billing inefficiencies rather than pricing strategy, indicating an operational issue that affects multiple services.

---

## 2. Discount Effectiveness Dashboard

**Objective:** Evaluate how discount strategies impact revenue and identify potential over-discounting.

**Key Insights:**

- Total Discount Given: £28K  
- Average Discount Rate: 5%  

**Discount Trend:**

- Discount usage increased in 2023, indicating greater reliance on promotional pricing  

**Discount by Product / Service:**

- Service D receives the highest discounts  
- Discount allocation is concentrated across specific services  

**Discount vs Revenue Relationship:**

- Higher discounts do not consistently generate higher revenue  
- Indicates diminishing returns on excessive discounting  

**Takeaway:**  
Discounts are not the primary driver of revenue leakage; however, excessive discounting may reduce profitability without significantly increasing revenue.

---

## 3. Customer Segmentation Dashboard

**Objective:** Analyze customer behavior to identify high-value segments, leakage exposure, and upselling opportunities.

**Key Insights:**

- Enterprise and SMB segments generate the highest revenue  
- Revenue leakage is also concentrated within these high-value segments  

**Usage vs Revenue Analysis:**

- Large Enterprise customers show high usage but relatively low revenue contribution  
- Indicates clear under-monetization  

**Customer Value Distribution:**

- Enterprise customers represent the most valuable segment  
- Small Business segment contributes lower revenue and usage  

**Takeaway:**  
While high-value segments drive revenue, under-monetized customers—particularly Large Enterprise—present significant opportunities for upselling and revenue optimization.

---
This toolset enabled efficient data transformation, robust analytical modeling, and the development of interactive dashboards to uncover revenue leakage patterns, customer behavior insights, and opportunities for revenue optimization.

# Strategic Recommendations

This section outlines actionable strategies to address revenue leakage, improve operational efficiency, and enhance overall revenue performance at Curacel.

---

## 1. Billing Process Optimization

**Objective:** Eliminate revenue leakage caused by billing inefficiencies.

**Recommendations:**

- Implement automated billing validation checks to detect discrepancies before invoicing  
- Introduce real-time billing error alerts to flag anomalies instantly  
- Conduct periodic (monthly/quarterly) revenue reconciliation audits  
- Reduce manual billing interventions to minimize human error  

**Expected Impact:**  
Improved billing accuracy, reduced revenue leakage, and stronger financial control.

---

## 2. Revenue Protection & Monitoring

**Objective:** Prevent revenue loss through proactive monitoring and control systems.

**Recommendations:**

- Develop automated dashboards to track revenue leakage in real time  
- Implement anomaly detection systems for unusual pricing or billing patterns  
- Establish internal KPIs for revenue accuracy and leakage thresholds  
- Create alerts for high-risk transactions and billing inconsistencies  

**Expected Impact:**  
Early detection of issues, faster resolution, and prevention of recurring revenue losses.

---

## 3. Pricing & Monetization Optimization

**Objective:** Improve revenue capture from high-usage customer segments.

**Recommendations:**

- Review pricing structure for Large Enterprise customers to ensure alignment with usage  
- Introduce tiered or usage-based pricing models for better revenue scalability  
- Identify and target under-monetized customers for upselling opportunities  
- Align pricing with value delivered to maximize revenue per customer  

**Expected Impact:**  
Increased revenue per customer and improved monetization of high-value segments.

---

## 4. Operational Standardization

**Objective:** Address inconsistencies across services contributing to leakage.

**Recommendations:**

- Audit Service D billing workflows to identify process gaps  
- Standardize billing logic across all products and services  
- Implement centralized billing rules to ensure consistency  
- Establish clear operational guidelines for pricing and invoicing  

**Expected Impact:**  
Reduced process variability, improved operational efficiency, and consistent revenue capture.

---

## 5. Customer Value Optimization

**Objective:** Maximize customer lifetime value and reduce underperformance.

**Recommendations:**

- Segment customers based on usage and revenue contribution  
- Design targeted upselling strategies for high-usage, low-revenue customers  
- Monitor customer behavior to identify early signs of under-monetization  
- Strengthen engagement strategies for high-value customer segments  

**Expected Impact:**  
Higher customer lifetime value, improved revenue growth, and better customer segmentation strategy.

---

## Strategic Outcome

The implementation of the recommended strategies is expected to significantly improve Curacel’s revenue performance and operational efficiency.

By addressing billing inefficiencies and strengthening revenue controls, the company can:

- Recover approximately £14K in lost revenue annually  
- Improve billing accuracy and reduce revenue leakage  
- Enhance visibility into revenue performance across products and customer segments  
- Increase revenue per customer through better monetization strategies  
- Strengthen overall financial stability without increasing customer acquisition costs  

These outcomes position Curacel to achieve more sustainable and predictable revenue growth.

---

## Key Strategic Insight

The analysis reveals that revenue leakage at Curacel is not driven by pricing or discount strategies, but by internal operational inefficiencies—specifically billing errors.

Additionally, certain high-usage customer segments, particularly Large Enterprise, are under-monetized, indicating missed opportunities for revenue optimization.

This highlights a critical opportunity for Curacel to improve revenue performance by focusing on:

- Strengthening billing systems  
- Aligning pricing with customer usage  
- Improving monetization of high-value segments  

---

## Conclusion

This analysis demonstrates that revenue leakage at Curacel is primarily an operational issue rather than a market or pricing problem.

While the leakage rate of 2% may appear small, its impact on profitability is significant when scaled across the business.

By implementing data-driven improvements in billing processes, pricing strategies, and customer monetization, Curacel can:

- Eliminate preventable revenue loss  
- Improve operational efficiency  
- Increase profitability without additional sales effort  

Ultimately, addressing revenue leakage enables Curacel to maximize the value of its existing customer base while building a stronger foundation for long-term growth.


## 👤 Author | Connect With Me

**Akinlade Opeyemi Mary**  
📊 Data Analyst | Business Intelligence | Credit Risk Analysis  

🔗 **LinkedIn:** [Akinlade Opeyemi Mary](https://www.linkedin.com/in/opeyemiakinlademary)  
📧 **Email:** akinladeopeyemi36@gmail.com
