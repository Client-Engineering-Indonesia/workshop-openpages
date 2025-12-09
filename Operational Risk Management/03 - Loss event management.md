# Loss Event Entry and Loss Event Management

## 1. Introduction
Loss events capture **operational failures** that result in financial, reputational, or compliance impact.  
IBM OpenPages provides workflows to **record, validate, and manage** these events, ensuring that organizations can learn from incidents and strengthen their risk posture.

---

## 2. Recording a Loss Event
Loss events can be submitted through a **dedicated portal** designed for users without OpenPages access.  
This ensures that even employees or external parties who do not have system credentials can still report incidents.

Steps:
- Navigate to: `<Openpages-Url>/openpages/app/jspview/react/lossEventEntry.html`
- Enter details:

  - **Contact Information** (basic info for follow‑up)  
    ![Contact Info](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-1.png)

  - **Loss Event General Info**  
    ![General Info](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-2.png)  
    - Description: ```new loss event submitted by <your initial name>```  
    - Outcome: ```Loss```  
    - What Happened:  
      ```During the recent procurement cycle, the purchasing team selected a vendor without full due diligence and paid in advance. The vendor failed to deliver due to financial difficulties, resulting in an unrecoverable loss of USD 50,000 and delays in project execution. This incident underscores gaps in vendor evaluation, contract safeguards, and contingency planning that require immediate improvement.```

  - **Loss Event Categorization**  
    - Causal Category: ```External```  
    - Causal Subcategory: ```Key supplier and partner exposure```  
    - Risk Category: ```Clients, Products and Business Practices```  
    - Risk Sub‑Category: ```Improper Business or Market Practices```  
    - Risk Example: ```Improper trade / market practices```  
    - Business Line: ```Commercial Banking```  

  - **Loss Event Date:** Use today’s date.  
  - **Involved Entities:**  
    - Primary Caused Entity: ```Global Financial Services/North America```  
    ![Entity Selection](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-4.png)

- Proceed to the **Loss Impacts** section:  
  ![Loss Impact](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-3.png)  
  - Description: (same narrative as above)  
  - Estimated Loss: ```50,000```  
  - Actual Loss: ```50,000```  
  - Effect Category: ```Financial```  

- Continue to **Preview and Submit**.  
  ![Preview and Submit](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-5.png)

> ⚠️ **Important:** After submitting, always **write down your event name** for tracking and follow‑up.

---

## 4. Managing the Event
Once submitted, the event becomes available in the OpenPages dashboard for risk managers to review.

- Navigate back to the **IBM OpenPages Dashboard**.  
- Click the **hamburger menu → Events → Loss Event**.  
- Search for your event name and open it.  
![Search Event](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-3/lab1-3-6.png)

On the loss event page, you can:
- Verify the validity of the event.  
- Update the **status** (e.g., Open, Validated, Closed).  
- Assign or change the **owner**.  
- Configure workflows to ensure proper handling and escalation.  

This step ensures accountability and that corrective actions are initiated.

---

## 5. Reporting & Future Recommendations
Loss event data is valuable not only for immediate remediation but also for long‑term risk management.

- Print individual loss event records for detailed examination or audit purposes.  
- Generate **loss event reports** for management or specific business units.  
- Analyze **trends by category, causal factor, or business unit** to identify systemic issues.  
- Integrate findings with **RCSA (Risk and Control Self Assessment)** to strengthen controls and prevent recurrence.  

---

## 6. Best Practices
- **Record events promptly** to ensure accuracy and completeness.  
- **Link events to root causes** for meaningful analysis and remediation.  
- **Use reports** to identify recurring