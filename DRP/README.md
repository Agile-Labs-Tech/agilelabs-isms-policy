<div align="center"> **Internal** </div>

# **Disaster Recovery Plan**

| Document Title | Disaster Recovery Plan |
| --- | --- |
| Organization Name | Agile Lab |
| Document No. | DRP |
| Revision No. | 0.1 |
| Effective Date | 12 December 2020 |
| Classification | Internal |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
| 08 Apr 2021 | 0.1 | - | Content update |
| 12 Dec 2020 | 0.0 | - | Initial version for release |

### **Prepared By:**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| Wayne Tng | Technical Leader | 12 Dec 2020 |

### **Reviewed By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| SzeTho ChangSheng | Information Security Manager | 12 Dec 2020 |

### **Approved By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| Jack Cam | Chief Security Officer | 12 Dec 2020 |

## Contents

- [Revision History](#revision-history)

- [Purpose, Scope And Users](#purpose-scope-and-users)

- [Reference Documents](#reference-documents)

- [Validity And Document Management](#validity-and-document-management)

- [Plan Objectives](#plan-objectives)

- [Employee Contact Information](#employee-contact-information)

- [Vendor Contact Information](#vendor-contact-information)

- [Plan Documentation Storage](#plan-documentation-storage)

- [Backup Strategy](#backup-strategy)

- [Risk Management](#risk-management)

- [Alert, escalation and plan invocation](#alert-escalation-and-plan-invocation)

- [Financial and Legal Issues](#financial-and-legal-issues)

- [DRP Exercising](#drp-exercising)

- [Appendices](#appendices)

## Purpose, Scope And Users

- The Scope of this plan covers Agile Lab Pte Ltd.
- The purpose of the disaster recovery program is to develop, test and document a well-structured and easily understood plan which will help the company recover as quickly and effectively as possible from an unforeseen disaster or emergency which interrupts information systems and business operations
- Users of this document are all employees of Agile Lab Pte Ltd (Agile Lab).

## Reference Documents

- ISO/IEC 27001 standard, clause 10.1
- Information Security Policy
- Internal audit procedure
- Incident management procedure

## Validity And Document Management

- This document is valid as of the date stated on the cover of this document.
- The owner of this document is Information Security Manager (ISM), who must check and, if necessary, update the document at least once a year.
- When evaluating the effectiveness and adequacy of this document, the following criteria need to be considered:

    1. number of initiated corrective actions
    2. number of incomplete corrective actions
    3. number of corrective actions taken without having been recorded in a designated form

## Plan Objectives

### Objectives

The principal objective of the disaster recovery program is to develop, test and document a well-structured and easily understood plan which will help the company recover as quickly and effectively as possible from an unforeseen disaster or emergency which interrupts information systems and business operations..

### Primary Objectives

- The need to ensure that all employees fully understand their duties in implementing such a plan
- The need to ensure that proposed contingency arrangements are cost-effective
- Disaster recovery capabilities as applicable to key customers, vendors and others

### Plans Assumptions

The following assumptions were used while creating this plan:

- An event has occurred that affects normal business operations
- There is limited or no access to the affected facility.
- Documents and equipment within the facility are in accessible
- Qualified personnel are available to continue operations

## Employee Contact Information

[Employee Contacts](https://docs.google.com/spreadsheets/d/1kRf8DYuAAOWTwffl7Wy43KO88n8ZrmcA7J_3jzZc834)

## Vendor Contact Information

[External Contacts](https://docs.google.com/spreadsheets/d/11b1ZbclzYwSC3ky8zxoWoIfQcWztTNrF6DWMxHJY3LU/edit#gid=967295095)

## Plan Documentation Storage

Copies of this plan and hard copies will be stored in secure locations to be defined by the company. Each member of senior management will be issued a softcopy in their email and a hard copy of this plan to be filed at home. Each member of the Disaster Recovery Team and the Business Recovery Team will be issued a softcopy and hard copy of this plan. A master protected softcopy will be stored on specific resources established for this purpose.

## Backup Strategy

This strategy entails the maintenance of all intellectual property and data which will enable redeployment of the affected project or system.

| **BACKUP STRATEGY** | |
| --- | --- |
| Source Code | On Gitlab repository and clone to AWS Code-commit on a daily basis |
| Database | Backup to private S3 on a daily basis |
| Server | Snapshot of Volumes |

## Risk Management

| Potential Disaster | List of Threats | Likelyhood | Impact Rating | Brief Description Of Potential Remedial Actions |
| --- | --- | --- | --- | --- |
| Natural/Man Made Disasters | Fire | 2 | 4 | Fire - Fire and smoke detectors on all corridor. Fire extinguisher in office.Flood, unihabitable facility, interruption of power supply - Telework.Disruption of internet - 1) Use mobile data 2) Satellite Internet (VSAT)
| | Flood | 2 | 4 |
| | Uninhabitable Facility | 2 | 4 |
| | Disruption of internet | 2 | 4 |
| | Interruption of power supply | 2 | 4 |
| Terrorism/War/Civil-War | Fire | 1 | 4 | Fire - Fire and smoke detectors on all corridor. Fire extinguisher in office.Flood, uninhabitable facility, interruption of power supply - Telework.Disruption of internet - 1) Use mobile data 2) Satellite Internet (VSAT) |
| | Flood | 1 | 4 |
| | Uninhabitable Facility | 1 | 4 |
| | Disruption of internet | 1 | 4 |
| | Interruption of power supply | 1 | 4 |
| Cyber Attack | Distributed denial-of-service (DDoS) attack | 3 | 5 | Hacking/Virus, Distributed denial-of-service (DDoS) attack, Competitor espionage, Destruction of records, Falsification of records , loss of customer data, - Revert older backup and deploy <br/> Cyber attacked, information leak, internal espionage, disclosure of password, Phishing, Eavesdropping/Surveillance - Password change workflow |
| | Loss of customer data privacy/confidentiality | 3 | 5 |
| | Falsification of records | 3 | 5 |
| | Hacking/Virus/Malware/Ransomware | 3 | 5 |
| | Phishing | 3 | 5 |
| | Destruction of records | 3 | 5 |
| | Disclosure of passwords | 3 | 5 |
| | Eavesdropping/Surveillance | 3 | 5 |
| Human Related | Theft of proprietary information or intellectual property | 2 | 4 | Information leak, internal espionage, destruction/ disclosure of password, - Password change workflow Loss of key personal - Keyman replacement Labour Strike - HR nego or replacement |
| | Former employee misconduct involving info systems | 2 | 4 |
| | Business partner(s) misconduct involving info systems | 2 | 4 |
| | Competitor espionage | 2 | 4 |
| | Internal espionage | 2 | 4 |
| | Accidental change of information system data | 2 | 4 |
| | Breach of contractual relations | 2 | 4 |
| | Destruction of records | 2 | 4 |
| | Disclosure of passwords | 2 | 4 |
| | Embezzlement | 2 | 4 |
| | Leakage/disclosure of information | 2 | 4 |
| | Loss of Service Provider | 2 | 4 |
| | Loss of Keyman | 2 | 4 |
| | Labour Strike | 2 | 4 |
| System Related | Critical Application bugs/error | 2 | 4 | Critical Application bugs/error Damage incurred during penetration testing Equipment Failure - Revert older backup and deploy |
| | Damage incurred during penetration testing | 2 | 4 |
| | Equipment Failure | 2 | 4 |

## Alert, escalation and plan invocation

### Activation of Emergency Response Team

When an incident occurs the Emergency Response Team (ERT) must be activated. The ERT will then decide the extent to which the DRP must be invoked. All employees must be issued a Quick Reference card containing ERT contact details to be used in the event of a disaster.

**Responsibilities of the ERT are to:**

  - Respond immediately to a potential disaster and call emergency services;
  - Assess the extent of the disaster and its impact on the business, data center,etc.;
  - Decide which elements of the DR Plan should be activated;
  - Establish and manage disaster recovery team to maintain vital services and return to normal operation;
  - Ensure employees are notified and allocate responsibilities and activities as required

### Disaster Recovery Team

The team will be contacted and assembled by the ERT.

**The team&#39;s responsibilities include:**

  - Establish facilities for an emergency level of service within 2.0 business hours;
  - Restore key services within 4.0 business hours of the incident;
  - Recover to business as usual within 8.0 to 24.0 hours after the incident;
  - Coordinate activities with disaster recovery team, first responders, etc.
  - Report to the emergency response team

### Emergency Alert, Escalation and DRP Activation

This policy and procedure has been established to ensure that in the event of a disaster or crisis, personnel will have a clear understanding of who should be contacted. Procedures have been addressed to ensure that communications can be quickly established while activating disaster recovery.

The DR plan will rely principally on key members of management and staff who will provide the technical and management skills necessary to achieve a smooth technology and business recovery. Suppliers of critical goods and services will continue to support recovery of business operations as the company returns to normal operating mode.

## Financial and Legal Issues
### Financial Assessment

The emergency response team shall prepare an initial assessment of the impact of the incident on the financial affairs of the company.

**The assessment should include:**

  - Loss of financial documents
  - Loss of revenue
  - Theft of check books, credit cards, etc.
  - Loss of cash

### Financial Requirements

The immediate financial needs of the company must be addressed.

**These can include:**

  - Cash flow position
  - Temporary borrowing capability
  - Upcoming payments for taxes, payroll taxes, Social Security, etc.
  - Availability of company credit cards to pay for supplies and services required post- disaster

### Legal Actions

The company legal department and ERT will jointly review the aftermath of the incident and decide whether there may be legal actions resulting from the event; in particular, the possibility of claims by or against the company for regulatory violations, etc.

# DRP Exercising

Disaster recovery plan exercises are an essential part of the plan development process. In a DRP exercise no one passes or fails; everyone who participates learns from exercises – what needs to be improved, and how the improvements can be implemented. Plan exercising ensures that emergency teams are familiar with their assignments and, more importantly, are confident in their capabilities.

Successful DR plans launch into action smoothly and effectively when they are needed. This will only happen if everyone with a role to play in the plan has rehearsed the role one or more times. The plan should also be validated by simulating the circumstances within which it has to work and seeing what happens

# Appendices

# Appendix A - Technology Disaster Recovery Plan
[Technology Disaster Recovery Plan](https://gitlab.com/agilelab/guides/-/tree/master/guidelines/disaster-recovery)

<div align="center"> **Internal** </div>
