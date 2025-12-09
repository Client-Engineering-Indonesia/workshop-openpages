# Understanding the ORM Module – Dashboard Overview

## 1. Introduction
The Operational Risk Management (ORM) module in IBM OpenPages provides a centralized dashboard to monitor risks, controls, and events.  
This dashboard acts as the **command center** for risk professionals, offering a consolidated view of the organization’s risk posture.  
By using it, teams can quickly identify emerging issues, track remediation progress, and ensure compliance with governance standards.

---

## 2. Accessing the Dashboard
- Log in to **IBM OpenPages** using your enterprise credentials.  
- Navigate to **Home**, where the dashboard serves as your landing page.  

> 💡 *Tip:* The dashboard is customizable, so each user can tailor it to their role and responsibilities.

---

## 3. Dashboard Components
To make the dashboard meaningful, you need to add panels that display relevant information.  
Start by selecting the **configure menu** on the right side of the screen.

![Configure Dashboard](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-1.png)

Then click on the **New Panel** button to begin adding components.

---

### Add My Tasks to Dashboard
This panel helps you stay on top of your assigned workflow tasks, ensuring accountability and timely action.

![My Tasks Panel](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-2.png)
- Type: ```My Tasks```
- Label: ```My Workflow Tasks```

Click on **Done** to save the panel.

---

### Add Risk Breakdown of Your Company
This chart provides a **visual distribution of risks** by category, helping you identify which areas carry the highest exposure.

![Risk Breakdown Config](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-3.png)  
![Risk Breakdown Chart](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-4.png)

Click on **New Panel** again and fill the fields with:
- Panel Type: ```Chart```
- Label: ```Risk Breakdown```
- Object Type: ```Risk```
- Filter: *(leave blank for all risks)*
- Chart Type: ```Bar```
- Chart Data Field: ```Risk Category```
- Method Type: ```Count```
- Sort Direction: ```Field definition order```
- Chart Display Configuration: ```Show top 10```

---

### Add Controls by Operating Effectiveness
This panel shows how effective your controls are, categorized by their operating effectiveness.  
It helps risk managers quickly spot weak controls that may need remediation.

![Controls Config](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-5.png)  
![Controls Chart](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-6.png)

Click on **New Panel** again and fill the fields with:
- Panel Type: ```Chart```
- Label: ```Controls by OE```
- Object Type: ```Control```
- Filter: ```Business Control```
- Chart Type: ```Pie```
- Chart Data Field: ```Operating Effectiveness```
- Method Type: ```Count```
- Sort Direction: ```Field definition order```
- Chart Display Configuration: ```Show top 10```

---

## 4. Best Practices
- **Review the dashboard daily** to stay updated on tasks, risks, and controls.  
- **Use filters** to narrow down to high‑impact risks or specific business units.  
- **Export charts** for management reporting and presentations.  
- **Customize panels** to reflect your role—risk managers may focus on controls, while executives may prefer risk trends.  
- **Keep it simple:** Avoid cluttering the dashboard with too many panels; focus on the most critical insights.

---

## 5. Summary
The ORM dashboard is a **powerful visualization tool** that transforms raw risk data into actionable insights.  
By configuring panels such as *My Tasks*, *Risk Breakdown*, and *Controls by Operating Effectiveness*, you create a tailored workspace that supports proactive risk management and informed decision‑making.

---
# Understanding the ORM Module – Business Entity Review

## 1. Introduction
The **Business Entity Review** feature in IBM OpenPages allows risk professionals to drill down into specific organizational units.  
By reviewing entities such as *North America*, you gain visibility into localized risks, controls, and events, which helps connect enterprise‑level risk posture with regional realities.

---

## 2. Navigating to Business Entity
To begin the review:

1. Navigate to the **hamburger menu** on the left.  
2. Choose **Organization → Business Entity**.  
3. In the search bar, type **North America** to locate the relevant business entity within your organization.

![Business Entity Search](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-7.png)  

---

## 3. Selecting the Entity
Click on the **North America record** under *Global Financial Services*.  
This opens the entity overview, which consolidates risk data, controls, and recent events for that region.
![Business Entity Search Result](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-8.png)

---

## 4. Reviewing the Overview
The entity overview provides a **snapshot of operational risk** for the selected business unit.  
Here you can see:

- **Risk rating profile:** A summary of risks categorized by type and severity.  
- **Control effectiveness:** How well controls are performing in mitigating risks.  
- **Loss events:** Incidents that have occurred recently, captured and summarized for analysis.  
- **Key indicators:** Metrics that highlight trends or emerging issues.  

This overview helps you quickly identify areas of concern and prioritize follow‑up actions.
![North America Entity](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-9.png)

![Entity Overview](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-1/lab1-1-10.png)

---

## 5. Discussion and Takeaways
At this stage, pause and reflect on the insights:

- What does the **risk distribution** tell us about the North America entity?  
- Are there **recurring loss events** that point to systemic issues?  
- Which **controls** appear strong, and which may need remediation?  
- How do these findings align with the **enterprise‑wide risk posture**?

> 💡 *Tip:* Use this review as a starting point for deeper analysis. You can drill into specific risks, controls, or events to uncover root causes and design corrective actions.

---

## 6. Benefits of Business Entity Review
- Provides **localized visibility** into risks and controls.  
- Helps connect **regional insights** with enterprise‑level reporting.  
- Supports **data‑driven decision making** for risk managers and executives.  
- Enables proactive identification of **emerging risks** before they escalate.  

---

## Summary
The Business Entity Review is a **powerful tool for contextualizing operational risk**.  
By focusing on a specific unit like *North America*, you gain actionable insights into recent loss events, control effectiveness, and overall risk posture—helping ensure that risk management is both **comprehensive and targeted**.