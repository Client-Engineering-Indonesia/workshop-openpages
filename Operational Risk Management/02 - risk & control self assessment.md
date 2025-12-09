# Risk and Control Self Assessment (RCSA)

## 1. Introduction
Risk and Control Self Assessment (RCSA) is a cornerstone of Operational Risk Management in IBM OpenPages.  
It enables business units to **identify risks**, **evaluate controls**, and **determine residual risk exposure**.  
The process is both **preventive** (spotting weaknesses before they cause issues) and **corrective** (improving controls after incidents).

---

## 2. Preparing for an RCSA
Before starting an assessment, ensure the following steps are completed:
- **Define scope**: Select the business unit, process, or product to be assessed.  
- **Gather documentation**: Collect policies, procedures, and prior assessments for reference.  
- **Assign roles**: Identify risk owners, control owners, and reviewers to ensure accountability.  

---

## 3. Initiating an RCSA in OpenPages
In this use case, let’s say we want to assess risks that exist when an employee or division performs purchasing activities.

- Navigate to **ORM > Risk Assessments**.  
![Navigate to Risk Assessments](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-1.png)

- Click **New Risk Assessment**.  
![New Risk Assessment](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-2.png)

- Enter metadata:  
![Metadata Entry](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-3.png)
  - Assessment name: ```Finance_<your initial name>_RA```  
  - Description: ```2025 Business Impact Analysis - Internal Purchasing Process```  
  - Approach: ```Qualitative```  
  - RCSA Coordinator: ```<your username>```  
  ![Coordinator Field](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-4.png)
  - Reviewer: ```<your username>```  
  - Guidance: ```Enter Detailed Risk Assessment Guidance Here```  
  - Domain: ```Operational```  
  - Primary Business Entity: ```North America```  

- Click **Save**.  
- On the **Finance_<your initial name>_RA** page, click **Edit** on the Owner field and add your username.  
![Owner Assignment](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-5.png)

---

## 4. Identifying Risks
As the owner of the risk assessment, it is your responsibility to add more information as needed.

- Return to your dashboard. Notice that you now have **1 new workflow task** since you assigned yourself as the owner.  
![New Workflow Task](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-6.png)

- Click on the new task.  
- Add additional information to the risk assessment.  
- Scroll down to the **Processes** section and click **Link Process**.  
![Link Process](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-7.png)

- Search for process ```P01``` (related to purchasing and payable) and add it to the risk assessment.  
![Process Search](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-8.png)

Once additional information is added, you can pass the risk assessment to the appropriate persona (e.g., risk manager) by clicking the **Actions** button in the top left corner and selecting **Start Risk Assessment**.  
![Start Risk Assessment](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-9.png)

---

## 5. Performing the Assessment
Now, acting as a risk manager, you will assess the risk by linking related risks to the assessment. You can also add more processes, controls, direct risks, and attachments.

- Scroll down to the **Related Information** section.  
- Click on the **Direct Risks** tab.  
![Direct Risks Tab](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-10.png)

- Click **Link Risks**.  
- Find ```1-P01-RSK-02-01``` and click **Done**.  
![Link Risks](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-11.png)

- Next, click on the **Attachments** tab and add a Risk Assessment Summary file (assuming you have performed an assessment before).  
- Search using the keyword ```risk assessment``` to locate the file.  
![Attachments Tab](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-12.png)

---

## 8. Reviewing and Approving
- Submit the assessment for **manager review**.  
  - Click the **Actions** button and choose **Evaluation Complete – High Risk**, then click **Continue**.  
  - Notice that the status now changes to **Awaiting Approval**. You can configure the workflow to specify who needs to approve the assessment.  
![Awaiting Approval](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-13.png)

- For now, go to the **Actions** button again and approve and complete your assessment.  
![Approve Assessment](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-15.png)

- Discuss with your instructor about the report generated by the system.

---

## 11. Reporting
Once the risk assessment is complete, you can generate a report for senior management.

- Return to the **Dashboard**.  
- From the hamburger menu, choose **Assessment → Risk Assessments**.  
- Click on the ```1-Finance_P&P_RA``` row. This example contains extensive information, allowing you to see how a detailed report looks.  
![Select Risk Assessment](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-16.png)

- On the **1-Finance_P&P_RA** page, click **Print Risk Assessment Summary** to generate the report.  
- You can now export or print the report as a PDF.  
![Print Report](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/lab1-2/lab1-2-17.png)

---

## 12. Best Practices
- Involve **process owners** for accurate risk identification.  
- Use **historical loss event data** to calibrate ratings.  
- Keep documentation **clear, consistent, and evidence‑based**.  
- Align RCSA outcomes with **regulatory requirements** (e.g., Basel II/III, SOX).  
- Review assessments periodically to ensure risks and controls remain relevant.

---

## 13. Summary
The Risk and Control Self Assessment (RCSA) process in IBM OpenPages provides a structured way to evaluate operational risks and the effectiveness of controls.  

By following the steps outlined:
- **Preparation** ensures scope, documentation, and roles are defined.  
- **Initiation** sets up the risk assessment with metadata and ownership.  
- **Identification** links relevant processes and assigns tasks.  
- **Assessment** connects risks, controls, and supporting documents.  
- **Review and Approval** formalizes the evaluation and ensures governance.  
- **Reporting** generates clear outputs for management and regulatory compliance.  

Together, these activities create a **comprehensive risk profile** that supports proactive management, accountability, and informed decision‑making across the enterprise.