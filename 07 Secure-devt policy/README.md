# **Information Security**

| Document Title | Secure Development Policy |
| --- | --- |
| Document No. | ISMS-07 |
| Revision No. | 0.0 |
| Effective Date | 12 December 2020 |
| Classification | Confidential |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
| 12 Dec 2020 | 0.0 | - | Final version for release |
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

| **Prepared By** |
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
| **Reviewed By** |
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
| **Approved By** |
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

[Revision History i](#_Toc58593142)

[1Purpose, Scope And Users 1](#_Toc58593143)

[2Reference Documents 1](#_Toc58593144)

[3Validity And Document Management 1](#_Toc58593145)

[4Secure Development And Maintenance 1](#_Toc58593146)

[4.1Risk assessment for the development process 1](#_Toc58593147)

[4.2Securing the development environment 2](#_Toc58593148)

[4.3Security requirements 2](#_Toc58593149)

[4.4Security requirements related to public networks 2](#_Toc58593150)

[4.5Checking and testing the implementation of security requirements 2](#_Toc58593151)

[4.6Change control 3](#_Toc58593152)

[4.7Protection of test data 3](#_Toc58593153)

[4.8Required security training 3](#_Toc58593154)

[5Records Management 3](#_Toc58593155)

[6Appendices 3](#_Toc58593156)

1.
# Purpose, Scope And Users

1. The purpose of this document is to define the basic rules for secure development of software and systems.
2. This document is applicable to development and maintenance of all services, architecture, software and systems that are part of the Information Security Management System (ISMS).
3. Users of this document are all employees who work on the development and maintenance of technology hardware and software in Agile Lab Pte Ltd (Agile Lab).

1.
# Reference Documents

1. ISO/IEC 27001 standard, clauses A.14.1.2, A.14.1.3, A.14.2.1, A.14.2.2, A.14.2.5, A.14.2.6, A.14.2.7, A.14.2.8, A.14.2.9, A.14.3.1
2. Risk Assessment and Risk Treatment Methodology
3. Operating Procedures For Information and Communication Technology (ICT)
4. Training and Awareness Plan

1.
# Validity And Document Management

1. This document is valid as of the date stated on the cover of this document.
2. The owner of this document is System Administrator (SA), who must check and, if necessary, update the document at least once a year.
3. When evaluating the effectiveness and adequacy of this document, the following criteria must be considered:

1. number of incidents arising from failed security controls built into the systems

1.
# Secure Development And Maintenance

1.
## Risk assessment for the development process

1. In addition to the risk assessment performed according to the Risk Assessment and Risk Treatment Methodology, the SA or Manager, IT &amp; Information Security (MIT) must periodically perform the assessment of the following:

1. the risks related to unauthorized access to the development environment
2. the risks related to unauthorized changes to the development environment
3. technical vulnerabilities of the IT systems used in the organization
4. the risks a new technology might bring if used in the organization

1.
## Securing the development environment

1. The secure development environment is restricted solely for the implementation of new systems or systems upgrades.
2. This is primarily an environment to tests the software and system before implementation and upgrade.
3. The secure environment is provisioned by using a separate network segment for testing.
4. Software may be developed in-house and outsourced to external software vendors.
5. For software developed and hosted by third parties, and used by Agile Lab on a subscription basis, the service provider will also be required to ensure a secure development environment for the implementation of new and upgrade systems.

1.
## Security requirements

1. When acquiring new information systems or developing or changing existing ones, SA or TL must document security requirements in the Security Requirements Specification (see Appendix).
2. This includes in-house developed application and database software; as well as software belonging to Agile Lab that is hosted in external data centres.
3. This also applies to application software and database systems and services subscribed (by Agile Lab) from external software service providers.

1.
## Security requirements related to public networks

1. The SA is responsible for defining security controls related to information in application services passing over public networks:

1. the description of authentication systems to be used
2. the description of how confidentiality and integrity of information is to be ensured
3. the description of how non-repudiation of actions will be ensured

1.
## Checking and testing the implementation of security requirements

1. The SA is responsible to define the methodology, responsibilities and the timing of checking whether all the security requirements from the Security Requirements Specification have been met, and whether the system is acceptable for operations.

1.
## Change control

1. Changes in the development and during the maintenance of the systems must be done according to the Operating Procedures For Information and Communication Technology.

1.
## Protection of test data

1. Confidential data, as well as data that can be related to individual persons must not be used as test data.
2. Exceptions may be approved only by the TL in which case SA must define how such test data are protected.

1.
## Required security training

1. SAdetermines the level of security skills and knowledge required for the implementation process and proposes the trainings to the TL.
2. SAshall include the appropriate trainings in the Training and Awareness Plan.

1.
# Records Management

| **Record name** | **Storage location** | **Person responsible for storage** | **Control for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| System implementation plan | Department cabinet &amp; shared folder | SA | After all data has been recorded, any new additions or editing must be disabled | 1 year |

1.
# Appendices

1. Security Requirements Specification
