# **Information Security**

| Document Title | Patch Management Policy |
| --- | --- |
| Document No. | ISMS-22 |
| Revision No. | 0.3 |
| Effective Date | 12 December 2020 |
| Classification | Confidential |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
| 03 Apr 2021 | 0.3 | - | Content update |
| 31 Mar 2021 | 0.2 | - | Content update |
| 25 Mar 2021 | 0.1 | - | Final version for release |
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

# Contents

- [Revision History](#revision-history)

- [Purpose, Scope And Users](#purpose-scope-and-users)

- [Reference Documents](#reference-documents)

- [Roles and Responsibilities](#roles-and-responsibilities)

- [Records Management](#records-management)

- [Procedures](#procedures)

- [Definitions](#definitions)

- [Severity Rating](#severity-rating)

- [Appendices](#appendices)

# Purpose, Scope And Users

1. This policy defines the guidelines for patch management for Agile Lab Pte Ltd&#39;s (Agile Lab&#39;s) systems and internal information and communications technology (ICT) systems, assets and infrastructure.
2. This procedure relates to the process of implementing security patches or updates of vendor operating systems and application software – ranging from collecting information about security vulnerability to monitoring the results of security update programs, in order to minimize the risk of malicious intrusions.
3. This procedure is not applicable to those computers or equipment which are configured to install security updates automatically or obtained formal exemption for patch installation.
4. The policy applies to all Agile Lab entities and all employees.

# Reference Documents

1. ISMS-01 ISMS Policy

# Roles and Responsibilities

1. System Administrator (SA) is responsible to:
    - Obtain the security alert or vulnerability notification related to the hardware / software / firmware used;
    - Evaluate the severity and urgency of patching;
    - Determine if a the security patch should be applied;
    - Monitor and review the implementation status of a security patch.
2. The Tech Leader (TL)is responsible for approving the security patches proposed by the SA.

# Records Management

| **Record name** | **Storage location** | **Person responsible for storage** | **Controls for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| None |

# Procedures

1. The Technical Leader shall subscribe to the mailing list of vendors or third-party security advisory websites about the technical vulnerability alerts, patch related information, and technology / product end-of-life and end-of-support announcement of the computer hardware and software.
2. These information resources should be updated based on changes in the inventory, or when other new or useful resources are found.
3. After understanding the details of a security vulnerability, the affected hardware / software / network / information systems and the existence of relevant mitigating controls, the Technical Leader shall determine the severity rating of the vulnerability, and the urgency of applying the security patch (or updating program).
4. All analyses and decisions shall be recorded on the Patch Management Worksheet.
5. Upon receiving a technology / product end-of-life or end-of-support announcement, the Technical Leader shall study the details of the announcements, identify the affected hardware, operating systems and application software, and the evaluate the adequacy of existing relevant mitigating controls, if any.
6. Technical Leader shall assess the risk of the continued use of the affected hardware, software or network equipment. S/He shall review and determine the availability of continued support from other vendors, the amount of redundancy, the availability of spare parts, and the existence of skilled technical support staff.
7. If an upgrade is needed, s/he shall prepare the upgrade plan for review with the AVP IT.
8. Following the Change Management Procedure, the Technical Leader shall identify all affected IT components, and submit a Change Request Form for applying the security patch / updating the program in the production environment.
9. Before applying the security patch or update program to the production environment, the Technical Leader shall coordinate with the responsible system / network administrators to test the security update program in a test environment.
10. After applying the security patch or update the program in the test environment, the Technical Leader or a delegated staff shall verify the behaviour and proper operation of the updated systems:

    Operating Systems Software
    - Check the event logs;
    - Check the logs of various products and functions;
    - Verify the operation of the necessary services.

    Application Software
    - Verify operation using the checklist;
    - Execute test transactions to verify its operation;
    - Verify the operation of extracted business applications.

11. The roll back procedure must also be tested, for the sake of problems that are caused by the application of the security update program or by faulty implementation.
12. Patches should be approved before deployment to show that testing and rollback has been performed
13. After applying the security patch / updating the program, Technical Leader shall verify that the change has been applied properly, and potential problems that may arise (caused by the vulnerability) have been avoided.
14. On regular basis, the Technical Leader shall use security vulnerability assessment tools to look for missing patches/ updates on computers.

# Definitions

## Severity Rating

| **Rating**   | **Definition**   |
| --- | --- |
| Critical  | Describes vulnerability that, if exploited, could allow propagation of an Internet worm without user action.  |
| High  | Describes vulnerability that, if exploited, could compromise user data confidentiality, integrity, or availability, as well as compromise the integrity or availability of processing resources.   |
| Medium  | Describes vulnerability for which the possibility of exploitation is significantly lessened by the existing configuration, or by the difficulty of infiltration or exploitation.  |
| Low  | Describes vulnerability that is extremely difficult to exploit or the exploitation of which has minimal impact.  |

**Urgency of Patching**

| **Rating**   | **Definition**   |
| --- | --- |
| 1  | Urgent application - Apply within 1 month  |
| 2  | Applying during the regular course of operation - At least once every 3 to 6 months  |
| 3  | Applying with the service pack -  When installing the next service pack.  |
| 4  | No application  - OS, functionality, product not affected.  |

# Appendices

Patch Management Guidelines
