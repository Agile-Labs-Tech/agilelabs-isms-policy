<div align="center"> **Internal** </div>

# **Information Security**

| Document Title | Policy on the Use of Cryptographic Controls |
| --- | --- |
| Organization Name | Agile Lab |
| Document No. | ISMS-09 |
| Revision No. | 0.6 |
| Effective Date | 12 April 2021 |
| Classification | Internal |

## Revision History

| **Date** | **Rev. No.** | **Page No.** | **Description of Amendments** |
| --- | --- | --- | --- |
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

### **Reviewed By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| SzeTho ChangSheng | Information Security Manager | 12 Apr 2021 |
| SzeTho ChangSheng | Information Security Manager | 29 Apr 2022 |

### **Approved By :**
| **Name** | **Designation** | **Date** |
| --- | --- | --- |
| Sujata Liao | Director | 12 Apr 2021 |
| Sujata Liao | Director | 29 Apr 2022 |

# Contents

- [Revision History](#revision-history)

- [Purpose, Scope And Users](#purpose-scope-and-users)

- [Reference Documents](#reference-documents)

- [Validity And Document Management](#validity-and-document-management)

- [Use Of Cryptography](#use-of-cryptography)

- [Cryptographic controls](#cryptographic-controls)

- [Cryptographic keys](#cryptographic-keys)

- [Records Management](#records-management)

- [Appendices](#appendices)

# Purpose, Scope And Users

1. The purpose of this document is to define rules for the use of cryptographic controls, as well as the rules for the use of cryptographic keys, in order to protect the confidentiality, integrity, authenticity and non-repudiation of information.
2. This document is applied to the entire Information Security Management System (ISMS) scope, i.e. to all systems and information used within the ISMS scope.
3. This document is approved and reviewed by the Tech Leader (TL) and System Administrator (SA), respectively.
4. The users of this document are all employees of Agile Lab Pte Ltd (Agile Lab).

# Reference Documents

1. ISO/IEC 27001 standard, clauses A.10.1.1, A.10.1.2, A.18.1.5
2. Information Security Policy
3. List of Legal, Regulatory, Contractual and Other Requirements

# Validity And Document Management

1. This document is valid as of the date stated on the cover of this document.
2. The owner of this document is TL; who must check and, if necessary, update the document at least once a year.
3. When evaluating the effectiveness and adequacy of this document, the following criteria must be considered:
    * number of incidents related to loss, compromise or destruction of cryptographic keys
    * number of systems to which cryptographic controls are applied contrary to this Policy

# Use Of Cryptography

## Cryptographic controls

1. The organization must protect confidential information during transmission by means of cryptographic controls; using password encryption software to encrypt the files containing the information before transmitting them.

1. TL is responsible for preparing instructions on the use of the mentioned cryptographic tools.
2. Owners of individual assets to which cryptographic controls are applied are responsible for appropriate application of individual cryptographic controls.

## Cryptographic keys

1. TL is responsible for prescribing the following rules regarding key management:
    * creation and distribution of cryptographic keys
    * archiving inactive keys which are necessary for encrypted electronic archives
    * destruction of keys

2. Keys are managed by their owners in line with the above mentioned rules.

3. The Department Manager and TL may grant access rights to other users to access key/password management records for a specific user for official company purposes, if required.
3. Cryptographic keys will be protected
    * SA or TL will store the list of cryptographic keys in a secure directory.
    * This secure directory will be accessible only to the SA and TL.
    * The SA or TL may authorize and grant access rights of the key to any other people persons.
4. In the case of loss, corruption or destruction, keys will be recovered
    * The SA or the authorized assistant will retrieve the cryptographic key from the directory.
    * Which shall then be re-issued to the relevant authorized person.

# Records Management

| **Record name** | **Storage location** | **Person responsible for storage** | **Controls for record protection** | **Retention time** |
| --- | --- | --- | --- | --- |
| Key/password management records | <a href="https://1password.com" target="_blank">1Password</a> | Individual users | Centralise Vault management managed by TL | Records are stored until deleted |
| Project credentials management cords | <a href="https://www.akeyless.io/" target="_blank">Akeyless</a> | Individual users | Only individual user and TL has access rights his or her own records | Records are stored for a period of 1 year |
| Rules &amp; instructions on the use and management of the cryptographic tools | Cloud repository | TL | Only TL and SA have the right to edit and publish the instructions | Instructions that are no longer valid are stored for a period of 1 year |

# Appendices

None

<div align="center"> **Internal** </div>
