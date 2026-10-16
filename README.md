# ISO/IEC 27001:2022 Statement of Applicability

## Project Overview

This project involved the development of an ISO/IEC 27001:2022 Statement of Applicability (SoA) for X LTD, a business-to-business (B2B) Software-as-a-Service (SaaS) company providing data analytics services through cloud infrastructure.

The project focused on assessing the applicability of the 93 information security controls in Annex A of ISO/IEC 27001:2022, documenting the rationale for control selection and exclusion, and establishing traceability between identified information security risks and relevant controls.

The assessment considered the organisation's operating environment, cloud infrastructure, remote working arrangements, information assets, supplier dependencies and identified information security risks. The resulting documentation supports control assessment, risk treatment planning, evidence management and preparation for an independent assessment.

## Organisation Profile

| Attribute                      | Description                                                    |
| ------------------------------ | -------------------------------------------------------------- |
| Organisation                   | X LTD (name redacted for confidentiality)                      |
| Industry                       | B2B SaaS — Data Analytics                                      |
| Workforce                      | 85 employees                                                   |
| Operating Model                | Fully remote                                                   |
| Infrastructure                 | Cloud-based infrastructure hosted on Amazon Web Services (AWS) |
| Customer Base                  | More than 200 enterprise clients                               |
| Data Processing Region         | AWS Europe (Ireland), eu-west-1                                |
| Information Security Objective | ISO/IEC 27001:2022 certification readiness                     |

## Project Objectives

The project addressed the following objectives:

* Assess the applicability of all 93 Annex A controls against the organisation's business and technology environment.
* Document control applicability decisions, implementation status and supporting justifications in a Statement of Applicability.
* Establish traceability between identified information security risks and relevant controls.
* Document and justify controls assessed as not applicable.
* Identify alternative measures where relevant to the treatment of risks associated with excluded controls.
* Establish an evidence reference index to support control verification and audit preparation.
* Prepare documented responses to anticipated auditor questions concerning significant control exclusions.
* Identify risk treatment measures and outstanding implementation or evidence requirements.

## Scope of Assessment

The assessment covered information security arrangements relevant to the organisation's cloud-hosted data analytics platform, including supporting personnel, company-managed endpoint devices, cloud infrastructure, information assets and supplier relationships.

The assessment considered the following areas:

* Information security governance and responsibilities.
* Identity and access management.
* Cloud infrastructure security and configuration management.
* Endpoint protection and remote working.
* Information classification, handling and protection.
* Security incident management and evidence collection.
* Supplier security and cloud service dependencies.
* Business continuity and information backup.
* Legal, regulatory and contractual information security requirements.
* Control implementation, supporting evidence and compliance monitoring.

Particular attention was given to determining whether the organisation's operating model justified excluding specific controls, especially those relating to physical facilities and infrastructure.

## Risk Assessment

The assessment considered six identified information security risks.

| Risk ID | Risk Description                     | Initial Risk Level |
| ------- | ------------------------------------ | ------------------ |
| R-001   | Unauthorised access to customer data | High               |
| R-002   | Employee laptop theft or loss        | Medium             |
| R-003   | Cloud misconfiguration               | Critical           |
| R-004   | Insider threat                       | Medium             |
| R-005   | Third-party breach involving AWS     | High               |
| R-006   | Business continuity failure          | Medium             |

These risks provide the basis for examining relevant controls and identifying risk treatment requirements.

Control mappings are intended to establish traceability between risks and relevant Annex A controls. They do not, by themselves, demonstrate that a risk has been adequately treated or that a control is operating effectively.

## Statement of Applicability Methodology

The Statement of Applicability addresses all 93 Annex A controls across the four control themes established by ISO/IEC 27001:2022.

| Control Theme  | Number of Controls |
| -------------- | -----------------: |
| Organisational |                 37 |
| People         |                  8 |
| Physical       |                 14 |
| Technological  |                 34 |
| **Total**      |             **93** |

Each control is assessed in the context of the organisation's operations, information security risks and applicable requirements.

The assessment distinguishes between applicability and implementation status. A control may be applicable even when implementation remains incomplete. Implementation claims require an appropriate evidential basis.

Where a control is assessed as not applicable, the justification should explain why the control is not necessary to address the organisation's circumstances or meet applicable requirements. Exclusions are not based solely on convenience or the absence of traditional infrastructure.

Alternative measures are considered where relevant to the treatment of associated risks. Their existence does not automatically establish that the risks are adequately controlled.

## Project Deliverables

The project comprises six Excel workbooks and a video walkthrough.

| File                                             | Description                                                                                                                                                 |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `01-Statement-of-Applicability.xlsx`             | Assessment of all 93 Annex A controls, including applicability decisions, justifications, implementation statuses, risk references and evidence references. |
| `02-Control-Exclusions-and-Auditor-Defence.xlsx` | Detailed exclusion justifications, supporting rationale, anticipated auditor questions and documented responses.                                            |
| `03-Alternative-Measures-Mapping.xlsx`           | Mapping of relevant alternative measures to excluded controls and associated information security risks.                                                    |
| `04-Risk-to-Control-Traceability.xlsx`           | Traceability between identified information security risks and relevant Annex A controls.                                                                   |
| `05-Evidence-Reference-Index.xlsx`               | Evidence references, verification status and outstanding evidence requirements for relevant controls.                                                       |
| `06-Risk-Assessment-and-Treatment.xlsx`          | Risk assessments, treatment decisions, proposed actions, risk owners and residual risk assessments where supported by sufficient information.               |

### Video Walkthrough

A Loom walkthrough accompanies the project to explain the assessment approach, significant control decisions and the rationale behind selected exclusions.

**Walkthrough:** [WILL BE INSERTED]

## Assessment Principles

### Risk-Informed Control Selection

Control decisions consider the organisation's operating environment, information security risks, relevant requirements and the purpose of each control.

### Defensible Exclusions

Each exclusion requires a documented rationale that reflects the organisation's circumstances. Controls are not excluded merely because they appear unnecessary at first glance.

### Separation of Applicability and Implementation

Applicability and implementation status are assessed separately. An applicable control is not automatically considered implemented, and an implementation claim requires appropriate supporting evidence.

### Evidence-Based Assessment

Evidence references are used to support verification of control implementation. Where evidence is unavailable or implementation has not been verified, this limitation is documented rather than replaced with an unsupported claim.

### Risk and Control Traceability

The project connects identified risks to relevant controls and proposed treatment measures to support review, prioritisation and accountability.

### Ongoing Review

Control applicability and risk treatment decisions should be reassessed when material changes occur in the organisation's operations, technology, suppliers, contractual obligations or risk environment.

## Project Outcome

The resulting documentation provides a structured basis for reviewing Annex A control applicability, evaluating information security risks, documenting control exclusions, identifying evidence requirements and supporting ISO/IEC 27001:2022 compliance activities.

The workbooks are intended to support management review, implementation planning and preparation for an independent assessment.

## Limitations

The assessment reflects the organisational information and evidence available during the engagement. Conclusions concerning implementation and control effectiveness depend on the supporting records and verification performed.

The preparation of a Statement of Applicability does not, by itself, establish that an organisation has implemented all necessary controls, operates a fully conformant Information Security Management System (ISMS) or has achieved ISO/IEC 27001 certification.

## Standard Reference

**ISO/IEC 27001:2022** — Information security, cybersecurity and privacy protection — Information security management systems — Requirements.

The project addresses the 93 Annex A controls associated with the 2022 edition of the standard.
