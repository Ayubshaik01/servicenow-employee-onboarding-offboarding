<div align="center">

| <img src="https://smartinternz.com/images/company_logos/thumbs/1589433559SmartBridge_Logo.png" width="160" alt="SmartBridge"> | <img src="https://www.myskillwallet.ai/skillwalletheaderlogo.png" width="160" alt="SkillWallet"> |
|:--|--:|

---

*Phase 5 -- Deployment, Documentation & Final Presentation*

## System Functionality & Capabilities Overview

</div>

| **Date** | 2026-07-01 |
|---|---|
| **Project Name** | Automated Employee Onboarding & Offboarding System |
| **Author** | AYUB HUSSAIN SHAIK |
| **Organization** | SKILLWALLET INTERNSHIP |
| **Document** | Functional Overview |

---
## Executive Summary

The Automated Employee Onboarding & Offboarding System optimizes employee lifecycle management through the ServiceNow ecosystem. The solution eliminates manual coordination with intelligent workflows that orchestrate request submission, authorization, departmental task distribution, and lifecycle tracking.

The implementation integrates **Service Portal request forms, automated workflow orchestration, role-based access restrictions, and centralized lifecycle tracking** to enable a secure and efficient process.

---

## System Capabilities

### Capability 1: Request Origination

- Users originate lifecycle requests via **Service Portal interface**
- Request forms capture required employee information using catalog field variables
- Submitted requests automatically generate unique tracking identifiers

---

### Capability 2: Workflow Authorization

- Submitted requests automatically transmit to **designated manager** for authorization
- Authorization requirement must be fulfilled before process continuation
- Manager decisions determine subsequent workflow progression

---

### Capability 3: Task Distribution Across Departments

Following authorization, the system automatically generates tasks for relevant departments:

- **HR Personnel** â€“ Employee documentation and lifecycle procedure management
- **IT Personnel** â€“ System access provisioning or revocation and user account management
- **Facilities Personnel** â€“ Physical asset allocation or recovery and workspace management
- **Security Personnel** â€“ Physical access permission administration

Each department receives task assignments aligned with their operational scope.

---

### Capability 4: Centralized Request Information Tracking

- All request details store in **Employee Lifecycle custom table**
- Table maintains:
  - Employee profile information
  - Request type classification
  - Authorization status
  - Task completion tracking
  - Request resolution status

This infrastructure enables centralized request lifecycle visibility.

---

### Capability 5: Conditional Form Field Display

- **UI Policies** conditionally render fields based on request type selection
- Example:
  - If **Request Type = Onboarding â†’ Commencement Date appears**
  - If **Request Type = Offboarding â†’ Departure Date appears**

This approach optimizes form usability and minimizes input errors.

---

### Capability 6: Notifications & SLA Performance Tracking

- **Automated email messaging** informs stakeholders during workflow transitions
- **Service Level Agreements (SLAs)** monitor task completion timelines
- Reports enable progress monitoring and management visibility

---

## Projected Business Impact

- Employee lifecycle processes operate with full automation
- Onboarding and offboarding cycle times accelerate
- Interdepartmental collaboration and coordination improve
- Employee information handling maintains security and role-based restrictions

---



