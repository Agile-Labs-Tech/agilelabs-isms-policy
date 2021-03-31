# **Information Security**

| Document Title | Privileged Access Management Policy |
| --- | --- |
| Document No. | ISMS-21 |
| Revision No. | 0.2 |
| Effective Date | 12 December 2020 |
| Classification | Confidential |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
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

- [Appendices](#appendices)

# Purpose, Scope And Users

1. This policy defines the guidelines to manage privileged access accounts for Agile Lab Pte Ltd&#39;s (Agile Lab&#39;s) systems and internal information and communications technology (ICT) systems, assets and infrastructure.
2. This procedure is established to ensure that critical information processing and data storage facilities (i.e. information systems, networks and applications) belonging to Agile Lab are monitored for conformity to this privileged access policy, and that users are only performing activities that have been explicitly authorized.
3. Users of this document are top management and persons who will be granted privileged access to application and processing systems, and those who will be granted privileged access to storage systems storing critical and customer information.
4. The policy applies to all Agile Lab entities and all employees.

# Reference Documents

1. ISMS-01 ISMS Policy

# Roles and Responsibilities

1. The Tech Leader (TL) is responsible for determining the level of logging for audit purposes, reviewing the audit logs for abnormal activities, and System Administrator (SA) will take the appropriate corrective actions to rectify the issues and nonconformities identified.
2. The following table illustrates the document and information types and the corresponding privileged access rights.

| **Appointment** | **Information or Document Types** | **Roles** |
| --- | --- | --- |
| AVP IT &amp; Cyber Security Risk Compliance | Systems, networks, firewall events and access logs, and firewall rules; examples include: <br/>- Firewall logs <br>- Firewall policy (rules) <br/>- Windows OS <br/>- Behaviour monitoring and remediation system <br/>- Financial system | Read, audit and approve |
| Information Security Manager | As above | - Design, specify and modify log templates – record types and level of detail for each record type <br/>- Specify frequency of creation, versioning or updating of (append) systems and events log files <br/>- Archive or delete &quot;old&quot; versions of log files |

# Records Management

| **Record name** | **Storage location** | **Person responsible for storage** | **Controls for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| Systems and events audit logs | Cloud directory;office (hard copy) | TL | TL | 1 year |

# Procedures

1. During information system acquisition, development, implementation and maintenance process, Information Security Manager determines the level of monitoring required for according to a risk assessment, in consultation of the system owner.
2. Information systems, network, and applications processing sensitive information should, at a minimum, enable recording of the following security-related events in an audit log:
    1. Authorized access, including the user ID, the date and time of events, the types of events, the files accessed, the program/utilities used.
    2. All privileged operations, such as use of administrative / supervisor accounts, system start-up and shut-down, input / output device mounting and unmounting.
    3. Unauthorized access attempts, such as failed attempts, access policy violations and notifications for network gateways and firewalls, alerts from intrusion prevention / detection systems.
    4. System alerts or failures, such as: console alerts or messages, system log exceptions, network management alarms.
    5. Changes to, or attempts to change, system security settings and controls.
3. The Information Security Manager ensures that audit logs are securely managed and that no access to amend the logs (other than by the system) must be allowed.
4. The Information Security Manager reviews the audit log on a regular and timely basis, making use of suitable log analysis utilities or audit tools to ensure that the most important events are seen and acted upon. The frequency of log review shall take into consideration of the:
    1. criticality of the application processes;
    2. value, sensitivity or criticality of the information involved;
    3. past experience of system infiltration and misuse;
    4. extent of system interconnection (particularly public networks).
5. Whenever suspicious activities are identified or thresholds of specific security-related events are exceeded, the Information Security Manager shall conduct the appropriate follow-up activities and record the course of action taken. A summary report of information security monitoring should be produced and submitted to the Information Security Working Group for review.
6. For significant security issues or the discovery of signs of successful system intrusion, the Information Security Manager shall report the case to a member of the Information Security Working Group and invoke the Security Incident Handling Procedures.
7. Privileged user accounts must be granted on a &quot;need to know&quot; and least privileged access basis; that is, to give users the minimum amount of privileges needed to perform their jobs adequately.
8. Privileged accounts shall not be used for day-to-day access; like those required to perform daily or periodic administration and/or operation activities.
9. All privileged accounts must be approved and designated to an individual owner for accountability.
10. Privileged accounts and user access rights shall be reviewed on a periodic basis. Particular attention should be given to the security-related event of the log file and facility including:
    1. the logging facility being de-activated;
    2. alterations to the message types that are recorded;
    3. log files being edited or deleted.
11. The Information Security Manager protects the log analysis tools and its output from unauthorized access. Furthermore, he / she must keep the audit logs for a retention periods that can meet the legal, regulatory, and business needs.

# Appendices

None
