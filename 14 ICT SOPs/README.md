# **Information Security**

| Document Title | Operating Procedures for Information and Communication Technology |
| --- | --- |
| Document No. | ISMS-14 |
| Revision No. | 0.0 |
| Effective Date | 12 December 2020 |
| Classification | Confidential |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
| 29 Nov 2019 | 0 | - | Final version for release |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |
|
 |
 |
 |
 |

| **Prepared By:** |
 |
 |
 |
| --- | --- | --- | --- |
|
 | System Administrator | 12 Dec 2020 |
 |
| Name | Designation | Date | Signature |
| --- | --- | --- | --- |
|
| |
| **Reviewed By :** |
 |
 |
 |
| --- | --- | --- | --- |
|
 | Tech Leader | 12 Dec 2020 |
 |
| Name | Designation | Date | Signature |
| --- | --- | --- | --- |
|
| |
| **Approved By :** |
 |
 |
 |
| --- | --- | --- | --- |
|
 | Chief Executive Officer | 12 Dec 2020 |

 |
| Name | Designation | Date | Signature |
| --- | --- | --- | --- |

# Contents

[Revision History i](#_Toc58599237)

[1Purpose, Scope And Users 1](#_Toc58599238)

[2Reference Documents 1](#_Toc58599239)

[3Validity And Document Management 1](#_Toc58599240)

[4Operating Procedures For Information And Communication Technology 1](#_Toc58599241)

[4.1Change Management 1](#_Toc58599242)

[4.2Installation of Software on Operational System 2](#_Toc58599243)

[4.3Backup 3](#_Toc58599244)

[a)Backup Procedure 3](#_Toc58599245)

[b)Testing Backup Copies 4](#_Toc58599246)

[4.4Network Security Management 4](#_Toc58599247)

[b)Network Services 4](#_Toc58599248)

[4.5Disposal And Destruction Of Equipment And Media 4](#_Toc58599249)

[d)Equipment 5](#_Toc58599250)

[e)Mobile Storage Media 5](#_Toc58599251)

[f)Paper Media 5](#_Toc58599252)

[4.6Information Transfer 5](#_Toc58599253)

[a)Electronic Communication Channels 5](#_Toc58599254)

[b)Relations With External Parties 5](#_Toc58599255)

[4.7System Monitoring 6](#_Toc58599256)

[4.8System Access Rights 7](#_Toc58599257)

[5Managing Records 8](#_Toc58599258)

[6Appendices 8](#_Toc58599259)

1.
# Purpose, Scope And Users

1. The purpose of this document is to ensure correct and secure functioning of information and communication technology.
2. This document is applied to the entire Information Security Management System (ISMS) scope, i.e. to all the information and communication technology, as well as to related documentation within the scope.
3. Users of this document are employees of Agile Lab Pte Ltd (Agile Lab) for information and communication technology.

1.
# Reference Documents

1. ISO/IEC 27001 standard, clauses A.8.3.2, A.11.2.7, A.12.1.1, A.12.1.2, A.12.3.1, A.12.4.1, A.12.4.3, A.13.1.1, A.13.1.2, A.13.2.1, A.13.2.2, A.14.2.4
2. Information Security Policy

1.
# Validity And Document Management

1. This document is valid as of the date stated on the cover of this document.
2. The owner of this document is System Administrator (SA), who must check and, if necessary, update the document at least once a year.
3. When evaluating the effectiveness and adequacy of this document, the following criteria must be considered:

1. number of incidents related to the secure functioning of ICT systems
2. number of incidents due to unclear responsibilities for the functioning of ICT systems

1.
# Operating Procedures For Information And Communication Technology

1.
## Change Management

1. A comprehensive set of documents shall be created and/or stored for any additional system that is developed and implemented in-house, or provided by an external vendor.
2. A complete system and network configuration and diagram shall also be created and made available.
3. Essential information for critical servers shall also be provided; including the number and size of partitions, number of cylinders, directory trees, directory names, software extensions, etc.
4. All system and related documentation provided by vendors are to be kept in the computer room. The documentation consists of manuals in physical and electronic formats (e.g. CD).
5. All system or related work performed (including OS upgrade, patching update, etc.) shall be properly recorded in detail in the Daily Log book.
6. Each change to office automation systems and network infrastructure must be made in the following way:

1. change may be proposed by the System Administrator (SA)
2. change must be authorized by the Tech Leader (TL); who must assess its justification for business and potential negative security impacts
3. changes must be implemented by the SA
4. TLis responsible for checking that the change has been implemented in accordance with the requirement
5. SAis responsible for testing and verifying the system&#39;s stability – the system must not be put into production before thorough testing has been conducted
6. implementation of changes must be reported to the TL

1. Each change to facilities management and data centre operation systems and infrastructure must be made in the following way:

1. change may be proposed by the System Administrator (SA)
2. change must be authorized by the Tech Leader (TL); who must assess its justification for business and potential negative security impacts
3. changes must be implemented by the SA
4. TLis responsible for checking that the change has been implemented in accordance with the requirement
5. SAis responsible for testing and verifying the system&#39;s stability – the system must not be put into production before thorough testing has been conducted
6. implementation of changes must be reported to the TL

1.
## Installation of Software on Operational System

1. Any new or upgrade software shall be approved by the CEO, or anyone appointed by the CEO, before the tests and installations may be attempted.
2. Any new or upgrade software shall be tested on a test PC or server in a standalone or independent network before the software may be installed in any user PC or operational server.
3. The test on a PC or server may be conducted in a test environment in the office or one of the vendor&#39;s offices.
4. The test PC or server shall be validated to be operating normally; that is, it is operating without any faults detected or failures during the start-up and normal operation modes.
5. To deploy the new or upgrade software on critical systems with local PC or server level redundancies, the software shall be installed first on the one of the PCs or servers. That is, no software shall be installed concurrently on both primary and secondary PCs or servers.
6. After the installation, one of the PCs or servers, the newly installed or upgraded software shall be checked and tested to verify that it the system is operating normally.
7. If the system cannot operate normally after the upgrade or installation, the software or upgrade installation may be uninstalled and re-installed.
8. If the installation process continues to fail after 3 attempts, the installation shall be terminated.
9. The PC or server shall be recovered to the state prior to the attempted upgrade or new installation.
10. The related issues shall be retested in the test environment.
11. If the issue can be replicated and resolved, the installation of the new software or upgrade may be attempted again on the second PC or server.
12. If the issue cannot be replicated and is unresolved, the installation shall be temporarily suspended, and the software vendor or suppliers shall be consulted and requested to provide a solution.
13. Any revised software versions shall be retested again in the test environment.
14. The test installation shall be validated, and the test server shall operate normally for a test to be concluded as successful test and installation.
15. The software or upgrade installation may resume with the one of the critical PCs or servers.
16. Once the first PC or server is verified to operate normally, the software or upgrade may be installed and tested on the second PC or server.

1.
## Backup

1.
### Backup Procedure

1. Backup copies must be created for all systems identified in the Business Continuity Plan and with the frequency specified in that document.
2. TLis responsible for backing up the information, software and system images.
3. Use backup software to backup automatically to external USB hard disk. Frequency of backup is daily, starting from 8:30 am.
4. Backup USB hard disk will be transferred and stored offsite (Director&#39;s residence). Two backup USB hard disks are used alternately.
5. Logs of the backup process are automatically created on systems where the backup copy is made.

1.
### Testing Backup Copies

1. Backup copies and the process of their restoration must be tested at least once a week. The USB hard disk will be attached to the system, and the ShadowProtect software will be used to validate the backup information.
2. TLis responsible for testing backup copies. Records on testing backup copies are kept in the Offsite Backup Scheduled form.

1.
## Network Security Management

1. TLis responsible for managing and controlling the computer networks, for ensuring the security of information in networks, and for protecting the services connected to the networks from unauthorized access. It is therefore necessary:

1. to separate the operational responsibility for networks from the responsibility for sensitive applications and other systems
2. to segregate network traffic belonging to Agile Lab from other domains – set up unique firewall policies, static routes, virtual local area networks, etc.
3. TLmust regularly monitor and test implemented controls

1.
## Network Services

1. TLmust define security features and the level of expected services for all network services, whether these services are provided in-house or outsourced – such requirements should be documented with service providers.
2. If the network services are outsourced, then the requirements must be specified in the agreement with the service provider.

1.
## Disposal And Destruction Of Equipment And Media

1. All data and licensed software stored on mobile storage media (e.g. USB flash drive and hard disk; but also on paper) and on all equipment containing storage media (e.g. computers, mobile phones, etc.) must be erased or the medium destroyed before it is disposed of or reused.
2. The person responsible for erasing data / destroying media must inform the owner of the asset in question about erasing/destroying, and the asset owner must update the Inventory of Assets.
3. An external service provider may be engaged by the owner of the asset to erase data from the media, and to dispose and destroy equipment and media.
4.
### Equipment

1. TLis responsible for checking and erasing data from equipment, unless the Information Security Policy prescribes differently.
2. Data must be erased by using the erasing tool supplied by manufacturer; but if the process is not secure enough considering the sensitivity of the data, then the storage medium must be destroyed.

1.
### Mobile Storage Media

1. TLis responsible for erasing data from mobile storage media, unless the Information Security Policy prescribes differently.
2. Data must be erased by using the erasing tool supplied by manufacturer; but if the erasure process is not secure enough considering the sensitivity of the data, then the storage medium must be destroyed.

1.
### Paper Media

1. Employees of the organization handling individual documents are responsible for destroying paper documents, unless the Information Security Policy prescribes differently. Paper documents are destroyed by paper shredders.

1.
## Information Transfer

1.
### Electronic Communication Channels

1. Organization&#39;s information may be exchanged through the following electronic communication channels: e-mail, download of files from the Internet, transfer of image files for artwork (via cloud storage), transfer of data (via email and FTP) , telephones, fax machines, SMS text messages, portable media, and forums and social networks.
2. TLdetermines the communication channel that may be used for each type of information, and possible restrictions regarding permissions to use the communication channels, i.e. defines which activities are forbidden.
3. In addition to controls prescribed by the Information Classification Policy, TL prescribes additional controls for each type of data and communication channel, based on risk assessment results.

1.
### Relations With External Parties

1. External parties include various service providers, vendor companies for hardware and software maintenance and clients.
2. Before exchanging information and/or software with any external party, an agreement must be signed, which is the responsibility of TL. The agreement may be in paper or electronic form (e.g. agreeing to general terms and conditions) and must contain clauses in line with the risk assessment, including at least the following:

- method of identification of the other party
- authorizations to access information
- ensuring non-repudiation
- technical standards for data transfer
- incident response
- labeling and handling sensitive information
- copyright

1. Agreements with external parties must be drawn up according to the Supplier Security Policy.

1.
## System Monitoring

1. Office Automation Systems and Network Infrastructure

1. Based on the risk assessment results, TL decides which logs will be kept on which systems and for which systems, and how long they will be stored. Logs must be kept for all sensitive systems.
2. TLis responsible for monitoring the logs of automatically reported faults on a daily basis, as well as to register faults reported by users, to analyze why errors occurred and to take appropriate corrective actions.
3. Specific authorizations may be specified for actions in the case of an error, as well as how records of errors are kept.
4. TLis responsible for regularly reviewing logs in order to monitor the activities of users, administrators and system operators. The review is conducted at intervals prescribed by TL, who determines and selects the records to be reviewed, and how the implemented review will be recorded. TL must be informed about the results of the review.

1. Facilities Management and Data Centre Operation Systems and Infrastructure

1. Based on the risk assessment results, TL decides which logs will be kept on which systems and for which systems, and how long they will be stored. Logs must be kept for all sensitive systems.
2. TLis responsible for monitoring the logs of automatically reported faults on a daily basis, as well as to register faults reported by users, to analyze why errors occurred and to take appropriate corrective actions.
3. Specific authorizations may be specified for actions in the case of an error, as well as how records of errors are kept.
4. TLis responsible for regularly reviewing logs in order to monitor the activities of users, administrators and system operators. The review is conducted at intervals prescribed by TL, who determines and selects the records to be reviewed, and how the implemented review will be recorded. TL must be informed about the results of the review.

1.
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

    1. IT will generate and provide a report listing the users and their access rights granted to each Department Manager.
    2. Each Department Manager shall review access rights report provided by IT, and inform IT to continue and/or update the access rights for each user.
    3. IT will grant or revoke access rights based on the instructions from each Department Manager.

1.
# Managing Records

| **Record name** | **Storage location** | **Person responsible for storage** | **Control for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| Vendor service log for OA systems &amp; network infrastructure | SA&#39;s cabinet | SA | Once created, the record cannot subsequently be changed | 1 year |
| --- | --- | --- | --- | --- |
| Vendor service log for facilities management &amp; data centre operation systems &amp; infrastructure | SA&#39;s cabinet | SA | Once created, the record cannot subsequently be changed | 1 year |
| Backup scheduler and verification logs – paper form | SA&#39;s cabinet | SA | Logs are read-only; they cannot be deleted or edited | Logs are stored for a period of 1 year |

2.
# Appendices

1. Incident Log
2. Daily Log book
