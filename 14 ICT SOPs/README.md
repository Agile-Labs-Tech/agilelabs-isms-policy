<div align="center"> **Internal** </div>

# **Information Security**

| Document Title | Operating Procedures for Information and Communication Technology |
| --- | --- |
| Organization Name | Agile Labs |
| Document No. | ISMS-14 |
| Revision No. | 0.9 |
| Effective Date | 12 April 2021 |
| Classification | Internal |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
| 21 May 2026 | 0.9 | - | Yearly review |
| 07 Apr 2025 | 0.8 | - | Yearly review |
| 08 Apr 2024 | 0.7 | - | Yearly review |
| 03 May 2023 | 0.6 | - | Yearly review |
| 25 Apr 2022 | 0.5 | - | Yearly review |
| 12 Apr 2021 | 0.4 | - | Update Approved By |
| 03 Apr 2021 | 0.3 | - | Content update |
| 31 Mar 2021 | 0.2 | - | Content update |
| 25 Mar 2021 | 0.1 | - | Final version for release |
| 12 Dec 2020 | 0.0 | - | Initial version for release |

### **Prepared By:**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| Wayne Tng | Technical Leader | 12 Apr 2021 |
| Wayne Tng | Technical Leader | 25 Apr 2022 |
| Wayne Tng | Technical Leader | 03 May 2023 |
| Wayne Tng | Technical Leader | 08 Apr 2024 |
| Wayne Tng | Technical Leader | 07 Apr 2025 |
| Wayne Tng | Technical Leader | 15 May 2026 |

### **Reviewed By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| SzeTho ChangSheng | Information Security Manager | 12 Apr 2021 |
| SzeTho ChangSheng | Information Security Manager | 29 Apr 2022 |
| SzeTho ChangSheng | Information Security Manager | 05 May 2023 |
| SzeTho ChangSheng | Information Security Manager | 22 Apr 2024 |
| SzeTho ChangSheng | Information Security Manager | 14 Apr 2025 |
| SzeTho ChangSheng | Information Security Manager | 21 May 2026 |

### **Approved By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| Sujata Liao | Director | 12 Apr 2021 |
| Sujata Liao | Director | 29 Apr 2022 |
| Sujata Liao | Director | 05 May 2023 |
| Sujata Liao | Director | 22 Apr 2024 |
| Sujata Liao | Director | 14 Apr 2025 |
| Sujata Liao | Director | 21 May 2026 |

# Contents

