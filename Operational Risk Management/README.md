# Operational Risk Management (ORM) Module

## Goal
The goal of this module is to provide everyone with a comprehensive toolset to **identify, manage, monitor, and report on operational risk across the enterprise**.  
It ensures that risk management activities are standardized, transparent, and actionable, enabling better decision‑making and resilience.

![Operational Risk Brief](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/2%20-%20ORM%20brief.png)

---

## Scope of ORM Modules
The ORM framework covers the following key areas:

- **Risk and Control Assessment (RCA):**  
  Evaluate risks systematically, identify controls, and measure their effectiveness to mitigate exposure.

- **Loss Events:**  
  Capture and analyze incidents that result in financial or operational loss, helping organizations learn and prevent recurrence.

- **Key Risk Indicators (KRIs):**  
  Monitor metrics that act as early warning signals for emerging risks, enabling proactive management.

- **Issues and Actions:**  
  Track identified issues, assign responsibilities, and monitor remediation actions to ensure accountability.

- **Scenario Analysis:**  
  Model potential risk scenarios to understand impact and likelihood, supporting stress testing and contingency planning.

- **External Events:**  
  Incorporate external data (e.g., industry incidents, regulatory changes) to broaden awareness and benchmark against peers.

![Scope of ORM](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/1%20-%20scope.png)

## Object Model
OpenPages Operational Risk Management (ORM) module is built on a flexible **object model** that organizes risk data into structured components.  
Each object represents a specific aspect of operational risk, and together they form a connected framework that enables monitoring, analysis, and reporting.
![Object model](https://github.com/Client-Engineering-Indonesia/workshop-openpages/blob/main/Operational%20Risk%20Management/Assets/7%20-%20Object%20Model.png)
### Key Objects in ORM
- **Risk:**  
  Represents potential events or conditions that could negatively impact the organization. Risks are categorized (e.g., operational, compliance, financial) and linked to controls and indicators.

- **Control:**  
  Actions or mechanisms put in place to mitigate risks. Controls can be assessed for their **operating effectiveness** and tied to specific business processes.

- **Loss Event:**  
  Records incidents where risks materialized, resulting in financial or operational impact. These events provide historical data for analysis and scenario planning.

- **Key Risk Indicator (KRI):**  
  Metrics that serve as early warning signals. KRIs are monitored regularly to detect changes in risk exposure.

- **Issue:**  
  Identified problems or gaps in risk management. Issues are tracked until resolved, ensuring accountability.

- **Action:**  
  Remediation steps linked to issues or risks. Actions are assigned to owners and monitored for completion.

- **Scenario Analysis:**  
  Hypothetical modeling of risk events to understand potential impact and likelihood. Useful for stress testing and forward‑looking risk assessments.

- **External Event:**  
  Captures industry‑wide or regulatory incidents outside the organization that may influence internal risk posture.

---

### Why the Object Model Matters
- Provides a **consistent structure** for capturing and managing risk data.  
- Ensures **traceability** by linking risks to controls, events, and actions.  
- Supports **reporting and analytics** by standardizing how information is stored.  
- Enables **scalability**, allowing organizations to expand risk coverage across multiple business units.  

## Usage
This module is designed for:
- **Risk managers** to assess and monitor risks.  
- **Executives and leadership** to gain visibility into enterprise risk posture.  
- **Operational teams** to manage issues and implement corrective actions.  
- **Auditors and regulators** to review compliance and governance practices.