- [Revision History](#revision-history)

- [Purpose, Scope And Users](#purpose-scope-and-users)

- [Reference Documents](#reference-documents)

- [Validity And Document Management](#validity-and-document-management)

- [Operating Procedures For Information And Communication Technology](#operating-procedures-for-information-and-communication-technology)

  - [Change Management](#change-management)

  - [Installation of Software on Operational System](#installation-of-software-on-operational-system)

    - [Random Checks](#random-checks)

  - [Backup](#backup)

    - [Backup Procedure](#backup-procedure)

  - [Network Security Management](#network-security-management)

  - [Disposal And Destruction Of Equipment And Media](#disposal-and-destruction-of-equipment-and-media)

    - [Equipment](#equipment)

    - [Mobile Storage Media](#mobile-storage-media)

    - [Paper Media](#paper-media)

  - [Information Transfer](#information-transfer)

    - [Electronic Communication Channels](#electronic-communication-channels)

    - [Relations With External Parties](#relations-with-external-parties)

  - [System Monitoring](#system-monitoring)

  - [System Access Rights](#system-access-rights)

- [Managing Records](#Managing Records)

- [Appendices](#appendices)

# Purpose, Scope And Users

1. The purpose of this document is to ensure correct and secure functioning of information and communication technology.
2. This document is applied to the entire Information Security Management System (ISMS) scope, i.e. to all the information and communication technology, as well as to related documentation within the scope.
3. Users of this document are employees of Agile Labs Pte Ltd (Agile Labs for information and communication technology.

# Reference Documents

1. ISO/IEC 27001 standard, clauses A.8.3.2, A.11.2.7, A.12.1.1, A.12.1.2, A.12.3.1, A.12.4.1, A.12.4.3, A.13.1.1, A.13.1.2, A.13.2.1, A.13.2.2, A.14.2.4
2. Information Security Policy

# Validity And Document Management

1. This document is valid as of the date stated on the cover of this document.
2. The owner of this document is Technical Leader (TL), who must check and, if necessary, update the document at least once a year.
3. When evaluating the effectiveness and adequacy of this document, the following criteria must be considered:

    1. number of incidents related to the secure functioning of ICT systems
    2. number of incidents due to unclear responsibilities for the functioning of ICT systems

# Operating Procedures For Information And Communication Technology

## Change Management

1. A comprehensive set of documents shall be created and/or stored for any additional system that is developed and implemented in-house, or provided by an external vendor.
2. A complete system and network configuration and diagram shall also be created and made available.
3. All system and related documentation provided by vendors are to be kept in the secure storage. The documentation consists of manuals in physical and electronic formats (e.g. CD).
4. All system or related work performed (including OS upgrade, patching update, etc.) shall be properly recorded in detail in the Maintenance Log book.
5. Each change to office automation systems and network infrastructure must be made in the following way:

    1. change may be proposed by any member in the Risk Management Commmittee (RMC)
    2. change must be authorized by the Tech Leader (TL); who must assess its justification for business and potential negative security impacts
    3. changes must be implemented by the SA
    4. TL is responsible for checking that the change has been implemented in accordance with the requirement
    5. SA is responsible for testing and verifying the system&#39;s stability – the system must not be put into production before thorough testing has been conducted
    6. implementation of changes must be reported to the TL

## Installation of Software on Operational System

1. Any new or upgrade software shall be approved by the CSO, or anyone appointed by the CSO, before the tests and installations may be attempted.
2. Any new or upgrade software shall be tested on a test PC or server in a standalone or independent network before the software may be installed in any user PC or operational server.
3. The test on a PC or server may be conducted in a test environment in the office or one of the vendor&#39;s offices.
4. The test PC or server shall be validated to be operating normally; that is, it is operating without any faults detected or failures during the start-up and normal operation modes.
5. To deploy the new or upgrade software on critical systems with local PC or server level redundancies, backup must be done first, the software shall then be installed first on the one of the PCs or servers. That is, no software shall be installed concurrently on both primary and secondary PCs or servers.
6. After the installation, one of the PCs or servers, the newly installed or upgraded software shall be checked and tested to verify that it the system is operating normally.
7. If the system cannot operate normally after the upgrade or installation, the software or upgrade installation may be uninstalled and re-installed or rollback.
8. If the installation process continues to fail after 2 attempts, the installation shall be terminated.
9. The PC or server shall be recovered to the state prior to the attempted upgrade or new installation.
10. The related issues shall be retested in the test environment.
11. If the issue can be replicated and resolved, the installation of the new software or upgrade may be attempted again on the second PC or server.
12. If the issue cannot be replicated and is unresolved, the installation shall be temporarily suspended, and the software vendor or suppliers shall be consulted and requested to provide a solution.
13. Any revised software versions shall be retested again in the test environment.
14. The test installation shall be validated, and the test server shall operate normally for a test to be concluded as successful test and installation.
15. The software or upgrade installation may resume with the one of the critical PCs or servers.
16. Once the first PC or server is verified to operate normally, the software or upgrade may be installed and tested on the second PC or server.

### Random Checks

- Random checks will be conducted by TL to ensure that Agile Labs&#39;s staff is following the guidelines.

## Backup

### Backup Procedure

1. Backup copies must be created for all systems identified in the Business Continuity Plan and with the frequency specified in that document.
2. SA is responsible for backing up the information, software and system images for the servers.
3. Each individuals staff is responsible for backing up the information, software and system images for their issued assets.
4. Use backup software([IDrive](https://www.idrive.com)) to backup automatically to Cloud services. Frequency of backup is daily, starting from 00:00 am.
5. Logs of the backup process are automatically created on systems where the backup copy is made.

## Network Security Management

1. SA is responsible for managing and controlling the server networks, for ensuring the security of information in networks, and for protecting the services connected to the networks from unauthorized access. It is therefore necessary:

    1. to separate the operational responsibility for networks from the responsibility for sensitive applications and other systems
    2. SA must regularly monitor and test implemented controls

## Disposal And Destruction Of Equipment And Media

1. All data and licensed software stored on mobile storage media (e.g. USB flash drive and hard disk; but also on paper) and on all equipment containing storage media (e.g. computers, mobile phones, etc.) must be erased or the medium destroyed before it is disposed of or reused.
2. The person responsible for erasing data / destroying media must inform the owner of the asset in question about erasing/destroying, and the asset owner must update the Inventory of Assets.
3. An external service provider may be engaged by the owner of the asset to erase data from the media, and to dispose and destroy equipment and media.
4. ### Equipment

    1. TL is responsible for checking and erasing data from equipment, unless the Information Security Policy prescribes differently.
    2. Data must be erased by using the erasing tool supplied by manufacturer; but if the process is not secure enough considering the sensitivity of the data, then the storage medium must be destroyed.

5. ### Mobile Storage Media

    1. TL is responsible for erasing data from mobile storage media, unless the Information Security Policy prescribes differently.
    2. Data must be erased by using the erasing tool supplied by manufacturer; but if the erasure process is not secure enough considering the sensitivity of the data, then the storage medium must be destroyed.

6. ### Paper Media

    1. Employees of the organization handling individual documents are responsible for destroying paper documents, unless the Information Security Policy prescribes differently. Paper documents are destroyed by paper shredders.

## Information Transfer

### Electronic Communication Channels

1. Organization&#39;s information may be exchanged through the following electronic communication channels: e-mail, download of files from the Internet, transfer of image files for artwork (via cloud storage), transfer of data (via email and SFTP) , telephones, SMS text messages, Slack Channels, portable media, and forums and social networks.
2. TL determines the communication channel that may be used for each type of information, and possible restrictions regarding permissions to use the communication channels.
3. In addition to controls prescribed by the Information Classification Policy, TL prescribes additional controls for each type of data and communication channel, based on risk assessment results.

### Relations With External Parties

1. External parties include various service providers, vendor companies for hardware and software maintenance and clients.
2. Before exchanging information and/or software with any external party, an agreement must be signed, which is the responsibility of ISM. The agreement may be in paper or electronic form (e.g. agreeing to general terms and conditions) and must contain clauses in line with the risk assessment, including at least the following:

    - method of identification of the other party
    - authorizations to access information
    - ensuring non-repudiation
    - technical standards for data transfer
    - incident response
    - labeling and handling sensitive information
    - copyright

3. Agreements with external parties must be drawn up according to the Supplier Security Policy.

## System Monitoring

1. Server monitoring and Network Infrastructure

    1. Based on the risk assessment results, TL decides which logs will be kept on which systems and for which systems, and how long they will be stored. Logs must be kept for all sensitive systems.
    2. TL is responsible for monitoring the logs of automatically reported faults via [Rollbar](https://rollbar.com/) integration when a fault happen, as well as to register faults reported by users, to analyze why errors occurred and to take appropriate corrective actions.
    3. Specific authorizations may be specified for actions in the case of an error, as well as how records of errors are kept.
    4. TL is responsible for regularly reviewing logs in order to monitor the activities of users, administrators and system operators. The review is conducted at intervals prescribed by TL, who determines and selects the records to be reviewed, and how the implemented review will be recorded. TL must be informed about the results of the review.

## System Access Rights

1. The procedures below describe the requirements and process to grant and revoke access rights to systems.
2. The procedures are applicable for the following situations:

| **Category** | **Key Actions** |
| --- | --- |
| New employees | Employees joining the company will be granted access rights to systems based on their job functions, roles and responsibilities. |
| Leaving employees | When the services of an employee ceases, his or her access rights shall be revoked. |
| Change in employee&#39;s job function | An employee&#39;s access rights will be granted and/or revoked based on the his or her roles and responsibilities in the new or amended job junction. |
| Disciplinary and/or investigations | For an employee undergoing investigation, or part of a set of disciplinary actions, his or her access rights may be revoked or temporarily deactivated, if instructions are issued by HR and/or Department Head. |

1. Access rights shall be reviewed annually.

    1. TL will generate and provide a report listing the users and their access rights granted to each Department Manager.
    2. Each Department Manager shall review access rights report provided by IT, and inform IT to continue and/or update the access rights for each user.
    3. TL will grant or revoke access rights based on the instructions from each Department Manager.

# Managing Records

| **Record name** | **Storage location** | **Person responsible for storage** | **Control for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| Vendor service log for OA systems &amp; network infrastructure | Cloud directory | TL | Once created, the record cannot subsequently be changed | 1 year |
| Backup scheduler and verification logs – paper form | Office&#39;s cabinet | TL or Department Head | Logs are read-only; they cannot be deleted or edited | Logs are stored for a period of 1 year |

# Appendices

None

<div align="center"> **Internal** </div>
